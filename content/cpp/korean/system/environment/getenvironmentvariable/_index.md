---
title: GetEnvironmentVariable()
second_title: Aspose.Slides for C++ API 참조
description: 현재 프로세스와 연결된 지정된 환경 변수의 값을 반환합니다.
type: docs
weight: 287
url: /ko/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) 메서드

현재 프로세스와 연결된 지정된 환경 변수의 값을 반환합니다.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| variable | const [String](../../string/)\& | 검색할 변수 이름을 포함하는 문자열 |

### 반환값

지정된 변수의 값

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) 메서드

지정된 위치에서 지정된 환경 변수의 값을 반환합니다.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| variable | const [String](../../string/)\& | 검색할 변수 이름을 포함하는 문자열 |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 변수가 위치한 장소 |

### 반환값

지정된 변수의 값

## 관련 보기

* 열거형 [EnvironmentVariableTarget](../../environmentvariabletarget/)
* 클래스 [String](../../string/)
* 구조체 [Environment](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)