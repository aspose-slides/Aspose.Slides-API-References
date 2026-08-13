---
title: DictionaryIterator
second_title: Aspose.Slides for C++ API 레퍼런스
description: KeyValuePair 표기법을 제공하는 사전 이터레이터.
type: docs
weight: 157
url: /ko/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator 클래스

[Dictionary](../dictionary/) [KeyValuePair](../keyvaluepair/) 표기법을 제공하는 이터레이터.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 클래스. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | 현재 이터레이터를 복제합니다. |
| void [DecrementIterator](./decrementiterator/)() override | 이터레이터를 한 단계 뒤로 이동합니다. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 생성자. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 생성자. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | 이동 생성자. |
| void [IncrementIterator](./incrementiterator/)() override | 이터레이터를 한 단계 앞으로 이동합니다. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | 지정된 단계 수만큼 이터레이터를 이동합니다. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | 소멸자. |

## 참고

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)