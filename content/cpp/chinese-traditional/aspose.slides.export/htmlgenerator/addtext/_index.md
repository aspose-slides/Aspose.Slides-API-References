---
title: AddText()
second_title: Aspose.Slides for C++ API 參考文件
description: 將純文字新增至 HTML 檔案，將特殊字元取代為 HTML 實體。換行和空白字元不會被取代。
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/htmlgenerator/addtext/
---
## HtmlGenerator::AddText(System::String) 方法

將純文字新增至 HTML 檔案，將特殊字元取代為 HTML 實體。換行和空白字元不會被取代。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::String text) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要新增的文字。 |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) 方法

將純文字新增至 HTML 檔案，將特殊字元取代為 HTML 實體。換行和空白字元不會被取代。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 要新增的文字。 |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

將純文字新增至 HTML 檔案，將特殊字元取代為 HTML 實體。換行和空白字元不會被取代。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 要新增的文字。 |
| startIndex | **int32_t** | 要新增部分的起始索引。 |
| length | **int32_t** | 要新增部分的長度。 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [HtmlGenerator](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)