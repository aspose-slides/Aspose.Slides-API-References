---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute l'étiquette de sensibilité à la fin de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) méthode

Ajoute l'étiquette de sensibilité à la fin de la collection.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | L'identifiant de l'étiquette de sensibilité. |
| siteId | [System::Guid](../../../system/guid/) | L'identifiant du site Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Indicateur indiquant si l'étiquette de sensibilité est activée. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Méthode d'affectation pour l'étiquette de sensibilité. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) méthode

Ajoute un [SensitivityLabel](../../sensitivitylabel/) à la collection.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | L'objet [SensitivityLabel](../../sensitivitylabel/) à ajouter à la fin de la collection. |

### Valeur de retour

L'index auquel le [SensitivityLabel](../../sensitivitylabel/) a été ajouté.

## Voir aussi

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)