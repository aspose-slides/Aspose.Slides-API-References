---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 배열의 요소를 다른 유형으로 캐스팅합니다. From이 SmartPtr 객체인 경우에 대한 오버라이드입니다.
type: docs
weight: 2978
url: /ko/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


지정된 배열의 요소를 다른 유형으로 캐스팅합니다. From이 [SmartPtr](../smartptr/) 객체인 경우에 대한 오버라이드입니다.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | 지정된 배열의 요소를 캐스팅할 대상 유형 |
| From | 캐스팅 대상 배열 요소의 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | 캐스팅할 요소를 포함하는 배열에 대한 공유 포인터 |

### Return Value

새 배열에 대한 포인터이며, 이 배열은 **from**의 요소와 동등한 **To** 유형의 요소를 포함합니다.

Deprecated
:   이 이전 호환성을 위해 추가되었습니다. 대신 ExplicitCast를 사용하십시오.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function


지정된 배열의 요소를 다른 유형으로 캐스팅합니다. From이 Boxable이고 To가 [Object](../object/)[]인 경우에 대한 오버라이드입니다.

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | 지정된 배열의 요소를 캐스팅할 대상 유형 |
| From | 캐스팅 대상 배열 요소의 유형 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | 캐스팅할 요소를 포함하는 배열에 대한 공유 포인터 |

### Return Value

새 배열에 대한 포인터이며, 이 배열은 **from**의 요소와 동등한 **To** 유형의 요소를 포함합니다.

Deprecated
:   이 이전 호환성을 위해 추가되었습니다. 대신 ExplicitCast를 사용하십시오.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* 클래스 [Array](../array/)
* 클래스 [Object](../object/)
* 구조체 [IsSmartPtr](../issmartptr/)
* 구조체 [IsBoxable](../isboxable/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)