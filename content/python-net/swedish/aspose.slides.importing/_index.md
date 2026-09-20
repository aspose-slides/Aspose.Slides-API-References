---
title: aspose.slides.importing
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.importing/
---
## Klasser

| Klass | Beskrivning |
| :- | :- |
| [`ExcelWorkbookImporter`](/slides/python-net/sv/aspose.slides.importing/excelworkbookimporter/) | Tillhandahåller funktionalitet för att importera innehåll från en Excel-arbetsbok till en presentation. |
| [`ExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/externalresourceresolver/) | Callback-klass som används för att lösa externa resurser under import av Html- och Svg-dokument.<br/>            Att använda denna resolver kan skapa en sårbarhet när en klient tillhandahåller en HTML- eller SVG-fil som får serverprogramvaran att hämta en lokal eller nätverksfil. Använd med försiktighet. Det rekommenderas att inte ange ExternalResourceResolver alls (endast inbäddade objekt kommer att läsas) eller att skapa en subklass som kontrollerar om den angivna URI:n är giltig. |
| [`HtmlExternalResolver`](/slides/python-net/sv/aspose.slides.importing/htmlexternalresolver/) | Callback-objekt som används av HTML-importrutinen för att hämta refererade objekt såsom bilder.<br/>            Att använda denna resolver kan skapa en sårbarhet när en klient tillhandahåller en HTML-fil som får serverprogramvaran att hämta en lokal eller nätverksfil. Använd med försiktighet. Det rekommenderas att inte ange HtmlExternalResolver alls (endast inbäddade objekt kommer att läsas) eller att skapa en subklass som kontrollerar om den angivna URI:n är giltig. |
| [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver/) | Callback-gränssnitt som används för att lösa externa resurser under import av Html- och Svg-dokument. |
| [`IHtmlExternalResolver`](/slides/python-net/sv/aspose.slides.importing/ihtmlexternalresolver/) | Callback-gränssnitt som används av HTML-importrutinen för att hämta refererade objekt såsom bilder. |
| [`PdfImportOptions`](/slides/python-net/sv/aspose.slides.importing/pdfimportoptions/) | Representerar PDF-importalternativen |