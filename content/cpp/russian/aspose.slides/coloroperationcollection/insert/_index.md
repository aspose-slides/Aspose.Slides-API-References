---
title: Insert()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет новую операцию в коллекцию.
type: docs
weight: 79
url: /ru/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) метод

Вставляет новую операцию в коллекцию.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| position | **int32_t** | Индекс, по которому будет вставлена операция. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Тип операции. |
| parameter | **float** | Параметр операции. |

### Возвращаемое значение

Вставленная операция.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) метод

Вставляет новую операцию в коллекцию.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| position | **int32_t** | Индекс, по которому будет вставлена операция. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Тип операции. |

### Возвращаемое значение

Вставленная операция.

## См. также

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)