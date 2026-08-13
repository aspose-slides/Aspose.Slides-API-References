---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 객체를 검색하고 전체 리스트 내에서 마지막으로 나타나는 항목의 0부터 시작하는 인덱스를 반환합니다.
type: docs
weight: 469
url: /ko/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const 메서드

지정된 객체를 검색하고 전체 리스트 내에서 마지막으로 나타나는 항목의 0부터 시작하는 인덱스를 반환합니다.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 리스트에서 찾을 객체 |

### 반환값

[List](../) 전체에서 항목이 마지막으로 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## List::LastIndexOf(const T\&, int32_t) const 메서드

지정된 객체를 검색하고 첫 번째 요소에서 지정된 인덱스까지 확장되는 [List](../)의 요소 범위 내에서 마지막으로 나타나는 항목의 0부터 시작하는 인덱스를 반환합니다.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 리스트에서 찾을 객체 |
| index | **int32_t** | 역방향 검색의 0부터 시작하는 시작 인덱스. |

### 반환값

[List](../)의 요소 범위에서 첫 번째 요소부터 index까지 확장되는 영역 내에서 항목이 마지막으로 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## List::LastIndexOf(const T\&, int32_t, int32_t) const 메서드

지정된 객체를 검색하고 지정된 개수의 요소를 포함하고 지정된 인덱스에서 끝나는 [List](../)의 요소 범위 내에서 마지막으로 나타나는 항목의 0부터 시작하는 인덱스를 반환합니다.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | [List](../)에서 찾을 객체 |
| index | **int32_t** | 역방향 검색의 0부터 시작하는 시작 인덱스. |
| count | **int32_t** | 검색할 구간에 포함된 요소 수. |

### 반환값

[List](../)의 요소 범위에서 count 개의 요소를 포함하고 index에서 끝나는 영역 내에서 항목이 마지막으로 나타나는 0부터 시작하는 인덱스이며, 찾지 못하면 -1을 반환합니다.

## 또 보기

* 클래스 [List](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)