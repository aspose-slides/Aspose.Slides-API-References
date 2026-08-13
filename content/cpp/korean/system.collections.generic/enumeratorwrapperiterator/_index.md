---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API 레퍼런스
description: 미리 생성된 열거자를 래핑하고 모든 호출을 해당 열거자로 전달하는 반복자입니다.
type: docs
weight: 196
url: /ko/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator 클래스

Iterator that wraps the pre-created enumerator and redirects all calls into it.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Element | Element 형식. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | 현재 반복자를 복제합니다. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | 반복자를 한 단계 앞으로 이동합니다. m_is_end와 m_pointer를 업데이트해야 합니다. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | 두 반복자가 같은 항목을 가리키는지 확인합니다. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | 소멸자. |

## 참조

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)