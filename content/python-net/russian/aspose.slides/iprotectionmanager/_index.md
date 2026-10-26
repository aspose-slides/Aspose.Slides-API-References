---
title: IProtectionManager class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/iprotectionmanager/
---
## IProtectionManager класс

Presentation password protection management.

The IProtectionManager type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/ru/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Это свойство имеет смысл, если презентация защищена паролем.<br/>            Если true, то свойства документа зашифрованы в файле презентации.<br/>            Если false, то свойства документа открыты, в то время как презентация зашифрована.<br/>            Чтение/запись **bool**. |
| [`is_encrypted`](/slides/python-net/ru/aspose.slides/iprotectionmanager/is_encrypted/) | Получает значение, указывающее, зашифровано ли данный экземпляр.<br/>            Только чтение **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/ru/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа <br/>            этого файла открыты.<br/>            Значение true означает, что только свойства документа загружаются из зашифрованного <br/>            файла презентации без использования пароля.<br/>            Значение false означает, что вся зашифрованная презентация загружается с использованием правильного <br/>            пароля, а не только свойства документа.<br/>            Если презентация не зашифрована, то значение свойства всегда false.<br/>            Если свойства документа зашифрованного файла не открыты, то значение свойства всегда false.<br/>            Если PresentationEx.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded <br/>            всегда false.<br/>            Только чтение **bool**. |
| [`is_write_protected`](/slides/python-net/ru/aspose.slides/iprotectionmanager/is_write_protected/) | Получает значение, указывающее, защищена ли эта презентация от записи.<br/>            Только чтение **bool**. |
| [`encryption_password`](/slides/python-net/ru/aspose.slides/iprotectionmanager/encryption_password/) | Возвращает пароль шифрования.<br/>            Только чтение **str**. |
| [`read_only_recommended`](/slides/python-net/ru/aspose.slides/iprotectionmanager/read_only_recommended/) | Получает или задаёт рекомендацию только для чтения.<br/>            Чтение/запись **bool**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/ru/aspose.slides/iprotectionmanager/encrypt/#str) | Шифрует Presentation с указанным паролем. |
| [`remove_encryption(self)`](/slides/python-net/ru/aspose.slides/iprotectionmanager/remove_encryption/#) | Удаляет шифрование. |
| [`set_write_protection(self, password)`](/slides/python-net/ru/aspose.slides/iprotectionmanager/set_write_protection/#str) | Устанавливает защиту от записи для этой презентации с указанным паролем. |
| [`remove_write_protection(self)`](/slides/python-net/ru/aspose.slides/iprotectionmanager/remove_write_protection/#) | Удаляет защиту от записи для этой презентации. |
| [`check_write_protection(self, password)`](/slides/python-net/ru/aspose.slides/iprotectionmanager/check_write_protection/#str) | Определяет, защищена ли презентация паролем для изменения. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)