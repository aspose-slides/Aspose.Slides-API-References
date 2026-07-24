---
title: Insert()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni işlemi bir koleksiyona ekler.
type: docs
weight: 79
url: /tr/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) yöntemi

Yeni işlemi bir koleksiyona ekler.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **int32_t** | İşlemin ekleneceği indeks. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | İşlem türü. |
| parameter | **float** | İşlemin parametresi. |

### Dönüş Değeri

Eklenen işlem.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) yöntemi

Yeni işlemi bir koleksiyona ekler.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **int32_t** | İşlemin ekleneceği indeks. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | İşlem türü. |

### Dönüş Değeri

Eklenen işlem.

## Ayrıca Bakınız

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IColorOperation](../../icoloroperation/)
* Sınıf [ColorOperationCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)