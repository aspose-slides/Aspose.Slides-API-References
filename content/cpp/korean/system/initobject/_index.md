---
title: InitObject()
second_title: Aspose.Slides for C++ API 참조
description: 공유 소유권을 가진 객체의 초기화를 시작합니다.
type: docs
weight: 2263
url: /ko/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) function

공유 소유권을 가진 객체의 초기화를 시작합니다.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Type of object to initialize |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) to initialize |

### 반환 값

ObjectBuilder configured for shared pointer construction

## 비고

[Object](../object/) 초기화는 [Get()](../get/) 호출로 완료되어야 합니다

## 참조

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)