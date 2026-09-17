---
title: PresentationInfo class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/presentationinfo/
---
## PresentationInfo класс

Информация о файле презентации

Тип PresentationInfo предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_encrypted`](/slides/python-net/ru/aspose.slides/presentationinfo/is_encrypted/) | Возвращает True, если привязанная презентация зашифрована, иначе False.<br/>            Только для чтения **bool**. |
| [`is_password_protected`](/slides/python-net/ru/aspose.slides/presentationinfo/is_password_protected/) | Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия. |
| [`is_write_protected`](/slides/python-net/ru/aspose.slides/presentationinfo/is_write_protected/) | Возвращает значение, указывающее, защищена ли привязанная презентация от записи. |
| [`load_format`](/slides/python-net/ru/aspose.slides/presentationinfo/load_format/) | Возвращает формат привязанной презентации.<br/>            Только для чтения [`LoadFormat`](/slides/python-net/ru/aspose.slides/loadformat). |

## Методы

| Метод | Описание |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/ru/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Записывает привязанную презентацию в поток. |
| [`write_binded_presentation(self, file)`](/slides/python-net/ru/aspose.slides/presentationinfo/write_binded_presentation/#str) | Записывает привязанную презентацию в файл. |
| [`check_password(self, password)`](/slides/python-net/ru/aspose.slides/presentationinfo/check_password/#str) | Проверяет, правильный ли пароль для презентации, защищённой паролем открытия. |
| [`check_write_protection(self, password)`](/slides/python-net/ru/aspose.slides/presentationinfo/check_write_protection/#str) | Проверяет, правильный ли пароль для изменения у презентации, защищённой от записи. |
| [`read_document_properties(self)`](/slides/python-net/ru/aspose.slides/presentationinfo/read_document_properties/#) | Возвращает свойства документа привязанной презентации. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/ru/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Обновляет свойства привязанной презентации. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)