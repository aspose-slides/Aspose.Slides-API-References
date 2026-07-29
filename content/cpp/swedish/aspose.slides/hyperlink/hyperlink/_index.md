---
title: Hyperlink()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av en hyperlänk.
type: docs
weight: 339
url: /sv/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) konstruktor


Skapar en instans av en hyperlänk.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |


## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) konstruktor


Skapar en instans av en hyperlänk som pekar på en specifik bild. Obs: den skapade hyperlänken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Målbild. |


## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) konstruktor


Skapar en instans av en hyperlänk med en annan hyperlänk som källa, och åsidosätter sekundära egenskaper.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Källhyperlänk |
| targetFrame | [System::String](../../../system/string/) | Målruta |
| tooltip | [System::String](../../../system/string/) | Verktygstipstext |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Hyperlink](../)
* Klass [ISlide](../../islide/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)