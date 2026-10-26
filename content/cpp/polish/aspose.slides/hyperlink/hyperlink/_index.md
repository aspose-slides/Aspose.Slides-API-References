---
title: Hyperlink()
second_title: Aspose.Slides dla dokumentacji API C++
description: Tworzy instancję hyperlink.
type: docs
weight: 339
url: /pl/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) konstruktor

Tworzy instancję hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) konstruktor

Tworzy instancję hyperlink, który wskazuje na określony slajd. Uwaga: utworzony hyperlink powinien być przypisany do obiektu z tej samej prezentacji, w przeciwnym razie link zostanie zapisany jako NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Docelowy slajd. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) konstruktor

Tworzy instancję hyperlink używając innego hyperlink jako źródła, nadpisując właściwości dodatkowe.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Źródłowy hyperlink |
| targetFrame | [System::String](../../../system/string/) | Docelowa ramka |
| tooltip | [System::String](../../../system/string/) | Tekst podpowiedzi |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Hyperlink](../)
* Klasa [ISlide](../../islide/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)