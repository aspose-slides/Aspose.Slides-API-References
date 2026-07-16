---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le label de sensibilité à la fin de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) méthode


Ajoute le label de sensibilité à la fin de la collection.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | L'ID du label de sensibilité. |
| siteId | [System::Guid](../../../system/guid/) | L'identifiant du site Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Drapeau indiquant si le label de sensibilité est activé. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | La méthode d'affectation du label de sensibilité. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) méthode


Ajoute un [SensitivityLabel](../../sensitivitylabel/) à la collection.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
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
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [String](../../../system/string/)
* Classe [Guid](../../../system/guid/)
* Classe [ISensitivityLabelCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)