---
title: Get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값으로 원자화된 문자열을 반환합니다.
type: docs
weight: 27
url: /ko/system.xml/nametable/get/
---
## NameTable::Get(const String\&) 메서드


지정된 값으로 원자화된 문자열을 반환합니다.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 찾을 이름입니다. |

### Return Value

원자화된 문자열 객체 또는 문자열이 아직 원자화되지 않은 경우 **nullptr**를 반환합니다.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 메서드


주어진 배열에서 지정된 문자 범위와 동일한 문자를 포함하는 원자화된 문자열을 반환합니다.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 찾을 이름을 포함하는 문자 배열입니다. |
| start | **int32_t** | 이름의 첫 번째 문자를 지정하는 배열에 대한 0 기반 인덱스입니다. |
| len | **int32_t** | 이름의 문자 수입니다. |

### Return Value

원자화된 문자열 또는 문자열이 아직 원자화되지 않은 경우 **nullptr**를 반환합니다. **len**이 0이면 [String::Empty](../../../system/string/empty/)이 반환됩니다.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)