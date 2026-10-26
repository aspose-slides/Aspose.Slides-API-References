---
title: PresentationInfo class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentationinfo/
---
## PresentationInfo 類別

關於簡報檔案的資訊

PresentationInfo 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_encrypted`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/is_encrypted/) | 取得 True 如果綁定的簡報已加密，否則為 False。<br/>            唯讀 **bool**. |
| [`is_password_protected`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/is_password_protected/) | 取得一個值，表示綁定的簡報是否受開啟密碼保護。 |
| [`is_write_protected`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/is_write_protected/) | 取得一個值，表示綁定的簡報是否受寫入保護。 |
| [`load_format`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/load_format/) | 取得綁定的簡報的格式。<br/>            唯讀 [`LoadFormat`](/slides/python-net/zh-hant/aspose.slides/loadformat). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | 將綁定的簡報寫入串流。 |
| [`write_binded_presentation(self, file)`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/write_binded_presentation/#str) | 將綁定的簡報寫入檔案。 |
| [`check_password(self, password)`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/check_password/#str) | 檢查提供的密碼是否正確，以開啟受開啟密碼保護的簡報。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/check_write_protection/#str) | 檢查提供的修改密碼是否正確，以寫入受保護的簡報。 |
| [`read_document_properties(self)`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/read_document_properties/#) | 取得綁定的簡報的文件屬性。 |
| [`update_document_properties(self, document_properties)`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | 更新綁定的簡報的屬性。 |


### 相關參考
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)