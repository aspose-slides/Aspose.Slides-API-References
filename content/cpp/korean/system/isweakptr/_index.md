---
title: IsWeakPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: "특정 클래스가 System::WeakPtr의 특수화인지 확인하는 Traits 클래스입니다. 인스턴스가 실제로 약한 모드에 있는지는 확인하지 않습니다."
type: docs
weight: 1756
url: /ko/system/isweakptr/
---
## IsWeakPtr 구조체


특정 클래스가 [System::WeakPtr](../weakptr/)의 특수화인지 확인하는 Traits 클래스입니다. 인스턴스가 실제로 약한 모드에 있는지는 확인하지 않습니다.

```cpp
template<class T>class IsWeakPtr : public System::detail::is_a<T, System::WeakPtr>
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 테스트된 타입. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)