---
title: operator=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 14
url: /ko/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_equal/
---
## Delegate< ReturnType(ArgumentTypes...)>::operator=(const Delegate\&) 메서드




```cpp
Delegate & System::Delegate<ReturnType(ArgumentTypes...)>::operator=(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::operator=(Delegate\&&) 메서드


Moving assignment operator. 지정된 delegate가 가리키는 엔터티의 소유권을 가져옵니다.

```cpp
Delegate & System::Delegate<ReturnType(ArgumentTypes...)>::operator=(Delegate &&o) noexcept
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | [Delegate](../delegate/)\&& | Delegate 객체에서 가리키는 엔터티를 이동합니다 |

### 반환 값

자신에 대한 참조

## 관련 항목

* 메서드 [Delegate](../delegate/)
* 클래스 [Delegate< ReturnType(ArgumentTypes...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)