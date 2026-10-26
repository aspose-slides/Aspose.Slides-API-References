---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en Paragraph i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) metod

Lägger till en [Paragraph](../../paragraph/) i slutet av samlingen.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [Paragraph](../../paragraph/) som ska läggas till i slutet av samlingen. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) metod

Lägger till ett innehåll av [ParagraphCollection](../../paragraphcollection/) i slutet av samlingen.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | [ParagraphCollection](../../paragraphcollection/) som ska läggas till i slutet av samlingen. |

### Returvärde

Indexet vid vilket [Paragraph](../../paragraph/) har lagts till eller -1 om det inte finns något att lägga till.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IParagraph](../../iparagraph/)
* Klass [IParagraphCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)