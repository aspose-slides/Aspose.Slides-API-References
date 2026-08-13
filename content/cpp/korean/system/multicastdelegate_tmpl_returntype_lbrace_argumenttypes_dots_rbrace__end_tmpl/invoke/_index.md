---
title: invoke()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 delegate 컬렉션에 존재하는 모든 delegate를 호출합니다. delegate는 컬렉션에 추가된 순서대로 호출됩니다. 메서드는 delegate가 실행되는 동안 블록됩니다.
type: docs
weight: 222
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const method


현재 delegate 컬렉션에 존재하는 모든 delegate를 호출합니다. delegate는 컬렉션에 추가된 순서대로 호출됩니다. 메서드는 delegate가 실행되는 동안 블록됩니다.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | ArgumentTypes... | 호출될 delegate에 전달할 인수 |

### 반환값

마지막으로 호출된 delegate의 반환값

## 참조

* 클래스 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)