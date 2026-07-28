---
title: Add()
second_title: Aspose.Slides C++ API-referencia
description: WebVTT zárt feliratokat ad a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) metódus

WebVTT zárt feliratokat ad a gyűjtemény végéhez.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | A zárt feliratok címkéje. |
| filePath | [System::String](../../../system/string/) | A WebVTT fájl elérési útja. |

### Visszatérési érték

A hozzáadott [ICaptions](../../icaptions/) példány.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metódus

WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamból.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | A zárt feliratok címkéje. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A bemeneti adatfolyam, amely WebVTT formátumú adatokat tartalmaz. |

### Visszatérési érték

A hozzáadott [ICaptions](../../icaptions/) példány.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ICaptions](../../icaptions/)
* Osztály [String](../../../system/string/)
* Osztály [CaptionsCollection](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)