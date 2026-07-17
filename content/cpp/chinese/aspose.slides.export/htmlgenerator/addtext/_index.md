---
title: AddText()
second_title: Aspose.Slides C++ API 参考
description: 向 HTML 文件添加纯文本，将特殊字符替换为 HTML 实体。换行符和空白字符不会被替换。
type: docs
weight: 92
url: /zh/aspose.slides.export/htmlgenerator/addtext/
---
## HtmlGenerator::AddText(System::String) 方法


向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::String text) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要添加的文本。 |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) 方法


向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 要添加的文本。 |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) 方法


向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 要添加的文本。 |
| startIndex | **int32_t** | 要添加部分的起始索引。 |
| length | **int32_t** | 要添加部分的长度。 |

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [HtmlGenerator](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)