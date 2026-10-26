---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열 문자를 기존 배열 요소에 복사합니다. 크기 조정은 수행되지 않습니다.
type: docs
weight: 430
url: /ko/system/string/copyto/
---
## String::CopyTo(int, const ArrayPtr\<char_t\>\&, int, int) const method

문자열 문자를 기존 배열 요소에 복사합니다. 크기 조정은 수행되지 않습니다.

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceIndex | int | 읽기를 시작할 문자열 인덱스. |
| destination | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 대상 배열. |
| destinationIndex | int | 쓰기 시작할 배열 인덱스. |
| count | int | 복사할 문자 수. |

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)