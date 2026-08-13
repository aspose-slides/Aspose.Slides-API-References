---
title: DictionaryIterator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.collections.generic/dictionaryiterator/dictionaryiterator/
---
## DictionaryIterator::DictionaryIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 생성자

생성자.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 보관할 반복자. |
| end | typename Dict::map_t::const_iterator\&& | 컨테이너의 끝을 가리키는 반복자. |

## DictionaryIterator::DictionaryIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 생성자

생성자.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 보관할 반복자. |
| end | const typename Dict::map_t::const_iterator\& | 컨테이너의 끝을 가리키는 반복자. |

## DictionaryIterator::DictionaryIterator(DictionaryIterator\&&) 생성자

이동 생성자.

```cpp
System::Collections::Generic::DictionaryIterator<Dict>::DictionaryIterator(DictionaryIterator &&other) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [DictionaryIterator](../)\&& | 데이터를 이동할 반복자. |

## 관련 항목

* 클래스 [DictionaryIterator](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)