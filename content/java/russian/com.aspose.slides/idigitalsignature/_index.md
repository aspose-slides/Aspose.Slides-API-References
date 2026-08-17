---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: Digital signature in signed file.
type: docs
url: /ru/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Цифровая подпись в подписанном файле.
## Методы

| Метод | Описание |
| --- | --- |
| [getCertificate()](#getCertificate--) | Объект сертификата, использованный для подписи документа. |
| [isValid()](#isValid--) | Если эта цифровая подпись действительна и документ не был изменён, это значение будет true. |
| [getSignTime()](#getSignTime--) | Время, когда документ был подписан. |
| [getComments()](#getComments--) | Назначение подписи. |
| [setComments(String value)](#setComments-java.lang.String-) | Назначение подписи. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Объект сертификата, использованный для подписи документа. Только для чтения byte[].

**Возвращает:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
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

**Возвращает:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

Время, когда документ был подписан. Только для чтения java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

Назначение подписи. Чтение/запись String.

**Возвращает:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Назначение подписи. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |