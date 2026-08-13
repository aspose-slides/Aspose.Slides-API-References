---
title: FromBase64CharArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Unicode 문자 배열에서 범위로 표시된 base-64 인코딩 데이터를 디코딩합니다.
type: docs
weight: 53
url: /ko/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) 메서드


Unicode 문자 배열에서 범위로 표시된 base-64 인코딩 데이터를 디코딩합니다.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 디코딩할 데이터를 포함하는 배열 |
| offset | int | 디코딩할 범위가 시작되는 입력 배열의 위치 |
| length | int | 디코딩할 범위의 길이 |

### 반환값

디코딩된 데이터를 포함하는 바이트 배열

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)