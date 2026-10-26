---
title: GetNamespace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 테스트의 네임스페이스를 검색합니다.
type: docs
weight: 14
url: /ko/system/testtoolsext/getnamespace/
---
## TestToolsExt::GetNamespace(const char *, const char *, std::string\&) 메서드

지정된 테스트의 네임스페이스를 검색합니다.

```cpp
static bool System::TestToolsExt::GetNamespace(const char *class_name, const char *method_name, std::string &name_space)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| class_name | const char * | 검색할 클래스. |
| method_name | const char * | 검색할 메서드. |
| name_space | std::string\& | 네임스페이스 이름을 넣을 변수, 찾은 경우. |

### 반환 값

테스트 메서드를 찾으면 true, 그렇지 않으면 false.

## 참고

* 구조체 [TestToolsExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)