---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega la etiqueta de sensibilidad al final de la colección.
type: docs
weight: 27
url: /es/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) método

Agrega la etiqueta de sensibilidad al final de la colección.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | El id de la etiqueta de sensibilidad. |
| siteId | [System::Guid](../../../system/guid/) | El identificador del sitio de Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Indicador que indica si la etiqueta de sensibilidad está habilitada. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | El método de asignación para la etiqueta de sensibilidad. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) método

Agrega un [SensitivityLabel](../../sensitivitylabel/) a la colección.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | El objeto [SensitivityLabel](../../sensitivitylabel/) que se agregará al final de la colección. |

### Valor de retorno

El índice en el que se agregó el [SensitivityLabel](../../sensitivitylabel/).

## Ver también

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)