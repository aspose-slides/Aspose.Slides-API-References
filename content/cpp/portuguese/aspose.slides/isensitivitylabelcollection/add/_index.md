---
title: Add()
second_title: Referência da API Aspose.Slides for C++
description: Adiciona a etiqueta de sensibilidade ao final da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

Adiciona a etiqueta de sensibilidade ao final da coleção.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | O id da etiqueta de sensibilidade. |
| siteId | [System::Guid](../../../system/guid/) | O identificador do site do Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Indicador que indica se a etiqueta de sensibilidade está habilitada. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | O método de atribuição para a etiqueta de sensibilidade. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

Adiciona um [SensitivityLabel](../../sensitivitylabel/) à coleção.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | O objeto [SensitivityLabel](../../sensitivitylabel/) a ser adicionado ao final da coleção. |

### Valor de Retorno

O índice no qual o [SensitivityLabel](../../sensitivitylabel/) foi adicionado.

## Veja Também

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [String](../../../system/string/)
* Classe [Guid](../../../system/guid/)
* Classe [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)