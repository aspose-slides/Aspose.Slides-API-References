---
title: IsSmartPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: 타입이 SmartPtr 클래스의 특수화인지 확인하는 특성 클래스.
type: docs
weight: 1704
url: /ko/system/issmartptr/
---
## IsSmartPtr 구조체

특성 클래스를 사용하여 유형이 [SmartPtr](../smartptr/) 클래스의 특수화인지 확인합니다.

```cpp
template<class T>class IsSmartPtr : public System::detail::is_a<T, System::SmartPtr>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 테스트된 클래스. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)