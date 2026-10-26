---
title: Hyperlink()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza egy hiperhivatkozás példányát.
type: docs
weight: 339
url: /hu/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) konstruktor

Létrehozza egy hiperhivatkozás példányát.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) konstruktor

Létrehozza egy olyan hiperhivatkozás példányát, amely egy adott diára mutat. Megjegyzés: a létrehozott hiperhivatkozást egyazon bemutató egyik objektumához kell hozzárendelni, különben a hivatkozás NoActionként lesz mentve.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Cél dia. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) konstruktor

Létrehozza egy hiperhivatkozás példányát egy másik hiperhivatkozás forrásaként, felülírva a másodlagos tulajdonságokat.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Forrás hiperhivatkozás |
| targetFrame | [System::String](../../../system/string/) | Célkeret |
| tooltip | [System::String](../../../system/string/) | Buboréksúgó szöveg |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Hyperlink](../)
* Osztály [ISlide](../../islide/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)