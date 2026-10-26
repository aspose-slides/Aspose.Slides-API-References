---
title: ToByteArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열 또는 부분 문자열을 바이트 배열로 변환합니다.
type: docs
weight: 508
url: /ko/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const 메서드

문자열 또는 부분 문자열을 바이트 배열로 변환합니다.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 부분 문자열 시작 인덱스. |
| length | **int32_t** | 부분 문자열 길이. |
| LE | **bool** | true이면 문자를 리틀 엔디안으로 인코딩하고, 그렇지 않으면 빅 엔디안으로 인코딩합니다. |

### 반환 값

[Array](../../array/) 문자열의 문자를 나타내는 바이트를 포함합니다.

## 추가 참조

* typedef [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)