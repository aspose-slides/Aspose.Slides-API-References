---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions Перечисление

Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом.

Тип PdfAccessPermissions содержит следующие члены:

## Поля

| Поле | Описание |
| :- | :- |
| NONE | Указывает, что у пользователя нет разрешений доступа. |
| PRINT_DOCUMENT | Указывает, может ли пользователь печатать документ (возможно, не в самом высоком качестве, в зависимости от <br/>            установлен ли также бит [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT)). |
| MODIFY_CONTENT | Указывает, может ли пользователь изменять содержимое документа операциями, отличными от контролируемых<br/>            битами [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Указывает, может ли пользователь копировать или иначе извлекать текст и графику из документа операциями <br/>            , отличными от контролируемых битом [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Указывает, может ли пользователь добавлять или изменять текстовые аннотации, заполнять интерактивные поля формы и, если бит<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) также установлен, создавать или изменять интерактивные поля формы (включая поля подписи <br/>            ). |
| FILL_EXISTING_FIELDS | Указывает, может ли пользователь заполнять существующие интерактивные поля формы (включая поля подписи), даже если<br/>            бит [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) сброшен. |
| EXTRACT_TEXT_AND_GRAPHICS | Указывает, может ли пользователь извлекать текст и графику в целях обеспечения доступности для пользователей с ограниченными возможностями<br/>            или в иных целях. |
| ASSEMBLE_DOCUMENT | Указывает, может ли пользователь собирать документ (вставлять, вращать или удалять страницы и создавать закладки или<br/>            миниатюры), даже если бит [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) сброшен. |
| HIGH_QUALITY_PRINT | Указывает, может ли пользователь печатать документ в представление, из которого может быть сгенерирована точная цифровая копия<br/>            содержимого PDF. Когда этот бит сброшен (и бит [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) установлен),<br/>            печать ограничивается низкоуровневым представлением внешнего вида, возможно, ухудшенного качества. |


### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)