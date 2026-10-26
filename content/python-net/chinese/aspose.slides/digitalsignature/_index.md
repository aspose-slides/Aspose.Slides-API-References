---
title: DigitalSignature class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/digitalsignature/
---
## DigitalSignature 类

已签名文件中的数字签名。

DigitalSignature 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/zh/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | 使用指定的证书创建新的 DigitalSignature 对象。 |
| [`__init__(self, file_path, password)`](/slides/python-net/zh/aspose.slides/digitalsignature/__init__/#str-str) | 使用指定的证书文件路径和密码创建新的 DigitalSignature 对象。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`certificate`](/slides/python-net/zh/aspose.slides/digitalsignature/certificate/) | 用于签署文档的证书对象。<br/>            只读 **System.Security.Cryptography.X509Certificates.X509Certificate2**。 |
| [`is_valid`](/slides/python-net/zh/aspose.slides/digitalsignature/is_valid/) | 如果此数字签名有效且文档未被篡改，则此值为 true。<br/>            只读 **bool**。 |
| [`sign_time`](/slides/python-net/zh/aspose.slides/digitalsignature/sign_time/) | 文档签署的时间。<br/>            只读 **System.DateTime**。 |
| [`comments`](/slides/python-net/zh/aspose.slides/digitalsignature/comments/) | 签名的目的。<br/>            读写 **str**。 |


### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)