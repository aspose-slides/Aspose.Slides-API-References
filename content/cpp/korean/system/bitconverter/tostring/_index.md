---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 바이트 배열의 모든 값을 16진수 문자열 표현으로 변환합니다. 16진수 표기에서 사용할 문자의 대소문자와 인접한 바이트 쌍 사이에 삽입되는 구분자는 해당 인수를 통해 지정됩니다.
type: docs
weight: 157
url: /ko/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method


지정된 바이트 배열의 모든 값을 16진수 문자열 표현으로 변환합니다. 16진수 표기에서 사용할 대문자 여부와 인접한 바이트 쌍 사이에 삽입되는 구분자는 해당 인수를 통해 지정됩니다.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| uppercase | **bool** | 결과 16진수 표현에 사용할 문자 대소문자를 지정합니다. |
| separator | const [String](../../string/)\& | 결과 문자열에서 인접한 바이트 쌍 사이에 삽입되는 구분자로 사용되는 문자열 |

### 반환값

[String](../../string/) 지정된 바이트 배열의 16진수 표현을 포함합니다.

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method


지정된 인덱스부터 시작하여 지정된 바이트 배열의 값을 16진수 문자열 표현으로 변환합니다.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환을 시작할 지정된 배열 내의 인덱스 |

### 반환값

[String](../../string/) 지정된 배열의 지정된 범위 요소들의 16진수 표현을 포함합니다.

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method


지정된 바이트 배열의 값 범위를 16진수 문자열 표현으로 변환합니다.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환할 바이트 배열 요소 범위가 시작되는 지정된 배열 내의 인덱스 |
| length | int | 변환할 바이트 배열 요소 범위의 길이 |

### 반환값

[String](../../string/) 지정된 배열의 지정된 범위 요소들의 16진수 표현을 포함합니다.

## 참조

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [String](../../string/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)