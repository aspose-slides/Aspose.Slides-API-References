---
title: aspose.slides.importing
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.importing/
---
## Klassen

| Klasse | Beschreibung |
| :- | :- |
| [`ExcelWorkbookImporter`](/slides/python-net/de/aspose.slides.importing/excelworkbookimporter/) | Stellt Funktionalität zum Importieren von Inhalten aus einer Excel-Arbeitsmappe in eine Präsentation bereit. |
| [`ExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/externalresourceresolver/) | Callback-Klasse, die zum Auflösen externer Ressourcen während des Imports von Html-, Svg-Dokumenten verwendet wird.<br/>            Die Verwendung dieses Resolvers könnte eine Schwachstelle erzeugen, wenn eine vom Client bereitgestellte HTML- oder SVG-Datei die Serversoftware dazu bringt, lokale oder Netzwerkdateien zu erhalten. Mit Vorsicht verwenden. Es wird empfohlen, ExternalResourceResolver überhaupt nicht anzugeben (es werden nur eingebettete Objekte gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene uri gültig ist. |
| [`HtmlExternalResolver`](/slides/python-net/de/aspose.slides.importing/htmlexternalresolver/) | Callback-Objekt, das von der HTML-Importroutine verwendet wird, um referenzierte Objekte wie Bilder zu erhalten.<br/>            Die Verwendung dieses Resolvers könnte eine Schwachstelle erzeugen, wenn eine vom Client bereitgestellte HTML-Datei die Serversoftware dazu bringt, lokale oder Netzwerkdateien zu erhalten. Mit Vorsicht verwenden. Es wird empfohlen, HtmlExternalResolver überhaupt nicht anzugeben (es werden nur eingebettete Objekte gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene uri gültig ist. |
| [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver/) | Callback-Schnittstelle, die zum Auflösen externer Ressourcen während des Imports von Html-, Svg-Dokumenten verwendet wird. |
| [`IHtmlExternalResolver`](/slides/python-net/de/aspose.slides.importing/ihtmlexternalresolver/) | Callback-Schnittstelle, die von der HTML-Importroutine verwendet wird, um referenzierte Objekte wie Bilder zu erhalten. |
| [`PdfImportOptions`](/slides/python-net/de/aspose.slides.importing/pdfimportoptions/) | Stellt die PDF-Importoptionen dar. |