---
title: ValueIterator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.collections.generic/valueiterator/valueiterator/
---
## ValueIterator::ValueIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 생성자

생성자.

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 보관할 이터레이터. |
| end | typename Dict::map_t::const_iterator\&& | 컨테이너 끝을 가리키는 이터레이터. |

## ValueIterator::ValueIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 생성자

생성자.

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 보관할 이터레이터. |
| end | const typename Dict::map_t::const_iterator\& | 컨테이너 끝을 가리키는 이터레이터. |

## ValueIterator::ValueIterator(ValueIterator\&&) 생성자

이동 생성자.

```cpp
System::Collections::Generic::ValueIterator<Dict>::ValueIterator(ValueIterator &&other) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [ValueIterator](../)\&& | 데이터를 이동할 이터레이터. |

## 참조

* 클래스 [ValueIterator](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)