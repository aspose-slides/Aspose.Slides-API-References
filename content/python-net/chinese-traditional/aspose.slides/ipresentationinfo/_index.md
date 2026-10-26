---
title: IPresentationInfo class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentationinfo/
---
## IPresentationInfo 類別

有關簡報檔案的資訊

IPresentationInfo 型別公開以下成員：

## 屬性

| Property | 說明 |
| :- | :- |
| [`is_encrypted`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/is_encrypted/) | 如果已繫結的簡報已加密則傳回 True，否則傳回 False。<br/>            唯讀 **bool**。 |
| [`is_password_protected`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/is_password_protected/) | 取得表示已繫結的簡報是否受密碼保護以供開啟的值。 |
| [`is_write_protected`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/is_write_protected/) | 取得表示已繫結的簡報是否受寫入保護的值。 |
| [`load_format`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/load_format/) | 取得已繫結的簡報的格式。<br/>            唯讀 [`LoadFormat`](/slides/python-net/zh-hant/aspose.slides/loadformat)。 |

## 方法

| Method | 說明 |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | 將已繫結的簡報寫入串流。 |
| [`write_binded_presentation(self, file)`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | 將已繫結的簡報寫入檔案。 |
| [`check_password(self, password)`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/check_password/#str) | 檢查開啟密碼保護的簡報的密碼是否正確。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/check_write_protection/#str) | 檢查寫入保護的簡報的修改密碼是否正確。 |
| [`read_document_properties(self)`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/read_document_properties/#) | 取得已繫結的簡報的文件屬性。 |
| [`update_document_properties(self, document_properties)`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | 更新已繫結的簡報的屬性。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)