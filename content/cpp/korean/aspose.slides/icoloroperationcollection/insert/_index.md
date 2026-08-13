---
title: Insert()
second_title: Aspose.Slides C++ API 참조
description: 새 연산을 컬렉션에 삽입합니다.
type: docs
weight: 40
url: /ko/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) method


새 연산을 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **int32_t** | 연산이 삽입될 인덱스입니다. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 연산 유형. |
| parameter | **float** | 연산 매개변수. |

### 반환 값

삽입된 연산.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) method


새 연산을 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **int32_t** | 연산이 삽입될 인덱스입니다. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 연산 유형. |

### 반환 값

삽입된 연산.

## 참조

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)