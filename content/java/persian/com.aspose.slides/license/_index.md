---
title: License
second_title: Aspose.Slides برای Java مرجع API
description: روش‌هایی برای صدور مجوز به مؤلفه فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/license/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

روش‌هایی برای صدور مجوز به مؤلفه ارائه می‌دهد.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [License()](#License--) | یک نمونه جدید از این کلاس را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | به مؤلفه مجوز می‌دهد. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | به مؤلفه مجوز می‌دهد. |
| [getVersion()](#getVersion--) | نسخه Aspose.Slides for Java را برمی‌گرداند. |
| [resetLicense()](#resetLicense--) | مجوز را بازنشانی می‌کند. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

یک نمونه جدید از این کلاس را مقداردهی اولیه می‌کند.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

به مؤلفه مجوز می‌دهد.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | یک جریان که شامل مجوز است. برای تغییر به حالت ارزیابی از null استفاده کنید. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

به مؤلفه مجوز می‌دهد.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| namePath | java.lang.String | می‌تواند نام کامل یا کوتاه یک فایل یا نام یک منبع توکار باشد. برای تغییر به حالت ارزیابی از رشته خالی استفاده کنید. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

نسخه Aspose.Slides for Java را برمی‌گرداند.

**بازگرداندن:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

مجوز را بازنشانی می‌کند. از این متد برای بازنشانی مجوز در مؤلفه استفاده کنید.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

بررسی می‌کند که آیا مجوز بر مؤلفه اعمال شده است یا نه

**بازگرداندن:**
boolean