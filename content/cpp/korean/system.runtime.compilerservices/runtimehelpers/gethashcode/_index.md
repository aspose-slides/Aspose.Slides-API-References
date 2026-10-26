---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "임의 타입에 대한 해시 코드를 가져옵니다. 이를 위해 Object::GetHashCode()를 호출합니다."
type: docs
weight: 1
url: /ko/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) 메서드

임의 유형에 대한 해시 코드를 가져옵니다. 이를 수행하기 위해 [Object::GetHashCode()](../../../system/object/gethashcode/)를 호출합니다.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 해시 코드를 가져올 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/)에서 정보를 가져오기 위해. |

### 반환값

대상 구현에 의해 계산된 해시 코드 값입니다.

## 참조

* 클래스 [SmartPtr](../../../system/smartptr/)
* 클래스 [RuntimeHelpers](../)
* 네임스페이스 [System::Runtime::CompilerServices](../../)
* 라이브러리 [Aspose.Slides](../../../)