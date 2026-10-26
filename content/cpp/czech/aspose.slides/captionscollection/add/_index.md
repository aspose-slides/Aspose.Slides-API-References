---
title: Add()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá uzavřené titulky WebVTT na konec kolekce.
type: docs
weight: 27
url: /cs/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) metoda


Přidá uzavřené titulky WebVTT na konec kolekce.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Popisek uzavřených titulků. |
| filePath | [System::String](../../../system/string/) | Cesta k souboru WebVTT. |

### Návratová hodnota

Přidaná instance [ICaptions](../../icaptions/).

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metoda


Přidá uzavřené titulky WebVTT na konec kolekce ze streamu.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Popisek uzavřených titulků. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream obsahující data ve formátu WebVTT. |

### Návratová hodnota

Přidaná instance [ICaptions](../../icaptions/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ICaptions](../../icaptions/)
* Třída [String](../../../system/string/)
* Třída [CaptionsCollection](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)