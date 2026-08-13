---
title: Build()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 직접 소유권을 가진 객체를 생성합니다.
type: docs
weight: 2289
url: /ko/system/build/
---
## System::Build(Args\&&...) 함수

직접 소유권을 가진 객체를 생성합니다.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 생성할 객체의 타입 |
| Args | 객체 생성에 대한 인수 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | Args\&&... | 객체 생성자에 전달할 인수 |

### 반환값

직접 객체 생성을 위해 구성된 ObjectBuilder
## 비고

[Object](../object/) 구성은 [Get()](../get/) 호출로 완료되어야 합니다

## 또한 보기

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)