---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: روش‌هایی برای مجوزدهی به کامپوننت فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ilicense/
---```
public interface ILicense
```

روش‌هایی برای مجوزدهی به کامپوننت فراهم می‌کند.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | مجوز کامپوننت را تنظیم می‌کند. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | مجوز کامپوننت را تنظیم می‌کند. |
| [resetLicense()](#resetLicense--) | مجوز را بازنشانی کنید |
| [isLicensed()](#isLicensed--) | بررسی کنید که آیا مجوز برای کامپوننت اعمال شده است یا نه |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


مجوز کامپوننت را تنظیم می‌کند.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| licenseName | java.lang.String | می‌تواند یک نام فایل کامل یا کوتاه یا نام یک منبع جاسازی‌شده باشد. برای استفاده در حالت ارزیابی یک رشته خالی را استفاده کنید.

--------------------

سعی می‌کند مجوز را در مکان‌های زیر پیدا کند:

1. مسیر صریح.

2. پوشهٔ اسمبلی کامپوننت.

3. پوشهٔ اسمبلی فراخوانی‌کنندهٔ مشتری.

4. پوشهٔ اسمبلی ورودی.

5. یک منبع جاسازی‌شده در اسمبلی فراخوانی‌کنندهٔ مشتری. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


مجوز کامپوننت را تنظیم می‌کند.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که شامل مجوز است.

--------------------

از این متد برای بارگذاری مجوز از یک جریان استفاده کنید. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


مجوز را بازنشانی کنید

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

از این متد برای بازنشانی مجوز در کامپوننت استفاده کنید

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


بررسی کنید که آیا مجوز برای کامپوننت اعمال شده است یا نه

**بازگشت:**
boolean - true اگر کامپوننت دارای مجوز باشد، در غیر این صورت false