---
title: IProtectionManager class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iprotectionmanager/
---
## IProtectionManager 類別

簡報密碼保護管理。

IProtectionManager 類型公開以下成員：

## 屬性

| Property | 描述 |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/encrypt_document_properties/) | 如果簡報已設定密碼保護，此屬性才有意義。<br/>            為 true 時，文件屬性在簡報檔案中會被加密。<br/>            為 false 時，文件屬性為公開，而簡報則被加密。<br/>            可讀寫 **bool**。 |
| [`is_encrypted`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/is_encrypted/) | 取得一個值，指出此實例是否已加密。<br/>            唯讀 **bool**。 |
| [`is_only_document_properties_loaded`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | 如果簡報檔案已設定密碼保護且此檔案的文件屬性為公開，此屬性才有意義。<br/>            true 表示僅從加密的簡報檔案中載入文件屬性，且不需要使用密碼。<br/>            false 表示整個加密的簡報會在使用正確密碼的情況下載入，而不僅僅載入文件屬性。<br/>            若簡報未加密，則屬性值永遠為 false。<br/>            若加密檔案的文件屬性未公開，則屬性值永遠為 false。<br/>            若 PresentationEx.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值永遠為 false。<br/>            唯讀 **bool**。 |
| [`is_write_protected`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/is_write_protected/) | 取得一個值，指出此簡報是否受寫入保護。<br/>            唯讀 **bool**。 |
| [`encryption_password`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/encryption_password/) | 傳回加密密碼。<br/>            唯讀 **str**。 |
| [`read_only_recommended`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/read_only_recommended/) | 取得或設定唯讀建議。<br/>            可讀寫 **bool**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/encrypt/#str) | 使用指定的密碼加密簡報。 |
| [`remove_encryption(self)`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/remove_encryption/#) | 移除加密。 |
| [`set_write_protection(self, password)`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/set_write_protection/#str) | 使用指定的密碼設定此簡報的寫入保護。 |
| [`remove_write_protection(self)`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/remove_write_protection/#) | 移除此簡報的寫入保護。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/check_write_protection/#str) | 判斷簡報是否受到密碼保護以進行修改。 |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)