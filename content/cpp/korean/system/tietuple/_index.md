---
title: TieTuple()
second_title: Aspose.Slides for C++ API 참조
description: 일부 값에 바인딩된 튜플을 생성합니다.
type: docs
weight: 3056
url: /ko/system/tietuple/
---
## System::TieTuple(Args\&&...) 함수

일부 값에 바인딩된 튜플을 생성합니다.

```cpp
template<typename...> ValueTuple<Args...> System::TieTuple(Args &&... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | [Tuple](../tuple/) 멤버 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | Args\&&... | [Tuple](../tuple/) 바인딩할 값들. |

### 반환값

주어진 값에 바인딩된 새 튜플.

## 참고

* 클래스 [ValueTuple](../valuetuple/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)