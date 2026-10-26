---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Egy Paragraph-ot ad a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) metódus

Hozzáad egy [Paragraph](../../paragraph/)-t a gyűjtemény végéhez.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | A [Paragraph](../../paragraph/) a gyűjtemény végéhez hozzáadandó. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) metódus

Hozzáad egy [ParagraphCollection](../../paragraphcollection/) tartalmat a gyűjtemény végéhez.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | A [ParagraphCollection](../../paragraphcollection/) a gyűjtemény végéhez hozzáadandó. |

### Visszatérési érték

Az index, amelynél a [Paragraph](../../paragraph/) hozzá lett adva, vagy -1, ha nincs mit hozzáadni.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IParagraph](../../iparagraph/)
* Osztály [IParagraphCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)