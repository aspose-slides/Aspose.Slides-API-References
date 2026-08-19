---
title: DigitalSignature
second_title: مرجع API Aspose.Slides برای جاوا
description: امضای دیجیتال در فایل امضاشده.
type: docs
url: /fa/com.aspose.slides/digitalsignature/
---
**وراثت:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

امضای دیجیتال در فایل امضاشده.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // ایجاد نمونه Presentation
>  Presentation pres = new Presentation();
>  try {
>     // ایجاد شی DigitalSignature با فایل PFX و گذرواژه PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // افزودن توضیح به امضای دیجیتال جدید
>      signature.setComments("Aspose.Slides digital signing test.");
>      // افزودن امضای دیجیتال به ارائه
>      pres.getDigitalSignatures().add(signature);
>      // ذخیره ارائه
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // ایجاد نمونه Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // بررسی معتبر بودن همه امضاهای دیجیتال
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

## سازندها

| سازنده | شرح |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | یک شیء DigitalSignature جدید با گواهی‌نامه‌ی مشخص شده ایجاد می‌کند. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | یک شیء DigitalSignature جدید با مسیر فایل گواهی‌نامه و رمز عبور مشخص ایجاد می‌کند. |
## متدها

| متد | شرح |
| --- | --- |
| [getCertificate()](#getCertificate--) | شیء گواهی‌نامه‌ای که برای امضای سند استفاده شده است. |
| [isValid()](#isValid--) | اگر این امضای دیجیتال معتبر باشد و سند دستخوش تغییر نشده باشد، این مقدار true خواهد بود. |
| [getSignTime()](#getSignTime--) | زمان امضای سند. |
| [getComments()](#getComments--) | هدف امضا. |
| [setComments(String value)](#setComments-java.lang.String-) | هدف امضا. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


یک شیء DigitalSignature جدید با گواهی‌نامه‌ی مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| certData | byte[] | یک آرایه بایت شامل گواهی‌نامه |
| password | java.lang.String | رمز عبور مورد نیاز برای دسترسی به گواهی‌نامه. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


یک شیء DigitalSignature جدید با مسیر فایل گواهی‌نامه و رمز عبور مشخص ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filePath | java.lang.String | مسیر فایل حاوی گواهی‌نامه. |
| password | java.lang.String | رمز عبور مورد نیاز برای دسترسی به گواهی‌نامه. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


شیء گواهی‌نامه‌ای که برای امضای سند استفاده شده است. فقط-خواندنی byte[].

**بازگشت:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


اگر این امضای دیجیتال معتبر باشد و سند دستخوش تغییر نشده باشد، این مقدار true خواهد بود. فقط-خواندنی boolean.

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


زمان امضای سند. فقط-خواندنی java.util.Date.

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