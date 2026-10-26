---
title: KVPairIterator
second_title: Aspose.Slides for C++ API 레퍼런스
description: "어댑터 이터레이터이며, std::pair를 Dictionary에서 기대되는 KVPair로 래핑합니다."
type: docs
weight: 391
url: /ko/system.collections.generic/kvpairiterator/
---
## KVPairIterator 클래스

어댑터 이터레이터이며, std::pair를 [Dictionary](../dictionary/)에서 기대되는 KVPair로 래핑합니다.

```cpp
template<typename KVPair,typename Container>class KVPairIterator
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| KVPair | 필요한 반환 유형 |
| Container | 래핑된 컨테이너 유형 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [KVPairIterator](./kvpairiterator/)(typename Container::const_iterator) |  |
| KVPair [operator*](./operator_star/)() const |  |
| [KVPairIterator](./)\& [operator++](./operator_plus_plus/)() |  |
| [KVPairIterator](./) [operator++](./operator_plus_plus/)(int) |  |
| [KVPairIterator](./)\& [operator--](./operator_minus_minus/)() |  |
| [KVPairIterator](./) [operator--](./operator_minus_minus/)(int) |  |
## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [iterator_category](./iterator_category/) |  |
| [value_type](./value_type/) |  |
| [difference_type](./difference_type/) |  |
| [pointer](./pointer/) |  |
| [reference](./reference/) |  |

## 참조

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)