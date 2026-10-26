---
title: Get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 배열의 지정된 문자 범위와 동일한 문자를 포함하는 원자화된 문자열을 가져옵니다.
type: docs
weight: 1
url: /ko/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 메서드

파생 클래스에서 재정의될 경우, 지정된 배열에서 지정된 문자 범위와 동일한 문자를 포함하는 원자화된 문자열을 가져옵니다.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 찾을 이름을 포함하는 문자 배열입니다. |
| offset | **int32_t** | 이름의 첫 번째 문자를 지정하는 배열의 0 기반 인덱스입니다. |
| length | **int32_t** | 이름의 문자 수입니다. |

### 반환값

원자화된 문자열 또는 문자열이 아직 원자화되지 않은 경우 **nullptr**를 반환합니다. **length**가 0이면 [String::Empty](../../../system/string/empty/)이 반환됩니다.

## XmlNameTable::Get(const String&) 메서드

파생 클래스에서 재정의될 경우, 지정된 문자열과 동일한 값을 포함하는 원자화된 문자열을 가져옵니다.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 찾을 이름입니다. |

### 반환값

원자화된 문자열 또는 문자열이 아직 원자화되지 않은 경우 **nullptr**를 반환합니다.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNameTable](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)