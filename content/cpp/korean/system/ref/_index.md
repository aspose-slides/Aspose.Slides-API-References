---
title: Ref()
second_title: Aspose.Slides for C++ API 참조
description: DynamicWeakPtr 객체에 대한 참조를 생성합니다. 함수 인수를 참조로 전달할 때 변환기가 사용합니다.
type: docs
weight: 2458
url: /ko/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) 함수


[DynamicWeakPtr](../dynamicweakptr/) 객체에 대한 참조를 생성합니다. 함수 인수를 참조로 전달할 때 변환기가 사용합니다.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Pointee type. |
| trunkMode | Mode of smart pointer itself. |
| weakLeafs | Indexes of template arguments for which SetTemplateWeakPtr method must be called. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Smart pointer to create reference to. |

### 반환 값

스마트 포인터 참조.

## System::Ref(T\&) 함수


객체에 대한 참조를 얻기 위한 도우미 함수입니다. 할당 후 [System::DynamicWeakPtr](../dynamicweakptr/)가 참조된 객체를 업데이트하도록 보장하는 데 사용됩니다.

```cpp
template<typename T> T & System::Ref(T &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Type to create reference to. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T\& | Value to create reference to. |

### 반환 값

이 함수에 전달된 값에 대한 참조.

## 또 보기

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)