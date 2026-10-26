---
title: Metered
second_title: Aspose.Slides برای Java مرجع API
description: متدهایی برای تنظیم کلید متری فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/metered/
---
**ارث‌بری:**
java.lang.Object
```
public class Metered
```

متدهایی برای تنظیم کلید متری ارائه می‌دهد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Metered()](#Metered--) | یک نمونه جدید از این کلاس را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | کلید عمومی و خصوصی متری را تنظیم می‌کند. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | اندازهٔ فایل مصرف را دریافت می‌کند |
| [getConsumptionCredit()](#getConsumptionCredit--) | اعتبار مصرف را دریافت می‌کند |
| [isMeteredLicensed()](#isMeteredLicensed--) | بررسی می‌کند که آیا متری مجوز دارد یا خیر |
### Metered() {#Metered--}
```
public Metered()
```

یک نمونه جدید از این کلاس را مقداردهی اولیه می‌کند.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

کلید عمومی و خصوصی متری را تنظیم می‌کند. اگر مجوز متری را خریداری کنید، هنگام شروع برنامه باید این API فراخوانی شود؛ معمولاً این کافی است. اما اگر همیشه در بارگذاری داده‌های مصرف شکست خورده و بیش از ۲۴ ساعت زمان بگذرد، مجوز به وضعیت ارزیابی تغییر می‌یابد؛ برای جلوگیری از این حالت باید به‌طور منظم وضعیت مجوز را بررسی کنید و اگر در وضعیت ارزیابی باشد، این API را دوباره فراخوانی کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| publicKey | java.lang.String | کلید عمومی |
| privateKey | java.lang.String | کلید خصوصی |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

اندازهٔ فایل مصرف را دریافت می‌کند

**بازگشت:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

اعتبار مصرف را دریافت می‌کند

**بازگشت:**
double - مقدار مصرف
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

بررسی می‌کند که آیا متری مجوز دارد یا خیر

**بازگشت:**
boolean - True یا false