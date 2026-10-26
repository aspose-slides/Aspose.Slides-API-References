---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: روش‌هایی برای صدور مجوز به مؤلفه فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ilicense/
---```
public interface ILicense
```

روش‌هایی برای صدور مجوز به مؤلفه فراهم می‌کند.

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
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | مجوز را برای مؤلفه فراهم می‌کند. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | مجوز را برای مؤلفه فراهم می‌کند. |
| [resetLicense()](#resetLicense--) | مجوز را بازنشانی می‌کند. |
| [isLicensed()](#isLicensed--) | بررسی می‌کند آیا مجوز برای مؤلفه اعمال شده است. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

مجوز را برای مؤلفه فراهم می‌کند.

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
| licenseName | java.lang.String | می‌تواند نام کامل یا کوتاه یک فایل یا نام یک منبع داخلی باشد. برای انتقال به حالت ارزیابی یک رشتهٔ خالی استفاده کنید. |

--------------------

سعی می‌کند مجوز را در مکان‌های زیر پیدا کند:

1. مسیر صریح.
2. پوشهٔ اسمبلی مؤلفه.
3. پوشهٔ اسمبلی فراخوانی‌کنندهٔ مشتری.
4. پوشهٔ اسمبلی ورودی.
5. منبع داخلی در اسمبلی فراخوانی‌کنندهٔ مشتری. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

مجوز را برای مؤلفه فراهم می‌کند.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که شامل مجوز است. |

--------------------

از این متد برای بارگذاری مجوز از یک جریان استفاده کنید. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

مجوز را بازنشانی می‌کند.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

از این متد برای بازنشانی مجوز در مؤلفه استفاده کنید.

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

بررسی می‌کند آیا مجوز برای مؤلفه اعمال شده است.

**باز می‌گردد:**
boolean - true اگر مؤلفه دارای مجوز باشد، در غیر این صورت false