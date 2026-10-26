---
title: ArrayInitializerCast()
second_title: Aspose.Slides C++ API 참조
description: 배열 기본 값을 변환합니다 (C#에서는 암시적으로 수행되지만 C++에서는 그렇지 않은 것으로 보입니다).
type: docs
weight: 209
url: /ko/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) 메서드

배열 기본 값을 변환합니다 (C#에서는 암시적으로 수행되지만 C++에서는 그렇지 않은 것으로 보입니다).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| To | 대상 유형. |
| From | 소스 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | From ... | 변환하여 대상 배열에 푸시할 값들. |

### 반환 값

[Array](../../array/)는 동일한 순서로 모든 인수의 변환된 복사본을 포함합니다.

## 참고

* 클래스 [ObjectExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)