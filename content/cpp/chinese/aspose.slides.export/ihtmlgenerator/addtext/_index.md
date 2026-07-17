---
title: AddText()
second_title: Aspose.Slides for C++ API 参考
description: 将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。
type: docs
weight: 92
url: /zh/aspose.slides.export/ihtmlgenerator/addtext/
---
## IHtmlGenerator::AddText(System::String) 方法

将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::String text)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要添加的文本。 |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) 方法

将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 要添加的文本。 |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 要添加的文本。 |
| startIndex | **int32_t** | 要添加部分的起始索引。 |
| length | **int32_t** | 要添加部分的长度。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [IHtmlGenerator](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)