---
title: TryParse()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 문자열을 Guid 객체로 변환하려고 시도합니다.
type: docs
weight: 157
url: /ko/system/guid/tryparse/
---
## Guid::TryParse(const String\&, Guid\&) 메서드

지정된 문자열을 [Guid](../) 객체로 변환하려 시도합니다.

```cpp
static bool System::Guid::TryParse(const String &input, Guid &g)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 변환할 문자열 |
| g | [Guid](../)\& | 성공하면 출력 [Guid](../) 객체. |

### 반환값

입력 문자열이 유효한 [Guid](../)을 나타내면 True, 그렇지 않으면 false.

## 참고

* 클래스 [String](../../string/)
* 클래스 [Guid](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)