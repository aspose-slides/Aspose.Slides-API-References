---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 때 지정된 문자열을 원자화하고 XmlNameTable에 추가합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

파생 클래스에서 재정의될 때, 지정된 문자열을 원자화하고 [XmlNameTable](../)에 추가합니다.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 추가할 이름을 포함하는 문자 배열 |
| offset | **int32_t** | 이름의 첫 번째 문자를 지정하는 배열의 0부터 시작하는 인덱스 |
| length | **int32_t** | 이름에 포함된 문자 수 |

### 반환값

새로운 원자화된 문자열, 이미 존재한다면 기존 문자열을 반환합니다. 길이가 0이면 [String::Empty](../../../system/string/empty/)가 반환됩니다.

## XmlNameTable::Add(const String\&) method

파생 클래스에서 재정의될 때, 지정된 문자열을 원자화하고 [XmlNameTable](../)에 추가합니다.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 추가할 이름 |

### 반환값

새로운 원자화된 문자열, 이미 존재한다면 기존 문자열을 반환합니다.

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNameTable](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)