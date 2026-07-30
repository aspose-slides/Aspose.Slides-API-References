---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge l'etichetta di sensibilità alla fine della raccolta.
type: docs
weight: 27
url: /it/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metodo

Aggiunge l'etichetta di sensibilità alla fine della raccolta.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | L'id dell'etichetta di sensibilità. |
| siteId | [System::Guid](../../../system/guid/) | L'identificatore del sito Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Il flag indica se l'etichetta di sensibilità è abilitata. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Il metodo di assegnazione per l'etichetta di sensibilità. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metodo

Aggiunge un [SensitivityLabel](../../sensitivitylabel/) alla raccolta.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | L'oggetto [SensitivityLabel](../../sensitivitylabel/) da aggiungere alla fine della raccolta. |

### Valore di ritorno

L'indice al quale [SensitivityLabel](../../sensitivitylabel/) è stato aggiunto.

## Vedi anche

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)