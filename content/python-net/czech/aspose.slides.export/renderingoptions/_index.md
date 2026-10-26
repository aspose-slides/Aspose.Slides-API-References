---
title: RenderingOptions class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/renderingoptions/
---
## RenderingOptions třída

Poskytuje možnosti, které řídí, jak je prezentace/slajd vykreslena.

**Dědičnost:**[`RenderingOptions`](/slides/python-net/cs/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)

Typ RenderingOptions vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.export/renderingoptions/__init__/#) | Výchozí konstruktor. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`warning_callback`](/slides/python-net/cs/aspose.slides.export/renderingoptions/warning_callback/) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen.<br/>            Čtení/zápis [`IWarningCallback`](/slides/python-net/cs/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/cs/aspose.slides.export/renderingoptions/progress_callback/) | Reprezentuje zpětnovazací objekt pro ukládání aktualizací postupu v procentech.<br/>            Viz [`IProgressCallback`](/slides/python-net/cs/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/cs/aspose.slides.export/renderingoptions/default_regular_font/) | Vrací nebo nastavuje font použitý v případě, že není nalezen výchozí font.<br/>            Čtení-zápis **str**. |
| [`gradient_style`](/slides/python-net/cs/aspose.slides.export/renderingoptions/gradient_style/) | Vrací nebo nastavuje vizuální styl gradientu.<br/>            Čtení/zápis [`GradientStyle`](/slides/python-net/cs/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/cs/aspose.slides.export/renderingoptions/skip_java_script_links/) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu.<br/>            Čtení/zápis **bool**. Výchozí hodnota je **false**. |
| [`slides_layout_options`](/slides/python-net/cs/aspose.slides.export/renderingoptions/slides_layout_options/) | Získá nebo nastaví režim, ve kterém jsou slajdy umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](/slides/python-net/cs/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/cs/aspose.slides.export/renderingoptions/ink_options/) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu.<br/>            Pouze pro čtení [`IInkOptions`](/slides/python-net/cs/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/cs/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Získá nebo nastaví hodnotu určující, zda je text vykreslen bez použití ligatur.<br/>            Když je nastavena na `true`, ligatury budou ve výstupu zakázány. Ve výchozím stavu je tato vlastnost nastavena na `false`. |

### Viz také
* třída [`RenderingOptions`](/slides/python-net/cs/aspose.slides.export/renderingoptions)
* třída [`SaveOptions`](/slides/python-net/cs/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)