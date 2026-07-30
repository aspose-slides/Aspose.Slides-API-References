---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge l'etichetta di sensibilità alla fine della raccolta.
type: docs
weight: 27
url: /it/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metodo

Aggiunge l'etichetta di sensibilità alla fine della raccolta.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | L'ID dell'etichetta di sensibilità. |
| siteId | [System::Guid](../../../system/guid/) | L'identificatore del sito Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Flag che indica se l'etichetta di sensibilità è abilitata. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Il metodo di assegnazione per l'etichetta di sensibilità. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metodo

Aggiunge un [SensitivityLabel](../../sensitivitylabel/) alla raccolta.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | L'oggetto [SensitivityLabel](../../sensitivitylabel/) da aggiungere alla fine della raccolta. |

### Valore restituito

L'indice al quale è stato aggiunto il [SensitivityLabel](../../sensitivitylabel/).

## Vedi anche

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [String](../../../system/string/)
* Classe [Guid](../../../system/guid/)
* Classe [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)