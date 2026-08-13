---
title: BuildArray()
second_title: Aspose.Slides for C++ API 참조
description: 배열을 빌드합니다.
type: docs
weight: 2276
url: /ko/system/buildarray/
---
## System::BuildArray() 함수


배열을 빌드합니다.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 빌드할 배열의 요소 타입 |

### 반환 값

ObjectBuilder 로 구성된 배열 구축

## 비고



ArrayPtr<T>를 생성하고 해당 빌더를 반환합니다  
[Object](../object/) 구성을 [Get()](../get/) 호출로 마무리해야 합니다

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)