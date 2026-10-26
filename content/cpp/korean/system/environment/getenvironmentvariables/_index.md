---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 프로세스와 연관된 모든 환경 변수 이름과 해당 값을 포함하는 사전을 반환합니다.
type: docs
weight: 326
url: /ko/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() 메서드

현재 프로세스와 연관된 모든 환경 변수 이름과 해당 값을 포함하는 사전을 반환합니다.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) 메서드

지정된 위치의 모든 환경 변수 이름과 해당 값을 포함하는 사전을 반환합니다.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 변수의 위치 |

### 반환 값

지정된 위치의 모든 환경 변수 이름과 해당 값을 포함하는 사전

## 참조

* 열거형 [EnvironmentVariableTarget](../../environmentvariabletarget/)
* 클래스 [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* 클래스 [String](../../string/)
* 구조체 [Environment](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)