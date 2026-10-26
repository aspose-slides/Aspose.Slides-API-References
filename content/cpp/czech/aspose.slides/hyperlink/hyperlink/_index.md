---
title: Hyperlink()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří instanci hypertextového odkazu.
type: docs
weight: 339
url: /cs/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) konstruktor


Vytvoří instanci třídy Hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) konstruktor


Vytvoří instanci třídy Hyperlink, která odkazuje na konkrétní snímek. Poznámka: vytvořený odkaz Hyperlink by měl být přiřazen k objektu ze stejné prezentace, jinak bude odkaz uložen jako NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Cílový snímek. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) konstruktor


Vytvoří instanci třídy Hyperlink pomocí jiného odkazu Hyperlink jako zdroje, přičemž přepíše sekundární vlastnosti.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Zdrojový odkaz Hyperlink |
| targetFrame | [System::String](../../../system/string/) | Cílový rámec |
| tooltip | [System::String](../../../system/string/) | Text popisku |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Hyperlink](../)
* Třída [ISlide](../../islide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)