---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: امضای دیجیتال در فایل امضا شده.
type: docs
url: /fa/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

امضای دیجیتال در فایل امضا شده.
## متدها

| متد | توضیح |
| --- | --- |
| [getCertificate()](#getCertificate--) | شیء Certificate که برای امضای سند استفاده شده است. |
| [isValid()](#isValid--) | اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار true خواهد بود. |
| [getSignTime()](#getSignTime--) | زمانی که سند امضا شد. |
| [getComments()](#getComments--) | هدف امضا. |
| [setComments(String value)](#setComments-java.lang.String-) | هدف امضا. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


شیء Certificate که برای امضای سند استفاده شده است. فقط خواندنی byte[].

**بازگشت:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار true خواهد بود. فقط خواندنی boolean.

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


**بازگشت:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```


زمانی که سند امضا شد. فقط خواندنی java.util.Date.

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


**بازگشت:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```


هدف امضا. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


هدف امضا. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |