---
title: XpsOptions class
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides.export/xpsoptions/
---
## XpsOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu XPS.

**Inheritance:**[`XpsOptions`](/slides/python-net/cs/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ XpsOptions vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/xpsoptions/__init__/#) | Výchozí konstruktor. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/xpsoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen.<br/>            Číst/Zapisovat [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/xpsoptions/progress_callback/) | Reprezentuje zpětnou volací objekt pro ukládání aktualizací postupu v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/xpsoptions/default_regular_font/) | Vrací nebo nastavuje písmo použité v případě, že zdrojové písmo nebylo nalezeno.<br/>            Číst/Zapisovat **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/xpsoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl přechodu.<br/>            Číst/Zapisovat [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/xpsoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Číst/Zapisovat **bool**. Výchozí hodnota je **false**. |
| [`show_hidden_slides`](/slides/python-net/cs/aspose.slides.export/xpsoptions/show_hidden_slides/) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky nebo ne.<br/>            Výchozí hodnota je `false`. |
| [`save_metafiles_as_png`](/slides/python-net/cs/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | True pro převod všech metafilů použitých v prezentaci na obrázky PNG.<br/>            Číst/Zapisovat **bool**. |
| [`draw_slides_frame`](/slides/python-net/cs/aspose.slides.export/xpsoptions/draw_slides_frame/) | True pro nakreslení černého rámečku kolem každého snímku.<br/>            Číst/Zapisovat **bool**. |

### Viz také
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* třída [`XpsOptions`](/slides/python-net/cs/aspose.slides.export/xpsoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)