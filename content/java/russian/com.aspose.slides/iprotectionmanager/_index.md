---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Управление защитой презентации паролем.
type: docs
url: /ru/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Управление защитой презентации паролем.
## Методы

| Метод | Описание |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Это свойство имеет смысл, если презентация защищена паролем. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Это свойство имеет смысл, если презентация защищена паролем. |
| [isEncrypted()](#isEncrypted--) | Возвращает значение, указывающее, зашифровано ли данный экземпляр. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла являются публичными. |
| [isWriteProtected()](#isWriteProtected--) | Возвращает значение, указывающее, защищена ли данная презентация от записи. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Возвращает пароль шифрования. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Получает или задаёт рекомендацию только для чтения. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Получает или задаёт рекомендацию только для чтения. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Шифрует презентацию с указанным паролем. |
| [removeEncryption()](#removeEncryption--) | Удаляет шифрование. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Устанавливает защиту от записи для этой презентации с указанным паролем. |
| [removeWriteProtection()](#removeWriteProtection--) | Удаляет защиту от записи для этой презентации. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Определяет, защищена ли презентация паролем для изменения. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, пока презентация зашифрована. Чтение/запись булево.

**Возвращаемое значение:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, пока презентация зашифрована. Чтение/запись булево.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Возвращает значение, указывающее, зашифровано ли данный экземпляр. Только для чтения, булево.

Значение: true, если презентация была загружена из зашифрованного файла или был вызван метод \#encrypt(String).encrypt(String); в противном случае — false.

**Возвращаемое значение:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла являются публичными. Значение true означает, что из зашифрованного файла презентации загружаются только свойства документа без использования пароля. Значение false означает, что загружается вся зашифрованная презентация с использованием правильного пароля, а не только свойства документа. Если презентация не зашифрована, то значение свойства всегда false. Если свойства документа зашифрованного файла не публичны, то значение свойства всегда false. Если PresentationEx.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false. Только для чтения, булево.

**Возвращаемое значение:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Возвращает значение, указывающее, защищена ли данная презентация от записи. Только для чтения, булево.

**Возвращаемое значение:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Возвращает пароль шифрования. Только для чтения, строка.

**Возвращаемое значение:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Получает или задаёт рекомендацию только для чтения. Чтение/запись булево.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Возвращаемое значение:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Получает или задаёт рекомендацию только для чтения. Чтение/запись булево.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Шифрует презентацию с указанным паролем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Пароль. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Удаляет шифрование.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Устанавливает защиту от записи для этой презентации с указанным паролем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Удаляет защиту от записи для этой презентации.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Определяет, защищена ли презентация паролем для изменения.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль для проверки. |

1. Перед вызовом этого метода следует проверить свойство (\#isWriteProtected.isWriteProtected). 2. Если пароль равен null или пустой строке, метод возвращает false.

**Возвращаемое значение:**
boolean — true, если пароль действителен; в противном случае — false.