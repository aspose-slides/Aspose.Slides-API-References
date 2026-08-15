---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的憑證建立新的 DigitalSignature 物件。
type: docs
weight: 66
url: /zh-hant/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) 建構子

使用指定的憑證建立新 [DigitalSignature](../) 物件。

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | 將用於簽署簡報的憑證。 |

## DigitalSignature::DigitalSignature(System::String, System::String) 建構子

使用指定的憑證檔案路徑與密碼建立新 [DigitalSignature](../) 物件。

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | 包含憑證的檔案路徑。 |
| password | [System::String](../../../system/string/) | 存取憑證所需的密碼。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* 類別 [DigitalSignature](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)