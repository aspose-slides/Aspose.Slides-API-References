---
title: Insert()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen Paragraph in die Sammlung an dem angegebenen Index ein.
type: docs
weight: 66
url: /de/aspose.slides/paragraphcollection/insert/
---
## ParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) Methode

Fügt ein [Paragraph](../../paragraph/) in die Sammlung an dem angegebenen Index ein.

```cpp
void Aspose::Slides::ParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem [Paragraph](../../paragraph/) eingefügt werden soll. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Das [Paragraph](../../paragraph/) zum Einfügen. |

## ParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) Methode

Fügt den Inhalt von [ParagraphCollection](../) in die Sammlung an dem angegebenen Index ein.

```cpp
void Aspose::Slides::ParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem Absätze eingefügt werden sollen. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | Die einzufügenden Absätze. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraph](../../iparagraph/)
* Klasse [ParagraphCollection](../)
* Klasse [IParagraphCollection](../../iparagraphcollection/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)