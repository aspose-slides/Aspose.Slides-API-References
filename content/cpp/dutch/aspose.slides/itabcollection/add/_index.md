---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een Tab toe aan de collectie.
type: docs
weight: 14
url: /nl/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) methode


Voegt een [Tab](../../tab/) toe aan de collectie.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) positie. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) uitlijning. |

### Return Value

Toegevoegde tab.

## ITabCollection::Add(System::SharedPtr\<ITab\>) methode


Voegt een [Tab](../../tab/) toe aan de collectie.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Het [Tab](../../tab/) object dat moet worden toegevoegd aan het einde van de collectie. |

### Return Value

De index waarop de tab werd toegevoegd.

## See Also

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)