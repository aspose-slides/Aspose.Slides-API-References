---
title: PptOptions class
second_title: Aspose.Slides pro Python pomocí .NET API
description: 
type: docs
url: /cs/aspose.slides.export/pptoptions/
---
## PptOptions class

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PPT.

**Dědičnost:**[`PptOptions`](/slides/python-net/cs/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ PptOptions obsahuje následující členy:

## Konstruktor

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/pptoptions/__init__/#) |  |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/pptoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen.<br/>            Čtení/zápis [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/pptoptions/progress_callback/) | Reprezentuje objekt zpětného volání pro aktualizace průběhu ukládání v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/pptoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že výchozí písmo není nalezeno.<br/>            Čtení/zápis **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/pptoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Čtení/zápis [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/pptoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. <br/>            Čtení/zápis **bool**. Výchozí hodnota je **false**. |
| [`root_directory_clsid`](/slides/python-net/cs/aspose.slides.export/pptoptions/root_directory_clsid/) | Reprezentuje GUID (CLSID) třídy objektu, který je uložen ve vstupu kořenového adresáře. Lze použít pro COM<br/>            aktivaci aplikace dokumentu.<br/>            Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'. |


### Viz také
* třída [`PptOptions`](/slides/python-net/cs/aspose.slides.export/pptoptions)
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)