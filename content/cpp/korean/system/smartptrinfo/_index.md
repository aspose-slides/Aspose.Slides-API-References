---
title: SmartPtrInfo
second_title: Aspose.Slides for C++ API 레퍼런스
description: 최종 타입을 알지 못한 상태에서도 SmartPtr의 내용을 테스트하고 변경하는 서비스 클래스입니다. 가비지 컬렉션 및 루프 참조 탐지 등에 사용됩니다. 'pointer to pointer'와 같은 개념으로 생각하십시오. SmartPtr의 기본 타입을 사용할 수 없으므로(기본 타입이 없기 때문에) 대신 이 'info' 클래스를 사용합니다.
type: docs
weight: 1249
url: /ko/system/smartptrinfo/
---
## SmartPtrInfo 클래스

Service class to test and alter [SmartPtr](../smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](../smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class.

```cpp
class SmartPtrInfo
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | 참조된 포인터가 가리키는 원시 객체를 가져옵니다. |
| [Object](../object/) * [getObject](./getobject/)() const | 참조된 포인터가 가리키는 객체를 가져옵니다. |
| [Object](../object/) * [getOwned](./getowned/)() const | 소유된 포인터가 가리키는 객체를 가져옵니다. |
| [operator bool](./operator_bool/)() const | info 객체가 null이 아닌 포인터를 가리키는지 확인합니다. |
| **bool** [operator!](./operator_not/)() const | info 객체가 null이 아닌 포인터를 가리키지 않는지 확인합니다. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | 참조된 포인터가 가리키는 [Object](../object/)의 메서드를 호출할 수 있습니다. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | 두 info 객체가 참조하는 포인터 값들을 비교합니다. |
| [SmartPtrInfo](./smartptrinfo/)() | 빈 [SmartPtrInfo](./) 객체를 생성합니다. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | 특정 스마트 포인터에 대한 정보를 가진 [SmartPtrInfo](./) 객체를 생성합니다. |

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)