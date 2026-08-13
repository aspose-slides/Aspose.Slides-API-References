---
title: Clear()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 배열이 읽기 전용이므로 지원되지 않습니다.
type: docs
weight: 53
url: /ko/system/array/clear/
---
## Array::Clear() 메서드


현재 객체가 나타내는 배열은 읽기 전용이므로 지원되지 않습니다.

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) 메서드


지정된 배열에서 **startIndex** 인덱스에서 시작하여 **count** 개의 값을 기본값으로 교체합니다.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Type | 대상 배열의 요소 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 대상 배열 |
| startIndex | int | [Index](../../index/) 교체를 시작하는 항목의 인덱스 |
| count | int | 교체할 항목 수 |

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 메서드 [Type](../../object/type/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)