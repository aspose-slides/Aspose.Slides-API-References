---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt ein Paragraph am Ende der Sammlung hinzu.
type: docs
weight: 27
url: /de/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) Methode

Fügt ein [Paragraph](../../paragraph/) am Ende der Sammlung hinzu.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Der [Paragraph](../../paragraph/) wird am Ende der Sammlung hinzugefügt. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) Methode

Fügt den Inhalt von [ParagraphCollection](../../paragraphcollection/) am Ende der Sammlung hinzu.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Der [ParagraphCollection](../../paragraphcollection/) wird am Ende der Sammlung hinzugefügt. |

### Rückgabewert

Der Index, an dem das [Paragraph](../../paragraph/) hinzugefügt wurde, oder -1, wenn nichts hinzuzufügen ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraph](../../iparagraph/)
* Klasse [IParagraphCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)