---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Управление защитой паролем презентации.
type: docs
url: /ru/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Управление защитой паролем презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Это свойство имеет смысл, если презентация защищена паролем. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Это свойство имеет смысл, если презентация защищена паролем. |
| [isEncrypted()](#isEncrypted--) | Получает значение, указывающее, зашифрован ли данный экземпляр. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла публичны. |
| [isWriteProtected()](#isWriteProtected--) | Получает значение, указывающее, защищена ли данная презентация от записи. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Возвращает пароль шифрования. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Получает или задаёт рекомендацию только для чтения. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Получает или задаёт рекомендацию только для чтения. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Шифрует презентацию с заданным паролем. |
| [removeEncryption()](#removeEncryption--) | Удаляет шифрование. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Устанавливает защиту от записи для этой презентации с заданным паролем. |
| [removeWriteProtection()](#removeWriteProtection--) | Снимает защиту от записи для этой презентации. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Определяет, защищена ли презентация паролем для изменения. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, пока презентация зашифрована. Чтение/запись boolean.

**Возвращает:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, пока презентация зашифрована. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Получает значение, указывающее, зашифрован ли данный экземпляр. Только чтение boolean.

Значение: true, если презентация была загружена из зашифрованного файла или был вызван метод \#encrypt(String).encrypt(String); иначе false.

**Возвращает:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла публичны. Значение true означает, что из зашифрованного файла презентации загружаются только свойства документа без использования пароля. Значение false означает, что загружается вся зашифрованная презентация с использованием правильного пароля, а не только свойства документа. Если презентация не зашифрована, то значение свойства всегда false. Если свойства документа зашифрованного файла не публичны, то значение свойства всегда false. Если PresentationEx.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false. Только чтение boolean.

**Возвращает:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Получает значение, указывающее, защищена ли данная презентация от записи. Только чтение boolean.

**Возвращает:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Возвращает пароль шифрования. Только чтение String.

**Возвращает:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Получает или задаёт рекомендацию только для чтения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Возвращает:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Получает или задаёт рекомендацию только для чтения. Чтение/запись boolean.

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

Шифрует презентацию с заданным паролем.

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

Устанавливает защиту от записи для этой презентации с заданным паролем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Снимает защиту от записи для этой презентации.
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
| password | java.lang.String | Пароль для проверки.

--------------------

1. Вы должны проверить свойство (\#isWriteProtected.isWriteProtected) перед вызовом этого метода. 2. Когда пароль null или пустой, этот метод возвращает false. |
**Возвращает:**
boolean - True if the password is valid; otherwise, false.