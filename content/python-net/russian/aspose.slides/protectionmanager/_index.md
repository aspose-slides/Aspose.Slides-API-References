---
title: ProtectionManager class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/protectionmanager/
---
## ProtectionManager класс

Presentation password protection management.

The ProtectionManager type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/ru/aspose.slides/protectionmanager/encrypt_document_properties/) | Это свойство имеет смысл, если презентация защищена паролем.<br/>            Если true, то свойства документа зашифрованы в файле презентации.<br/>            Если false, то свойства документа публичны, пока презентация зашифрована.<br/>            Чтение/запись **bool**. |
| [`is_encrypted`](/slides/python-net/ru/aspose.slides/protectionmanager/is_encrypted/) | Возвращает значение, указывающее, зашифровано ли этот экземпляр.<br/>            Только для чтения **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/ru/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла публичны.<br/>            Значение true означает, что только свойства документа загружаются из зашифрованного файла презентации без использования пароля.<br/>            Значение false означает, что вся зашифрованная презентация загружается с использованием правильного пароля, а не только свойства документа.<br/>            Если презентация не зашифрована, то значение свойства всегда false.<br/>            Если свойства документа зашифрованного файла не публичны, то значение свойства всегда false.<br/>            Если Presentation.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false.<br/>            Только для чтения **bool**. |
| [`is_write_protected`](/slides/python-net/ru/aspose.slides/protectionmanager/is_write_protected/) | Возвращает значение, указывающее, защищена ли эта презентация от записи.<br/>            Только для чтения **bool**. |
| [`encryption_password`](/slides/python-net/ru/aspose.slides/protectionmanager/encryption_password/) | Возвращает пароль, используемый для шифрования презентации.<br/>            Только для чтения **str**. |
| [`read_only_recommended`](/slides/python-net/ru/aspose.slides/protectionmanager/read_only_recommended/) | Возвращает или задаёт рекомендацию только для чтения.<br/>            Чтение/запись **bool**. |

## Методы

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/ru/aspose.slides/protectionmanager/encrypt/#str) | Шифрует презентацию с указанным паролем. |
| [`remove_encryption(self)`](/slides/python-net/ru/aspose.slides/protectionmanager/remove_encryption/#) | Удаляет шифрование. |
| [`set_write_protection(self, password)`](/slides/python-net/ru/aspose.slides/protectionmanager/set_write_protection/#str) | Устанавливает защиту от записи для этой презентации с указанным паролем. |
| [`remove_write_protection(self)`](/slides/python-net/ru/aspose.slides/protectionmanager/remove_write_protection/#) | Снимает защиту от записи для этой презентации. |
| [`check_write_protection(self, password)`](/slides/python-net/ru/aspose.slides/protectionmanager/check_write_protection/#str) | Определяет, защищена ли презентация паролем для изменения. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)