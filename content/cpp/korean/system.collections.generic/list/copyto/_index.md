---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 리스트 요소를 기존 배열 요소에 복사합니다.
type: docs
weight: 209
url: /ko/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) 메서드

리스트 요소를 기존 배열 요소에 복사합니다.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | 대상 배열. |
| arrayIndex | int | 대상 배열 시작 인덱스. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) 메서드

모든 요소를 기존 배열 요소에 복사합니다.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/)에 요소를 복사합니다. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) 메서드

지정된 인덱스부터 요소를 기존 배열 요소에 복사합니다.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 현재 객체가 나타내는 리스트에서 복사를 시작할 요소의 0 기반 인덱스 |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/)에 요소를 복사합니다. |
| arrayIndex | int | 대상 배열의 시작 위치. |
| count | int | 복사할 요소 수. |

## 참조

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [List](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)