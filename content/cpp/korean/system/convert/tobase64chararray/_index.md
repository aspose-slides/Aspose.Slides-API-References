---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Base-64는 지정된 바이트 배열의 요소 범위를 인코딩하고 인코딩된 데이터를 유니코드 문자 배열로 저장합니다.
type: docs
weight: 27
url: /ko/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) 메서드

Base-64는 지정된 바이트 배열의 요소 범위를 인코딩하고 인코딩된 데이터를 유니코드 문자 배열로 저장합니다.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 인코딩할 요소 범위를 포함하는 바이트 배열 |
| offset_in | int | 인코딩할 범위가 시작되는 입력 배열의 요소 인덱스 |
| length | int | 인코딩할 요소 범위의 길이 |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 결과 데이터를 넣을 출력 배열에 대한 상수 참조 |
| offset_out | int | 결과 데이터를 넣기 시작할 출력 배열의 인덱스 |
| insert_line_breaks | **bool** | 매 76개의 Base-64 문자마다 출력 배열에 줄 바꿈 문자를 삽입할지 여부를 지정합니다. |

### 반환값

출력 배열에 기록된 문자 수

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) 메서드

Base-64는 지정된 바이트 배열의 요소 범위를 인코딩하고 인코딩된 데이터를 유니코드 문자 배열로 저장합니다.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 인코딩할 요소 범위를 포함하는 바이트 배열 |
| offset_in | int | 인코딩할 범위가 시작되는 입력 배열의 요소 인덱스 |
| length | int | 인코딩할 요소 범위의 길이 |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 결과 데이터를 넣을 출력 배열에 대한 상수 참조 |
| offset_out | int | 결과 데이터를 넣기 시작할 출력 배열의 인덱스 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 인코딩 데이터의 서식 옵션을 지정합니다. |

### 반환값

출력 배열에 기록된 문자 수

## See Also

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)