---
title: ToBase64String()
second_title: Aspose.Slides for C++ API 참조
description: Base-64는 지정된 바이트 배열의 요소를 인코딩하고 인코딩된 데이터를 문자열로 반환합니다.
type: docs
weight: 40
url: /ko/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) 메서드

Base-64는 지정된 바이트 배열의 요소들을 인코딩하고 인코딩된 데이터를 문자열로 반환합니다.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 인코딩할 바이트 배열 |
| insert_line_breaks | **bool** | 각 76개의 Base-64 문자마다 출력 문자열에 줄 바꿈 문자를 삽입할지 여부를 지정합니다 |

### 반환 값

입력 배열의 Base-64 인코딩 표현을 포함하는 문자열

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) 메서드

Base-64는 지정된 바이트 배열의 요소 범위를 인코딩하고 인코딩된 데이터를 문자열로 반환합니다.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 인코딩할 요소 범위를 포함하는 바이트 배열 |
| offset_in | int | 인코딩을 시작하는 입력 배열 내 요소의 인덱스 |
| length | int | 인코딩할 요소 범위의 길이 |
| insert_line_breaks | **bool** | 각 76개의 Base-64 문자마다 출력 문자열에 줄 바꿈 문자를 삽입할지 여부를 지정합니다 |

### 반환 값

입력 배열 요소 범위에 대한 Base-64 인코딩 표현을 포함하는 문자열

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) 메서드

Base-64는 지정된 바이트 배열의 요소들을 인코딩하고 인코딩된 데이터를 문자열로 반환합니다.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 인코딩할 바이트 배열 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 인코딩 데이터의 형식 옵션을 지정합니다 |

### 반환 값

입력 배열의 Base-64 인코딩 표현을 포함하는 문자열

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) 메서드

Base-64는 지정된 바이트 배열의 요소 범위를 인코딩하고 인코딩된 데이터를 문자열로 반환합니다.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 인코딩할 요소 범위를 포함하는 바이트 배열 |
| offset_in | int | 인코딩을 시작하는 입력 배열 내 요소의 인덱스 |
| length | int | 인코딩할 요소 범위의 길이 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 인코딩 데이터의 형식 옵션을 지정합니다 |

### 반환 값

입력 배열 요소 범위에 대한 Base-64 인코딩 표현을 포함하는 문자열

## 관련 보기

* 열거형 [Base64FormattingOptions](../../base64formattingoptions/)
* 타입정의 [ArrayPtr](../../arrayptr/)
* 클래스 [String](../../string/)
* 구조체 [Convert](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)