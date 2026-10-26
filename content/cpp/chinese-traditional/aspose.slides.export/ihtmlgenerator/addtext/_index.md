---
title: AddText()
second_title: Aspose.Slides for C++ API 參考文件
description: 將純文字新增至 html 檔案中，將特殊字元替換為 html 實體。換行符與空白字元不會被取代。
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/ihtmlgenerator/addtext/
---
## IHtmlGenerator::AddText(System::String) 方法

將純文字新增到 html 檔案中，將特殊字元替換為 html 實體。換行符及空白字元不會被取代。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::String text)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text to add. |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) 方法

將純文字新增到 html 檔案中，將特殊字元替換為 html 實體。換行符及空白字元不會被取代。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Text to add. |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

將純文字新增到 html 檔案中，將特殊字元替換為 html 實體。換行符及空白字元不會被取代。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Text to add. |
| startIndex | **int32_t** | Start index of the portion to add. |
| length | **int32_t** | Length of the portion to add. |

## 參見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [IHtmlGenerator](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)