---
title: ValueIterator
second_title: Aspose.Slides C++ API 레퍼런스
description: 값 접근을 제공하는 사전 반복자.
type: docs
weight: 625
url: /ko/system.collections.generic/valueiterator/
---
## ValueIterator 클래스

[Dictionary](../dictionary/) 값 접근을 제공하는 반복자.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 클래스. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | 현재 반복자를 복제합니다. |
| void [DecrementIterator](./decrementiterator/)() override | 반복자를 한 단계 뒤로 이동시킵니다. |
| void [IncrementIterator](./incrementiterator/)() override | 반복자를 한 단계 앞으로 이동시킵니다. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 반복자를 지정된 단계 수만큼 이동시킵니다. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 생성자. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 생성자. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | 이동 생성자. |
| virtual  [~ValueIterator](./~valueiterator/)() | 소멸자. |

## 참조

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)