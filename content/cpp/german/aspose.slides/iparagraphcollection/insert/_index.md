---
title: Insert()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen Paragraph in die Sammlung an dem angegebenen Index ein.
type: docs
weight: 40
url: /de/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) Methode

Fügt ein [Paragraph](../../paragraph/) in die Sammlung an der angegebenen Position ein.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem [Paragraph](../../paragraph/) eingefügt werden soll. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Der [Paragraph](../../paragraph/), der eingefügt werden soll. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) Methode

Fügt einen Inhalt von [ParagraphCollection](../../paragraphcollection/) in die Sammlung an der angegebenen Position ein.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem Absätze eingefügt werden sollen. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Die Absätze, die eingefügt werden sollen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraph](../../iparagraph/)
* Klasse [IParagraphCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)