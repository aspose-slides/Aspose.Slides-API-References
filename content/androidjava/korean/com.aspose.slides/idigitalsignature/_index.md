---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /ko/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

서명된 파일의 디지털 서명.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 문서를 서명하는 데 사용된 인증서 객체. |
| [isValid()](#isValid--) | 이 디지털 서명이 유효하고 문서가 변조되지 않은 경우 이 값은 true가 됩니다. |
| [getSignTime()](#getSignTime--) | 문서가 서명된 시점. |
| [getComments()](#getComments--) | 서명의 목적. |
| [setComments(String value)](#setComments-java.lang.String-) | 서명의 목적. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

문서를 서명하는 데 사용된 인증서 객체. 읽기 전용 byte[].

**반환값:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

이 디지털 서명이 유효하고 문서가 변조되지 않은 경우 이 값은 true가 됩니다. 읽기 전용 boolean.

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


**반환값:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

문서가 서명된 시점. 읽기 전용 java.util.Date.

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


**반환값:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

서명의 목적. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

서명의 목적. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |