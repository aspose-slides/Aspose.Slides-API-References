---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een Paragraph toe aan het einde van de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) method


Voegt een [Paragraph](../../paragraph/) toe aan het einde van de collectie.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | De [Paragraph](../../paragraph/) die aan het einde van de collectie moet worden toegevoegd. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) method


Voegt een inhoud van [ParagraphCollection](../../paragraphcollection/) toe aan het einde van de collectie.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | De [ParagraphCollection](../../paragraphcollection/) die aan het einde van de collectie moet worden toegevoegd. |

### Retourwaarde

De index waarop de [Paragraph](../../paragraph/) is toegevoegd of -1 als er niets toe te voegen is.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraph](../../iparagraph/)
* Klasse [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)