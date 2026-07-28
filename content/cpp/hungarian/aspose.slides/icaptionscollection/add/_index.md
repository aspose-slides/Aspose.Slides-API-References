---
title: Add()
second_title: Aspose.Slides C++ API hivatkozás
description: WebVTT zárt feliratokat ad a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) metódus

WebVTT zárt feliratokat ad a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | A zárt feliratok címkéje. |
| filePath | [System::String](../../../system/string/) | A WebVTT fájl elérési útja. |

### Visszatérési érték

A hozzáadott [ICaptions](../../icaptions/) példány.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metódus

WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamból.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | A zárt feliratok címkéje. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A WebVTT formátumú adatot tartalmazó bemeneti adatfolyam. |

### Visszatérési érték

A hozzáadott [ICaptions](../../icaptions/) példány.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [ICaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)