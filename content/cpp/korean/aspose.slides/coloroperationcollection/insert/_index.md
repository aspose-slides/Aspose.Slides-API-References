---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 작업을 컬렉션에 삽입합니다.
type: docs
weight: 79
url: /ko/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) 메서드

새 작업을 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **int32_t** | 작업이 삽입될 인덱스입니다. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 작업 유형입니다. |
| parameter | **float** | 작업의 매개변수입니다. |

### 반환 값

삽입된 작업.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) 메서드

새 작업을 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **int32_t** | 작업이 삽입될 인덱스입니다. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 작업 유형입니다. |

### 반환 값

삽입된 작업.

## 관련 항목

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)