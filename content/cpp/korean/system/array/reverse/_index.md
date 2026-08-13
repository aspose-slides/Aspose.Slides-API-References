---
title: Reverse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 배열의 요소들을 반전시킵니다.
type: docs
weight: 755
url: /ko/system/array/reverse/
---
## Array::Reverse(const ArrayPtr\<Type\>\&) 메서드


지정된 배열의 요소 순서를 반전시킵니다.

```cpp
template<typename Type> static void System::Array<T>::Reverse(const ArrayPtr<Type> &arr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 대상 배열 |

## Array::Reverse(const ArrayPtr\<Type\>\&, int, int) 메서드


지정된 배열에서 요소 범위의 순서를 반전시킵니다.

```cpp
template<typename Type> static void System::Array<T>::Reverse(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 대상 배열 |
| startIndex | int | [Index](../../index/) 역전 범위가 시작되는 배열 내 인덱스 |
| count | int | 역전할 범위의 크기 |

## 또 보기

* typedef [ArrayPtr](../../arrayptr/)
* 메서드 [Type](../../object/type/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)