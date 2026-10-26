---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/protectionmanager/
---
## ProtectionManager 類別

簡報密碼保護管理。

ProtectionManager 類型公開以下成員：

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/encrypt_document_properties/) | 如果簡報已設定密碼保護，此屬性才有意義。<br/>            為 true 時，文件屬性在簡報檔案中被加密。<br/>            為 false 時，文件屬性為公開，而簡報則被加密。<br/>            讀寫 **bool**。 |
| [`is_encrypted`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/is_encrypted/) | 取得指示此實例是否已加密的值。<br/>            唯讀 **bool**。 |
| [`is_only_document_properties_loaded`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | 如果簡報檔案已設定密碼保護且該檔案的文件屬性為公開，此屬性才有意義。<br/>            true 表示僅從加密的簡報檔案中載入文件屬性，而不使用密碼。<br/>            false 表示使用正確的密碼載入整個加密的簡報，而不僅載入文件屬性。<br/>            如果簡報未加密，則此屬性的值始終為 false。<br/>            如果加密檔案的文件屬性不是公開，則此屬性的值始終為 false。<br/>            如果 Presentation.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性的值始終為 false。<br/>            唯讀 **bool**。 |
| [`is_write_protected`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/is_write_protected/) | 取得指示此簡報是否受寫入保護的值。<br/>            唯讀 **bool**。 |
| [`encryption_password`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/encryption_password/) | 取得用於簡報加密的密碼。<br/>            唯讀 **str**。 |
| [`read_only_recommended`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/read_only_recommended/) | 取得或設定唯讀建議。<br/>            讀寫 **bool**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/encrypt/#str) | 使用指定的密碼加密簡報。 |
| [`remove_encryption(self)`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/remove_encryption/#) | 移除加密。 |
| [`set_write_protection(self, password)`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/set_write_protection/#str) | 使用指定的密碼為此簡報設定寫入保護。 |
| [`remove_write_protection(self)`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/remove_write_protection/#) | 移除此簡報的寫入保護。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/check_write_protection/#str) | 判斷簡報是否受到密碼保護以供修改。 |

### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)