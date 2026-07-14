---
title: Metered
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: روش‌هایی برای تنظیم کلید متر شده فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/metered/
---
**Inheritance:**  
java.lang.Object  
```
public class Metered
```

روش‌هایی برای تنظیم کلید متر شده فراهم می‌کند.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Metered()](#Metered--) | یک نمونه جدید از این کلاس را مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | کلید عمومی و خصوصی متر شده را تنظیم می‌کند. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | اندازه فایل مصرف را دریافت می‌کند |
| [getConsumptionCredit()](#getConsumptionCredit--) | اعتبار مصرف را دریافت می‌کند |
| [isMeteredLicensed()](#isMeteredLicensed--) | بررسی می‌کند که آیا متر شده دارای لایسنس است یا خیر |

### Metered() {#Metered--}
```
public Metered()
```

یک نمونه جدید از این کلاس را مقداردهی اولیه می‌کند.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

کلید عمومی و خصوصی متر شده را تنظیم می‌کند. اگر لایسنس متر شده خریداری کنید، هنگام شروع برنامه باید این API فراخوانی شود؛ معمولاً این کافی است. با این حال، اگر همیشه در بارگذاری داده‌های مصرف اشتباه شود و بیش از ۲۴ ساعت ادامه یابد، لایسنس به وضعیت ارزیابی تبدیل می‌شود؛ برای جلوگیری از این حالت، باید به‌طور منظم وضعیت لایسنس را بررسی کنید و اگر وضعیت ارزیابی بود، این API را دوباره فراخوانی کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| publicKey | java.lang.String | کلید عمومی |
| privateKey | java.lang.String | کلید خصوصی |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

اندازه فایل مصرف را دریافت می‌کند

**مقدار برگشتی:**
double

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

اعتبار مصرف را دریافت می‌کند

**مقدار برگشتی:**
double - consumption quantity

### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

بررسی می‌کند که آیا متر شده دارای لایسنس است یا خیر

**مقدار برگشتی:**
boolean - درست یا نادرست