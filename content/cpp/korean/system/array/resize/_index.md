---
title: Resize()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 배열의 크기를 지정된 값으로 변경하거나 지정된 크기의 새 배열을 생성합니다.
type: docs
weight: 768
url: /ko/system/array/resize/
---
## Array::Resize(ArrayPtr\<Type\>\&, int) 메서드


지정된 배열의 크기를 지정된 값으로 변경하거나 지정된 크기의 새 배열을 생성합니다.

```cpp
template<typename Type> static void System::Array<T>::Resize(ArrayPtr<Type> &arr, int new_size)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | [Array](../) 를 크기 조정합니다. **arr**이 null 포인터인 경우 새 배열이 생성됩니다 |
| new_size | int | 배열의 새로운 크기, 또는 **arr**이 null인 경우 새 배열의 크기 |

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 메서드 [Type](../../object/type/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)