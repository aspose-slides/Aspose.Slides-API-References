---
title: Insert()
second_title: Aspose.Slides C++ API referenciája
description: Beszúr egy Paragraph-et a gyűjteménybe a megadott indexen.
type: docs
weight: 40
url: /hu/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) metódus

Beszúr egy [Paragraph](../../paragraph/) a gyűjteménybe a megadott indexen.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla-alapú index, amelynél [Paragraph](../../paragraph/)-t be kell szúrni. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | A beillesztendő [Paragraph](../../paragraph/). |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) metódus

Beszúr egy [ParagraphCollection](../../paragraphcollection/) tartalmat a gyűjteménybe a megadott indexen.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla-alapú index, amelynél a bekezdéseket be kell szúrni. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | A beillesztendő bekezdések. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IParagraph](../../iparagraph/)
* Osztály [IParagraphCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)