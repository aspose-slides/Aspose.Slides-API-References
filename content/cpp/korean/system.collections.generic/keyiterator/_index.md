---
title: KeyIterator
second_title: Aspose.Slides for C++ API 레퍼런스
description: 키 접근을 제공하는 사전 반복자.
type: docs
weight: 365
url: /ko/system.collections.generic/keyiterator/
---
## KeyIterator 클래스


[Dictionary](../dictionary/) 키 접근을 제공하는 반복자.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Dict | [Dictionary](../dictionary/) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | 현재 iterator를 복제합니다. |
| void [DecrementIterator](./decrementiterator/)() override | iterator를 한 단계 뒤로 이동합니다. |
| void [IncrementIterator](./incrementiterator/)() override | iterator를 한 단계 앞으로 이동합니다. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | 생성자. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | 생성자. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | 이동 생성자. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | iterator를 지정된 단계 수만큼 이동합니다. |
| virtual  [~KeyIterator](./~keyiterator/)() | 소멸자. |

## 참고

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)