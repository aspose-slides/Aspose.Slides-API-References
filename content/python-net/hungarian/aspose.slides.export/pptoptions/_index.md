---
title: PptOptions class
second_title: Aspose.Slides Pythonhoz a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.export/pptoptions/
---
## PptOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy bemutató PPT formátumban.

**Öröklés:**[`PptOptions`](/slides/python-net/hu/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)

A PptOptions típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.export/pptoptions/__init__/#) |  |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`warning_callback`](/slides/python-net/hu/aspose.slides.export/pptoptions/warning_callback/) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad.<br/>            Olvasás/írás [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hu/aspose.slides.export/pptoptions/progress_callback/) | Representál egy visszahívási objektumot a mentési előrehaladás százalékos frissítéseihez.<br/>            Lásd [`IProgressCallback`](/slides/python-net/hu/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hu/aspose.slides.export/pptoptions/default_regular_font/) | Visszaadja vagy beállítja a betűkészletet, amely akkor használatos, ha a forrás betűkészlet nem található.<br/>            Olvasás-írás **str**. |
| [`gradient_style`](/slides/python-net/hu/aspose.slides.export/pptoptions/gradient_style/) | Visszaadja vagy beállítja a gradient vizuális stílusát.<br/>            Olvasás/írás [`GradientStyle`](/slides/python-net/hu/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hu/aspose.slides.export/pptoptions/skip_java_script_links/) | Megadja, hogy a bemutató mentésekor kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat.<br/>            Olvasás/írás **bool**. Az alapértelmezett érték **false**. |
| [`root_directory_clsid`](/slides/python-net/hu/aspose.slides.export/pptoptions/root_directory_clsid/) | Representálja az objektumosztály GUID-ját (CLSID), amely a gyökérkönyvtár bejegyzésében tárolódik. COM-hez használható a dokumentum alkalmazásának aktiválásához.<br/>            Az alapértelmezett érték '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8' megfelelője. |

### Lásd még
* osztály [`PptOptions`](/slides/python-net/hu/aspose.slides.export/pptoptions)
* osztály [`SaveOptions`](/slides/python-net/hu/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)