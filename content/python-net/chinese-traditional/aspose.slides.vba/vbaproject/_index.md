---
title: VbaProject class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.vba/vbaproject/
---
## VbaProject 類別

Represents VBA project with presentation macros.

The VbaProject type exposes the following members:

## 建構子

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/__init__/#) | 此建構函式從頭建立新的 VBA 專案。<br/>            專案將以 1252 Windows Latin 1 (ANSI) 代碼頁建立 |
| [`__init__(self, data)`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/__init__/#bytes) | 此建構函式從 OLE 容器的二進位表示載入 VBA 專案。 |

## 屬性

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/name/) | 傳回 VBA 專案的名稱。<br/>            唯讀 **str**. |
| [`modules`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/modules/) | 傳回 VBA 專案中包含的所有模組的清單。<br/>            唯讀 [`IVbaModuleCollection`](/slides/python-net/zh-hant/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/references/) | 傳回 VBA 專案中包含的所有參考的清單。<br/>            唯讀 [`IVbaReferenceCollection`](/slides/python-net/zh-hant/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/is_password_protected/) | 指示 VBAProject 是否受密碼保護以檢視專案屬性。<br/>            唯讀 **bool**. |

## 方法

| Method | Description |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/zh-hant/aspose.slides.vba/vbaproject/to_binary/#) | 傳回 VBA 專案作為 OLE 容器的二進位表示 |


### 另請參閱
* 模組 [`aspose.slides.vba`](/slides/python-net/zh-hant/aspose.slides.vba)
* 函式庫 [`Aspose.Slides`](/slides/python-net)