---
title: DigitalSignature class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/digitalsignature/
---
## DigitalSignature 類別

已簽名檔案中的數位簽章。

DigitalSignature 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/zh-hant/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | 使用指定的憑證建立新的 DigitalSignature 物件。 |
| [`__init__(self, file_path, password)`](/slides/python-net/zh-hant/aspose.slides/digitalsignature/__init__/#str-str) | 使用指定的憑證檔案路徑和密碼建立新的 DigitalSignature 物件。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`certificate`](/slides/python-net/zh-hant/aspose.slides/digitalsignature/certificate/) | 用於簽署文件的憑證物件。<br/>            唯讀 **System.Security.Cryptography.X509Certificates.X509Certificate2**。 |
| [`is_valid`](/slides/python-net/zh-hant/aspose.slides/digitalsignature/is_valid/) | 如果此數位簽章有效且文件未被竄改，則此值為 true。<br/>            唯讀 **bool**。 |
| [`sign_time`](/slides/python-net/zh-hant/aspose.slides/digitalsignature/sign_time/) | 文件簽署的時間。<br/>            唯讀 **System.DateTime**。 |
| [`comments`](/slides/python-net/zh-hant/aspose.slides/digitalsignature/comments/) | 簽章的目的。<br/>            可讀寫 **str**。 |


### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)