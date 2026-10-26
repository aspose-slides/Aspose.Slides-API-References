---
title: operator>>()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 입력 스트림에서 UTF-8 인코딩을 사용하여 문자열을 가져옵니다.
type: docs
weight: 3004
url: /ko/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String&) function

입력 스트림에서 UTF-8 인코딩을 사용하여 문자열을 가져옵니다.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in | std::istream\& | 입력 스트림 객체(**char**와 함께 **basic_ostream**을 인스턴스화한 것). |
| str | [String](../string/)\& | 입력 스트림에서 읽을 문자열. |

### 반환값

문자열이 추출된 입력 스트림.

## System::operator>>(std::wistream\&, String&) function

입력 스트림에서 문자열을 가져옵니다.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| in | std::wistream\& | 입력 스트림 객체(****wchar_t****와 함께 **basic_ostream**을 인스턴스화한 것). |
| str | [String](../string/)\& | 입력 스트림에서 읽을 문자열. |

### 반환값

문자열이 추출된 입력 스트림.

## 참고

* 클래스 [String](../string/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)