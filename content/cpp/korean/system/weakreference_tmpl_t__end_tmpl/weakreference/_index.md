---
title: WeakReference()
second_title: Aspose.Slides for C++ API 참조
description: 기본 생성자.
type: docs
weight: 1
url: /ko/system/weakreference_tmpl_t__end_tmpl/weakreference/
---
## WeakReference< T >::WeakReference() 메서드

기본 생성자.

```cpp
System::WeakReference<T>::WeakReference()
```

## WeakReference< T >::WeakReference(std::nullptr_t) 메서드

nullptr에서 생성자.

```cpp
System::WeakReference<T>::WeakReference(std::nullptr_t)
```

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&) 메서드

WeakReference 클래스의 새 인스턴스를 초기화하고, 지정된 객체를 참조합니다.

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/)를 저장할. |

## WeakReference< T >::WeakReference(const SmartPtr\<T\>\&, bool) 메서드

WeakReference 클래스의 새 인스턴스를 초기화하고, 지정된 객체를 참조합니다.

```cpp
System::WeakReference<T>::WeakReference(const SmartPtr<T> &data, bool trackResurrection)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [SmartPtr](../../smartptr/)\<T\>\& | [Object](../../object/)를 저장할. |
| trackResurrection | **bool** | 무시됩니다. |

## 참고

* 클래스 [WeakReference< T >](../)
* 클래스 [SmartPtr](../../smartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)