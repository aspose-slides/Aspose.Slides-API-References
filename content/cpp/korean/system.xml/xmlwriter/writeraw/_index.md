---
title: WriteRaw()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 문자 버퍼에서 원시 마크업을 수동으로 씁니다.
type: docs
weight: 287
url: /ko/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) 메서드

파생 클래스에서 재정의될 경우, 문자 버퍼에서 원시 마크업을 수동으로 씁니다.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 기록할 텍스트를 포함하는 문자 배열입니다. |
| index | **int32_t** | 기록할 텍스트 시작 위치를 나타내는 버퍼 내 위치입니다. |
| count | **int32_t** | 기록할 문자 수입니다. |

## XmlWriter::WriteRaw(const String\&) 메서드

파생 클래스에서 재정의될 경우, 문자열에서 원시 마크업을 수동으로 씁니다.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | 기록할 텍스트를 포함하는 [String](../../../system/string/)입니다. |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlWriter](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)