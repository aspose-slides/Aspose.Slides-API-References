---
title: IProtectionManager
second_title: Справочник по API Aspose.Slides для .NET
description: Управление защитой паролем презентации.
type: docs
weight: 6260
url: /ru/net/aspose.slides/iprotectionmanager/
---
## IProtectionManager interface

Управление защитой паролем презентации.

```csharp
public interface IProtectionManager
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/iprotectionmanager/encryptdocumentproperties) { get; set; } | Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа шифруются в файле презентации. Если false, то свойства документа являются общедоступными, а представление зашифровано. Чтение/записьBoolean. |
| [EncryptionPassword](../../aspose.slides/iprotectionmanager/encryptionpassword) { get; } | Возвращает пароль шифрования. Только чтениеString. |
| [IsEncrypted](../../aspose.slides/iprotectionmanager/isencrypted) { get; } | Получает значение, указывающее, зашифрован ли этот экземпляр. Только чтениеBoolean. |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/iprotectionmanager/isonlydocumentpropertiesloaded) { get; } | Это свойство имеет смысл, если файл презентации защищен паролем и документ свойства этого файла общедоступны. Значение true означает, что из зашифрованного файла презентации загружаются только свойства документа без использования пароля. Значение false означает, что вся зашифрованная презентация загружается с использованием правильного пароля, а не только свойства документа. Если представление не зашифровано, то значение свойства всегда равно false. Если свойства документа зашифрованного файла не являются общедоступными, то значение свойства всегда равно false. Если PresentationEx.EncryptDocumentProperties имеет значение true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда равно false. Только чтениеBoolean. |
| [IsWriteProtected](../../aspose.slides/iprotectionmanager/iswriteprotected) { get; } | Получает значение, указывающее, защищена ли эта презентация от записи. Только чтениеBoolean. |
| [ReadOnlyRecommended](../../aspose.slides/iprotectionmanager/readonlyrecommended) { get; set; } | Получает или задает рекомендацию только для чтения. Чтение/записьBoolean. |

## Методы

| Имя | Описание |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/iprotectionmanager/checkwriteprotection)(string) | Определяет, защищена ли презентация паролем для изменения. |
| [Encrypt](../../aspose.slides/iprotectionmanager/encrypt)(string) | Шифрует презентацию с указанным паролем. |
| [RemoveEncryption](../../aspose.slides/iprotectionmanager/removeencryption)() | Удаляет шифрование. |
| [RemoveWriteProtection](../../aspose.slides/iprotectionmanager/removewriteprotection)() | Снимает защиту от записи для этой презентации. |
| [SetWriteProtection](../../aspose.slides/iprotectionmanager/setwriteprotection)(string) | Установить защиту от записи для этой презентации с указанным паролем. |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->