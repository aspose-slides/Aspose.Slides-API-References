---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션 끝에 새 작업을 추가합니다.
type: docs
weight: 66
url: /ko/aspose.slides/coloroperationcollection/add/
---
## ColorOperationCollection::Add(ColorTransformOperation, float) 메서드

컬렉션의 끝에 새 작업을 추가합니다.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Add(ColorTransformOperation operation, float parameter) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 작업 유형. |
| parameter | **float** | 작업 매개변수. |

### 반환 값

추가된 연산.

## ColorOperationCollection::Add(ColorTransformOperation) 메서드

컬렉션의 끝에 새 작업을 추가합니다.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Add(ColorTransformOperation operation) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 작업 유형. |

### 반환 값

추가된 연산.

## 참고

* 열거형 [ColorTransformOperation](../../colortransformoperation/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColorOperation](../../icoloroperation/)
* 클래스 [ColorOperationCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)