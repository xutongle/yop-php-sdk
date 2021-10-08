[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyop-platform%2Fyop-php-sdk.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyop-platform%2Fyop-php-sdk?ref=badge_shield)

### 环境依赖
php v5.5+
安装php的mcrypt扩展 openssl，启用模块curl

### 目录结构描述
```
├──src
│   ├── Util                        // 工具类
│   │   ├── AESEncrypter.php        // AES函数集
│   │   ├── Base64Url.php           // Base64Url函数集
│   │   ├── BlowfishEncrypter.php   // 加解密处理
│   │   ├── HttpRequest.php         // Http请求函数集
│   │   ├── HttpUtils.php           // Http处理共通函数集
│   │   ├── StringBuilder.php       // 字符串创建函数集
│   │   ├── StringUtils             // 字符串处理函数集
│   │   └── YopSignUtils.php        // YOP签名共通函数集
│   ├── YopClient.php               // 对称秘钥请求处理函数集
│   ├── YopClient3.php              // 非对称秘钥请求处理函数集
│   ├── YopConfig.php               // YOP配置信息函数集
│   ├── YopRequest.php              // YOP请求处理函数集
│   ├── YopResponse.php             // YOP返回处理函数集
│   ├── test                        // 测试
│   │   ├── Info.php                // PHP环境测试页面
│   │   └── RsaTest.php             // 测试程序页面
│   ├── Readme.txt                  // help
```
### 接口调用说明
请求示例，参考./test/RsaTest.php

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyop-platform%2Fyop-php-sdk.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyop-platform%2Fyop-php-sdk?ref=badge_large)