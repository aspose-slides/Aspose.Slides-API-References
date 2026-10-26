---
title: BuildObject()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 공유 소유권을 가진 객체를 빌드합니다.
type: docs
weight: 2250
url: /ko/system/buildobject/
---
## System::BuildObject(Args\&&...) 함수

공유 소유권을 가진 객체를 빌드합니다.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 빌드할 객체의 유형 |
| Args | 객체 생성에 대한 인수 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | 객체 생성자에 전달할 인수 |

### 반환 값

ObjectBuilder configured for shared pointer construction

## 비고

SharedPtr<T>를 생성하고 해당 빌더를 반환합니다
[Object](../object/) 생성은 [Get()](../get/) 호출로 완료해야 합니다

## 참고

* Typedef [SharedPtr](../sharedptr/)
* 네임스페이스 [System](../)
* Library [Aspose.Slides](../../)