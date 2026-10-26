---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Цифровая подпись в подписанном файле.
type: docs
url: /ru/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Цифровая подпись в подписанном файле.
## Методы

| Метод | Описание |
| --- | --- |
| [getCertificate()](#getCertificate--) | Объект сертификата, который использовался для подписи документа. |
| [isValid()](#isValid--) | Если эта цифровая подпись действительна и документ не был подделан, это значение будет истинным. |
| [getSignTime()](#getSignTime--) | Время, когда документ был подписан. |
| [getComments()](#getComments--) | Назначение подписи. |
| [setComments(String value)](#setComments-java.lang.String-) | Назначение подписи. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Объект сертификата, который использовался для подписи документа. Только для чтения byte[].

**Возвращаемое значение:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Если эта цифровая подпись действительна и документ не был подделан, это значение будет истинным. Только для чтения boolean.

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

**Возвращаемое значение:**
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

**Возвращаемое значение:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

Назначение подписи. Чтение/запись String.

**Возвращаемое значение:**
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