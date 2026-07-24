---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Paragraph am Ende der Sammlung hinzu.
type: docs
weight: 40
url: /de/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) Methode

Fügt ein [Paragraph](../../paragraph/) am Ende der Sammlung hinzu.

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Der [Paragraph](../../paragraph/), der am Ende der Sammlung hinzugefügt werden soll. |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) Methode

Fügt einen Inhalt von [ParagraphCollection](../) am Ende der Sammlung hinzu.

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | Der [ParagraphCollection](../), der am Ende der Sammlung hinzugefügt werden soll. |

### Rückgabewert

Der Index, an dem das [Paragraph](../../paragraph/) hinzugefügt wurde, oder -1, wenn nichts hinzuzufügen ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraph](../../iparagraph/)
* Klasse [ParagraphCollection](../)
* Klasse [IParagraphCollection](../../iparagraphcollection/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)