---
title: Hyperlink()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Instanz eines Hyperlinks.
type: docs
weight: 339
url: /de/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) Konstruktor


Erstellt eine Instanz eines Hyperlinks.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) Konstruktor


Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist. Hinweis: Der erstellte Hyperlink sollte einem Objekt derselben Präsentation zugewiesen werden, sonst wird der Link als NoAction gespeichert.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Ziel-Folie. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) Konstruktor


Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle, wobei sekundäre Eigenschaften überschrieben werden.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Quell-Hyperlink |
| targetFrame | [System::String](../../../system/string/) | Ziel-Frame |
| tooltip | [System::String](../../../system/string/) | Tooltip-Text |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Hyperlink](../)
* Klasse [ISlide](../../islide/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)