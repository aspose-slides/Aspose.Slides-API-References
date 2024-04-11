---
title: aspose.slides.importing
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.importing/
---


## Classes

| Class | Description |
| :- | :- |
| [`ExternalResourceResolver`](/slides/python-net/aspose.slides.importing/externalresourceresolver/) | Callback class used to resolve external resources during Html, Svg documents import.<br/>            Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid. |
| [`HtmlExternalResolver`](/slides/python-net/aspose.slides.importing/htmlexternalresolver/) | Callback object used by HTML import routine to obtain referrenced objects such as images.<br/>            Using this resolver could create a vulnurability when client provided HTML file will make server software to obtain local or network file. Use with caution. It is recommended not to specify HtmlExternalResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid. |
| [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver/) | Callback interface used to resolve external resources during Html, Svg documents import. |
| [`IHtmlExternalResolver`](/slides/python-net/aspose.slides.importing/ihtmlexternalresolver/) | Callback interface used by HTML import routine to obtain referrenced objects such as images. |
| [`PdfImportOptions`](/slides/python-net/aspose.slides.importing/pdfimportoptions/) | Represents the PDF import options |

