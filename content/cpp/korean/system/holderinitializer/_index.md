---
title: HolderInitializer
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 클래스는 객체 인스턴스에 대한 영구적인 참조를 얻기 위해 사용됩니다. 객체가 lvalue이든 rvalue이든 상관없습니다. 이러한 참조를 얻으려면 'HoldIfTemporary' 메서드를 사용하십시오. 이 메서드에는 세 가지 오버로드가 있습니다. 두 개는 rvalue를 매개변수로 받아 그대로 그 참조를 반환합니다. 세 번째는 반대로 lvalue를 매개변수로 받아 포인터 복사를 수행한 뒤 그 복사본에 대한 참조를 반환합니다. 또한, 클래스에는 전달된 값을 무조건 보유하는 'Hold' 메서드가 있습니다(스택에 있는 로컬 변수나 해당 변수의 자식 참조를 복사하는 데 사용됩니다).
type: docs
weight: 1639
url: /ko/system/holderinitializer/
---
## HolderInitializer struct


이 클래스는 객체 인스턴스에 대한 영구적인 참조를 얻기 위해 사용됩니다. 객체가 lvalue이든 rvalue이든 상관없습니다. 이러한 참조를 얻으려면 'HoldIfTemporary' 메서드를 사용하십시오. 이 메서드에는 세 가지 오버로드가 있습니다. 두 개는 rvalue를 매개변수로 받아 그대로 그 참조를 반환합니다. 세 번째는 반대로 lvalue를 매개변수로 받아 포인터 복사를 수행한 뒤 그 복사본에 대한 참조를 반환합니다. 또한, 클래스에는 전달된 값을 무조건 보유하는 'Hold' 메서드가 있습니다(스택에 있는 로컬 변수나 그 자식 참조를 복사하는 데 사용됩니다).

```cpp
template<typename T,bool>class HolderInitializer
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 보관될 객체의 유형 |
| R | T가 참조 유형([SmartPtr](../smartptr/) 특수화 또는 [System::String](../string/) 유형)인 경우 true이며, 임시 참조 보관이 실제로 필요한 경우, 그렇지 않으면 false |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | 전달된 lvalue를 홀더에 복사한 후 홀더 참조를 반환합니다. 호출자는 이 메서드를 사용하여 전달된 값을 무조건 보관해야 합니다. |
|  [HolderInitializer](./holderinitializer/)(T\&) | 전달된 값으로 홀더 참조를 초기화합니다. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | rvalue에 대한 참조(const)를 반환합니다. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | rvalue에 대한 참조(비-const)를 반환합니다. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | 전달된 lvalue를 홀더에 복사한 후 홀더 참조를 반환합니다. |

## 참조

* 네임스페이스 [System](../)
* Library [Aspose.Slides](../../)