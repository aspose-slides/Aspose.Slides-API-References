---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열을 원자화하고 NameTable에 추가합니다.
type: docs
weight: 14
url: /ko/system.xml/nametable/add/
---
## NameTable::Add(const String\&) 메서드


지정된 문자열을 원자화하고 [NameTable](../)에 추가합니다.

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | 추가할 문자열입니다. |

### 반환값

원자화된 문자열 또는 이미 [NameTable](../)에 존재하는 경우 기존 문자열을 반환합니다.

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 메서드


지정된 문자열을 원자화하고 [NameTable](../)에 추가합니다.

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 추가할 문자열을 포함하는 문자 배열입니다. |
| start | **int32_t** | 문자열의 첫 번째 문자를 지정하는 0 기반 배열 인덱스입니다. |
| len | **int32_t** | 문자열의 문자 수입니다. |

### 반환값

원자화된 문자열 또는 이미 [NameTable](../)에 존재하는 경우 기존 문자열을 반환합니다. len이 0이면 [String::Empty](../../../system/string/empty/)가 반환됩니다.

## 또보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)