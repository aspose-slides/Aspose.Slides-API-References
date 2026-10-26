---
title: DigitalSignature
second_title: Справочник API Aspose.Slides для Java
description: Цифровая подпись в подписанном файле.
type: docs
url: /ru/com.aspose.slides/digitalsignature/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Цифровая подпись в подписанном файле.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Инициализировать экземпляр Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Создать объект DigitalSignature с файлом PFX и паролем PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Добавить комментарий к новой цифровой подписи
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Добавить цифровую подпись к презентации
>      pres.getDigitalSignatures().add(signature);
>      // Сохранить презентацию
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Инициализировать экземпляр Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Проверить, являются ли все цифровые подписи действительными
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Создает новый объект DigitalSignature с указанным сертификатом. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Создает новый объект DigitalSignature с указанным путем к файлу сертификата и паролем. |

## Методы

| Метод | Описание |
| --- | --- |
| [getCertificate()](#getCertificate--) | Объект сертификата, который использовался для подписи документа. |
| [isValid()](#isValid--) | Если эта цифровая подпись действительна и документ не был изменён, это значение будет true. |
| [getSignTime()](#getSignTime--) | Время, когда документ был подписан. |
| [getComments()](#getComments--) | Назначение подписи. |
| [setComments(String value)](#setComments-java.lang.String-) | Назначение подписи. |

### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Создает новый объект DigitalSignature с указанным сертификатом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| certData | byte[] | массив байтов, содержащий сертификат |
| password | java.lang.String | Пароль, необходимый для доступа к сертификату. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Создает новый объект DigitalSignature с указанным путем к файлу сертификата и паролем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу с сертификатом. |
| password | java.lang.String | Пароль, необходимый для доступа к сертификату. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Объект сертификата, который использовался для подписи документа. Только для чтения byte[].

**Возвращаемое значение:**
byte[]

### isValid() {#isValid--}
```
public final boolean isValid()
```

Если эта цифровая подпись действительна и документ не был изменён, это значение будет true. Только для чтения boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:** boolean

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

Время, когда документ был подписан. Только для чтения java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:** java.util.Date

### getComments() {#getComments--}
```
public final String getComments()
```

Назначение подписи. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Назначение подписи. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |