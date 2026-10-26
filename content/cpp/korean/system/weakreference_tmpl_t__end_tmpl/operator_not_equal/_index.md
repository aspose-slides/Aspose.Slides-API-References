---
title: operator!=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 참조된 객체가 null이 아닌지 확인합니다.
type: docs
weight: 66
url: /ko/system/weakreference_tmpl_t__end_tmpl/operator_not_equal/
---
## WeakReference< T >::operator!=(std::nullptr_t) const 메서드

참조된 객체가 null이 아닌지 확인합니다.

```cpp
bool System::WeakReference<T>::operator!=(std::nullptr_t) const
```

### 반환 값

참조된 객체가 null이 아니면 true, 그렇지 않으면 false.

## WeakReference< T >::operator!=(const WeakReference\<T\>\&) const 메서드

참조된 객체를 다른 WeakReference 클래스 인스턴스와 비교합니다.

```cpp
bool System::WeakReference<T>::operator!=(const WeakReference<T> &other) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) 비교 대상. |

### 반환 값

비교된 객체가 서로 다른 객체를 참조하면 true, 객체가 동일하면 false.

## 관련 항목

* 메서드 [WeakReference](../weakreference/)
* 클래스 [WeakReference< T >](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)