---
title: IsTest()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 테스트 메서드가 존재하는지 확인합니다.
type: docs
weight: 1
url: /ko/system/testtoolsext/istest/
---
## TestToolsExt::IsTest(const char *, const char *, const char *) 메서드

테스트 메서드가 존재하는지 확인합니다.

```cpp
static bool System::TestToolsExt::IsTest(const char *name_space, const char *class_name, const char *method_name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name_space | const char * | 찾을 네임스페이스입니다. |
| class_name | const char * | 찾을 클래스입니다. |
| method_name | const char * | 찾을 메서드입니다. |

### 반환값

테스트 메서드가 등록되어 있으면 true, 그렇지 않으면 false.

## TestToolsExt::IsTest(const char *, const char *) 메서드

테스트 메서드가 존재하는지 확인합니다.

```cpp
static bool System::TestToolsExt::IsTest(const char *class_name, const char *method_name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| class_name | const char * | 찾을 클래스입니다. |
| method_name | const char * | 찾을 메서드입니다. |

### 반환값

테스트 메서드가 등록되어 있으면 true, 그렇지 않으면 false.

## 참조

* 구조체 [TestToolsExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)