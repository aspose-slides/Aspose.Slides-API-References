---
title: VbaProject class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.vba/vbaproject/
---
## VbaProject třída

Reprezentuje VBA projekt s makry prezentace.

Typ VbaProject obsahuje následující členy:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.vba/vbaproject/__init__/#) | Tento konstruktor vytvoří nový VBA projekt od nuly.<br/>            Projekt bude vytvořen v kódové stránce 1252 Windows Latin 1 (ANSI) |
| [`__init__(self, data)`](/slides/python-net/cs/aspose.slides.vba/vbaproject/__init__/#bytes) | Tento konstruktor načte VBA projekt z binární reprezentace kontejneru OLE. |

## Vlastnosti

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/cs/aspose.slides.vba/vbaproject/name/) | Vrací název VBA projektu.<br/>            Pouze pro čtení **str**. |
| [`modules`](/slides/python-net/cs/aspose.slides.vba/vbaproject/modules/) | Vrací seznam všech modulů, které jsou obsaženy v VBA projektu.<br/>            Pouze pro čtení [`IVbaModuleCollection`](/slides/python-net/cs/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/cs/aspose.slides.vba/vbaproject/references/) | Vrací seznam všech odkazů, které jsou obsaženy v VBA projektu.<br/>            Pouze pro čtení [`IVbaReferenceCollection`](/slides/python-net/cs/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/cs/aspose.slides.vba/vbaproject/is_password_protected/) | Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu.<br/>            Pouze pro čtení **bool**. |

## Metody

| Method | Description |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/cs/aspose.slides.vba/vbaproject/to_binary/#) | Vrací binární reprezentaci VBA projektu jako kontejner OLE |


### Viz také
* modul [`aspose.slides.vba`](/slides/python-net/cs/aspose.slides.vba)
* knihovna [`Aspose.Slides`](/slides/python-net)