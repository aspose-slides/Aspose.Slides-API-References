---
title: Add()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá uzavřené titulky WebVTT na konec kolekce.
type: docs
weight: 27
url: /cs/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) method


Přidá uzavřené titulky WebVTT na konec kolekce.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Štítek uzavřených titulků. |
| filePath | [System::String](../../../system/string/) | Cesta k souboru WebVTT. |

### Návratová hodnota

Přidaná instance [ICaptions](../../icaptions/).

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) method


Přidá uzavřené titulky WebVTT na konec kolekce ze streamu.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Štítek uzavřených titulků. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream obsahující data ve formátu WebVTT. |

### Návratová hodnota

Přidaná instance [ICaptions](../../icaptions/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ICaptions](../../icaptions/)
* Třída [String](../../../system/string/)
* Třída [ICaptionsCollection](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)