---
title: operator<()
second_title: Aspose.Slides for C++ API 참조
description: SmartPtr 클래스에 대한 less-compare 의미를 제공합니다.
type: docs
weight: 235
url: /ko/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const 메서드

[SmartPtr](../) 클래스를 위한 less-compare 의미를 제공합니다.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 현재 포인터와 비교할 포인터 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | Y * | 현재 포인터와 비교할 포인터. |

### 반환값

[SmartPtr](../)가 참조하는 객체가 p보다 '작은' 경우 True이며, 그렇지 않으면 false.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const 메서드

[SmartPtr](../) 클래스를 위한 less-compare 의미를 제공합니다.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 현재 포인터와 비교할 포인터 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | 현재 포인터와 비교할 포인터. |

### 반환값

[SmartPtr](../)가 참조하는 객체가 x보다 '작은' 경우 True이며, 그렇지 않으면 false.

## 참고

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)