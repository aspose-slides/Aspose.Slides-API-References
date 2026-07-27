---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega la etiqueta de sensibilidad al final de la colección.
type: docs
weight: 27
url: /es/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) método


Agrega la etiqueta de sensibilidad al final de la colección.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | El id de la etiqueta de sensibilidad. |
| siteId | [System::Guid](../../../system/guid/) | El identificador del sitio de Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Bandera que indica si la etiqueta de sensibilidad está habilitada. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | El método de asignación para la etiqueta de sensibilidad. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) método


Agrega un [SensitivityLabel](../../sensitivitylabel/) a la colección.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | El objeto [SensitivityLabel](../../sensitivitylabel/) que se agregará al final de la colección. |

### Valor devuelto

El índice en el que se agregó [SensitivityLabel](../../sensitivitylabel/).

## Ver también

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)