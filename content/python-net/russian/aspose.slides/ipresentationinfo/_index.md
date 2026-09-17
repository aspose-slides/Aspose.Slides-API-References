---
title: IPresentationInfo class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ipresentationinfo/
---
## IPresentationInfo класс

Информация о файле презентации

The IPresentationInfo type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/ru/aspose.slides/ipresentationinfo/is_encrypted/) | Returns True if binded presentation is encrypted, otherwise False.<br/>            Only for reading **bool**. |
| [`is_password_protected`](/slides/python-net/ru/aspose.slides/ipresentationinfo/is_password_protected/) | Returns a value that indicates whether a binded presentation is protected by a password to open. |
| [`is_write_protected`](/slides/python-net/ru/aspose.slides/ipresentationinfo/is_write_protected/) | Returns a value that indicates whether a binded presentation is write protected. |
| [`load_format`](/slides/python-net/ru/aspose.slides/ipresentationinfo/load_format/) | Returns format of the binded presentation.<br/>            Only for reading [`LoadFormat`](/slides/python-net/ru/aspose.slides/loadformat). |

## Методы

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/ru/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Writes binded presentation to stream. |
| [`write_binded_presentation(self, file)`](/slides/python-net/ru/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Writes binded presentation to file. |
| [`check_password(self, password)`](/slides/python-net/ru/aspose.slides/ipresentationinfo/check_password/#str) | Checks whether a password is correct for a presentation protected with open password. |
| [`check_write_protection(self, password)`](/slides/python-net/ru/aspose.slides/ipresentationinfo/check_write_protection/#str) | Checks whether a password to modify is correct for a write protected presentation. |
| [`read_document_properties(self)`](/slides/python-net/ru/aspose.slides/ipresentationinfo/read_document_properties/#) | Returns document properties of binded presentation. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/ru/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Updates properties of binded presentation. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)