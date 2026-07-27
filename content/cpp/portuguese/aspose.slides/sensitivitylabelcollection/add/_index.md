---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o rótulo de sensibilidade ao final da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) método

Adiciona o rótulo de sensibilidade ao final da coleção.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | O id do rótulo de sensibilidade. |
| siteId | [System::Guid](../../../system/guid/) | O identificador do site do Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Indicador indica se o rótulo de sensibilidade está habilitado. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | O método de atribuição para o rótulo de sensibilidade. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) método

Adiciona um [SensitivityLabel](../../sensitivitylabel/) à coleção.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | O objeto [SensitivityLabel](../../sensitivitylabel/) a ser adicionado ao final da coleção. |

### Valor de Retorno

O índice no qual o [SensitivityLabel](../../sensitivitylabel/) foi adicionado.

## Ver Também

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)