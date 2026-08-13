---
title: WriteRaw()
second_title: Aspose.Slides for C++ API 참조
description: 문자 버퍼에서 원시 마크업을 수동으로 씁니다.
type: docs
weight: 417
url: /ko/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) 메서드

문자 버퍼에서 원시 마크업을 수동으로 씁니다.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 쓰기를 위한 텍스트를 포함하는 문자 배열입니다. |
| index | **int32_t** | 버퍼 내에서 쓰기를 시작할 텍스트의 시작 위치를 나타냅니다. |
| count | **int32_t** | 작성할 문자 수입니다. |

## XmlTextWriter::WriteRaw(const String\&) 메서드

문자열에서 원시 마크업을 수동으로 씁니다.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) 작성할 텍스트를 포함합니다. |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)