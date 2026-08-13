---
title: operator()()
second_title: Aspose.Slides for C++ API 참조
description: 현재 위임 컬렉션에 존재하는 모든 위임을 호출합니다. 위임은 컬렉션에 추가된 순서대로 호출됩니다. 연산자는 위임이 실행되는 동안 차단됩니다.
type: docs
weight: 235
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const 메서드


현재 위임 컬렉션에 존재하는 모든 위임을 호출합니다. 위임은 컬렉션에 추가된 순서대로 호출됩니다. 연산자는 위임이 실행되는 동안 차단됩니다.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | ArgumentTypes... | 호출될 위임에 전달할 인수 |

### 반환 값

마지막으로 호출된 위임의 반환 값

## 참조

* 클래스 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)