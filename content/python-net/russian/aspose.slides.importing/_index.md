---
title: aspose.slides.importing
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.importing/
---
## Классы

| Класс | Описание |
| :- | :- |
| [`ExcelWorkbookImporter`](/slides/python-net/ru/aspose.slides.importing/excelworkbookimporter/) | Предоставляет функциональность импорта содержимого из рабочей книги Excel в презентацию. |
| [`ExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/externalresourceresolver/) | Класс обратного вызова, используемый для разрешения внешних ресурсов во время импорта документов Html, Svg.<br/>            Использование этого резольвера может создать уязвимость, когда предоставленный клиентом файл HTML или SVG заставит серверное программное обеспечение получить локальный или сетевой файл. Используйте с осторожностью. Рекомендуется не указывать ExternalResourceResolver вовсе (будут читаться только встроенные объекты) или создать подкласс, который проверяет, является ли указанный uri действительным. |
| [`HtmlExternalResolver`](/slides/python-net/ru/aspose.slides.importing/htmlexternalresolver/) | Объект обратного вызова, используемый процедурой импорта HTML для получения ссылочных объектов, таких как изображения.<br/>            Использование этого резольвера может создать уязвимость, когда предоставленный клиентом файл HTML заставит серверное программное обеспечение получить локальный или сетевой файл. Используйте с осторожностью. Рекомендуется не указывать HtmlExternalResolver вовсе (будут читаться только встроенные объекты) или создать подкласс, который проверяет, является ли указанный uri действительным. |
| [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver/) | Интерфейс обратного вызова, используемый для разрешения внешних ресурсов во время импорта документов Html, Svg. |
| [`IHtmlExternalResolver`](/slides/python-net/ru/aspose.slides.importing/ihtmlexternalresolver/) | Интерфейс обратного вызова, используемый процедурой импорта HTML для получения ссылочных объектов, таких как изображения. |
| [`PdfImportOptions`](/slides/python-net/ru/aspose.slides.importing/pdfimportoptions/) | Представляет параметры импорта PDF. |