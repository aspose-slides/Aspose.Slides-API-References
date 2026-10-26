---
title: ProtectionManager
second_title: Aspose.Slides для Android через справочник Java API
description: Управление защитой презентации паролем.
type: docs
url: /ru/com.aspose.slides/protectionmanager/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Управление защитой презентации паролем.
## Методы

| Метод | Описание |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Это свойство имеет смысл, если презентация защищена паролем. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Это свойство имеет смысл, если презентация защищена паролем. |
| [isEncrypted()](#isEncrypted--) | Возвращает значение, указывающее, зашифровано ли данный экземпляр. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла являются публичными. |
| [isWriteProtected()](#isWriteProtected--) | Возвращает значение, указывающее, защищена ли эта презентация от записи. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Шифрует Presentation указанным паролем. |
| [removeEncryption()](#removeEncryption--) | Удаляет шифрование. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Устанавливает защиту от записи для этой презентации с указанным паролем. |
| [removeWriteProtection()](#removeWriteProtection--) | Снимает защиту от записи для этой презентации. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Определяет, защищена ли презентация паролем для изменения. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Возвращает пароль, используемый для шифрования презентации. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Получает или задает рекомендацию только для чтения. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Получает или задает рекомендацию только для чтения. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, в то время как презентация зашифрована. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, в то время как презентация зашифрована. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Возвращает значение, указывающее, зашифровано ли данный экземпляр. Только для чтения boolean.

Значение: true, если презентация была загружена из зашифрованного файла или был вызван метод \#encrypt(String).encrypt(String); иначе false.

**Возвращаемое значение:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла публичны. Значение true означает, что только свойства документа загружаются из зашифрованного файла презентации без использования пароля. Значение false означает, что загружается вся зашифрованная презентация с использованием правильного пароля, а не только свойства документа. Если презентация не зашифрована, то значение свойства всегда false. Если свойства документа зашифрованного файла не публичны, то значение свойства всегда false. Если Presentation.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Возвращает значение, указывающее, защищена ли эта презентация от записи. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Шифрует Presentation указанным паролем.

--------------------

> ```
> Следующий пример кода показывает, как зашифровать презентацию PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Пароль. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Удаляет шифрование.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Устанавливает защиту от записи для этой презентации с указанным паролем.

--------------------

> ```
> Следующий пример кода показывает, как установить защиту от записи для презентации.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Снимает защиту от записи для этой презентации.

--------------------

> ```
> Этот пример кода показывает, как снять защиту от записи с презентации PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
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

1. Необходимо проверить свойство (\#isWriteProtected.isWriteProtected) перед вызовом этого метода. 2. Когда пароль равен null или пуст, этот метод возвращает false. |

**Возвращаемое значение:**
boolean - True, если пароль действителен; иначе false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Возвращает пароль, используемый для шифрования презентации. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Получает или задает рекомендацию только для чтения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Получает или задает рекомендацию только для чтения. Чтение/запись boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |