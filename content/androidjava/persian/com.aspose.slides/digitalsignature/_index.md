---
title: DigitalSignature
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: امضای دیجیتال در فایل امضا شده.
type: docs
url: /fa/com.aspose.slides/digitalsignature/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

امضای دیجیتال در فایل امضا شده.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // یک شیء Presentation را مقداردهی اولیه کنید
>  Presentation pres = new Presentation();
>  try {
>     // ایجاد شیء DigitalSignature با فایل PFX و رمز عبور PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // نظر به امضای دیجیتال جدید
>      signature.setComments("Aspose.Slides digital signing test.");
>      // اضافه کردن امضای دیجیتال به ارائه
>      pres.getDigitalSignatures().add(signature);
>      // ذخیره ارائه
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // یک شیء Presentation را مقداردهی اولیه کنید
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // بررسی اینکه آیا تمام امضاهای دیجیتال معتبر هستند
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

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | یک شیء DigitalSignature جدید با گواهی‌نامه مشخص‌شده ایجاد می‌کند. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | یک شیء DigitalSignature جدید با مسیر فایل گواهی‌نامه و رمز عبور مشخص‌شده ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getCertificate()](#getCertificate--) | شیء Certificate که برای امضای سند استفاده شده است. |
| [isValid()](#isValid--) | اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار true خواهد بود. |
| [getSignTime()](#getSignTime--) | زمانی که سند امضا شده است. |
| [getComments()](#getComments--) | هدف امضا. |
| [setComments(String value)](#setComments-java.lang.String-) | هدف امضا. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


یک شیء DigitalSignature جدید با گواهی‌نامه مشخص‌شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| certData | byte[] | آرایه بایتی حاوی گواهی‌نامه |
| password | java.lang.String | رمز عبوری که برای دسترسی به گواهی‌نامه لازم است. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


یک شیء DigitalSignature جدید با مسیر فایل گواهی‌نامه و رمز عبور مشخص‌شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filePath | java.lang.String | مسیر فایل حاوی گواهی‌نامه. |
| password | java.lang.String | رمز عبوری که برای دسترسی به گواهی‌نامه لازم است. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


شیء Certificate که برای امضای سند استفاده شده است. فقط-خواندنی byte[].

**بازگشت:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار true خواهد بود. فقط-خواندنی boolean.

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
public final Date getSignTime()
```


زمانی که سند امضا شده است. فقط-خواندنی java.util.Date.

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

**بازگشت:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


هدف امضا. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


هدف امضا. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |