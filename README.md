**京东联盟SDK**

API列表地址：https://union.jd.com/#/openplatform/api


封装了基础权限的API，未获得高级权限


### 使用

`composer require yumufeng/jd-union-sdk`


示例如下：
```php
$config = [
    'appkey' => '',
    'appSecret' => '',
];

$client = new \JdMediaSdk\JdFatory($config);

//获取商品
$goods = $client->good->Info(['3480573']);

如果有错误将会返回false
if (!$result){
     var_dump($client->getError());
}

```
### 联系

哪位大佬，能提供一下高级权限的，可以联系我
QQ：445328312 (京东联盟权限)
