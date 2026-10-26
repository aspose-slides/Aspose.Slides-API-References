---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un Tab à la collection.
type: docs
weight: 14
url: /fr/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) méthode


Ajoute un [Tab](../../tab/) à la collection.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) alignment. |

### Valeur de retour

Onglet ajouté.

## ITabCollection::Add(System::SharedPtr\<ITab\>) méthode


Ajoute un [Tab](../../tab/) à la collection.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | L'objet [Tab](../../tab/) à ajouter à la fin de la collection. |

### Valeur de retour

L'index auquel l'onglet a été ajouté.

## Voir aussi

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)