---
title: IndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 특정 항목의 첫 번째 인덱스를 가져옵니다.
type: docs
weight: 222
url: /ko/system.collections.generic/list/indexof/
---
## List::IndexOf(const T\&) const 메서드


특정 항목의 첫 번째 인덱스를 가져옵니다.

```cpp
int System::Collections::Generic::List<T>::IndexOf(const T &item) const override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 찾을 항목. |

### 반환 값

[Index](../../../system/index/) 지정된 항목의 첫 번째 발생 위치 또는 찾지 못하면 -1.

## List::IndexOf(const T\&, int) const 메서드


목록에서 특정 항목을 찾습니다.

```cpp
int System::Collections::Generic::List<T>::IndexOf(const T &item, int index) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 찾을 항목. |
| index | int | [Index](../../../system/index/) 시작 검색 위치. |

### 반환 값

[Index](../../../system/index/) 지정된 항목의 첫 번째 인스턴스 위치 또는 찾지 못하면 -1.

## 참고

* 클래스 [List](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)