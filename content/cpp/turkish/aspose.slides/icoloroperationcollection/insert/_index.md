---
title: Insert()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir işlemi bir koleksiyona ekler.
type: docs
weight: 40
url: /tr/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metodu


Yeni işlemi bir koleksiyona ekler.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **int32_t** | İşlemin ekleneceği indeks. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | İşlem türü. |
| parameter | **float** | İşlemin parametresi. |

### Dönüş Değeri

Eklemiş işlem.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) metodu


Yeni işlemi bir koleksiyona ekler.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **int32_t** | İşlemin ekleneceği indeks. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | İşlem türü. |

### Dönüş Değeri

Eklemiş işlem.

## Ayrıca

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)