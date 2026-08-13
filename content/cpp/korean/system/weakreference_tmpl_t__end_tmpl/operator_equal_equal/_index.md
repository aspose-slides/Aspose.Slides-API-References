---
title: operator==()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 참조된 객체가 null인지 확인합니다.
type: docs
weight: 53
url: /ko/system/weakreference_tmpl_t__end_tmpl/operator_equal_equal/
---
## WeakReference< T >::operator==(std::nullptr_t) const 메서드

참조된 객체가 null인지 확인합니다.

```cpp
bool System::WeakReference<T>::operator==(std::nullptr_t) const
```

### 반환 값

참조된 객체가 null이면 True, 그렇지 않으면 false.

## WeakReference< T >::operator==(const WeakReference\<T\>\&) const 메서드

참조된 객체를 다른 WeakReference 클래스 인스턴스와 비교합니다.

```cpp
bool System::WeakReference<T>::operator==(const WeakReference<T> &other) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) 비교 대상. |

### 반환 값

비교된 객체가 같은 객체를 참조하면 True, 그렇지 않으면 false.

## 참고

* 메서드 [WeakReference](../weakreference/)
* 클래스 [WeakReference< T >](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)