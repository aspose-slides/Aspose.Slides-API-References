---
title: KeyIterator()
second_title: Aspose.Slides for C++ API 참조
description: 생성자.
type: docs
weight: 1
url: /ko/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) 생성자

생성자.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | 보관할 반복자. |
| end | typename Dict::map_t::const_iterator\&& | 컨테이너 끝을 가리키는 반복자. |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) 생성자

생성자.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | 보관할 반복자. |
| end | const typename Dict::map_t::const_iterator\& | 컨테이너 끝을 가리키는 반복자. |

## KeyIterator::KeyIterator(KeyIterator\&&) 생성자

이동 생성자.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | 데이터를 이동할 반복자. |

## 또 보기

* 클래스 [KeyIterator](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)