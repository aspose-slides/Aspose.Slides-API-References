---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /fa/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

یک شیء باینری بزرگ (BLOB) داده باینری است که به‌عنوان یک موجودیت واحد ذخیره می‌شود - به‌عبارت دیگر BLOB می‌تواند صدا، ویدیو یا خود ارائه باشد. تعداد زیادی از تکنیک‌ها برای بهینه‌سازی مصرف حافظه هنگام کار با BLOBها استفاده می‌شود - که ممکن است از قبل در ارائه ذخیره شده باشد یا به‌صورت برنامه‌نویسی بعداً اضافه شود. با استفاده از [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) می‌توانید جنبه‌های متفاوت رفتار مربوط به مدیریت BLOBها را برای طول عمر نمونه [IPresentation](../../com.aspose.slides/ipresentation) تغییر دهید.

## متدها

| متد | شرح |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | این ویژگی مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان در طول طول عمر نمونه باشد. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | این ویژگی مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان در طول طول عمر نمونه باشد. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | این ویژگی مشخص می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طور قابل توجهی مصرف حافظه را کاهش می‌دهد اما نیاز به اجازهٔ ایجاد فایل دارد. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | این ویژگی مشخص می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طور قابل توجهی مصرف حافظه را کاهش می‌دهد اما نیاز به اجازهٔ ایجاد فایل دارد. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

این ویژگی مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان در طول طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) نمی‌تواند در طول طول عمر نمونه Presentation تغییر کند. این یک مثال است:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException به دلیل قفل بودن pres.pptx برای طول عمر Presentation پرتاب می‌شود
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // پس از آزاد شدن شیء Presentation، فایل قفل‌برداری می‌شود و می‌تواند حذف شود
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**بازگشت:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

این ویژگی مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان در طول طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) نمی‌تواند در طول طول عمر نمونه Presentation تغییر کند. این یک مثال است:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException به دلیل قفل بودن pres.pptx برای طول عمر یک Presentation پرتاب خواهد شد
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // پس از آزاد شدن شیء Presentation، فایل قفل‌برداری می‌شود و می‌تواند حذف شود
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

این ویژگی مشخص می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طور قابل توجهی مصرف حافظه را کاهش می‌دهد اما نیاز به اجازهٔ ایجاد فایل دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد.

**بازگشت:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

این ویژگی مشخص می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طور قابل توجهی مصرف حافظه را کاهش می‌دهد اما نیاز به اجازهٔ ایجاد فایل دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشهٔ موقت سیستم استفاده می‌شود. فرآیند میزبانی باید اجازهٔ ایجاد فایل و پوشه در آنجا را داشته باشد.

**بازگشت:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشهٔ موقت سیستم استفاده می‌شود. فرآیند میزبانی باید اجازهٔ ایجاد فایل و پوشه در آنجا را داشته باشد.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ تنها وقتی که این حد برسد، مکانیسم‌های جایگزین (مانند فایل‌های موقت) به‌کار گرفته می‌شود. نگهداری BLOBها در حافظه عملکرد را حداکثر می‌کند اما می‌تواند منجر به استفادهٔ زیاد از حافظه شود. از این ویژگی برای تنظیم رفتار متناسب با محیط یا نیازهای خود استفاده کنید.

--------------------

این ویژگی نادیده گرفته می‌شود اگر \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) روی false تنظیم شود، زیرا در آن حالت حافظه تنها مکان ذخیره‌سازی در دسترس است و محدود کردن استفاده از BLOBها در حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض 629,145,600 بایت (600 مگابایت) است.

--------------------

می‌توانید این ویژگی را روی صفر تنظیم کنید، اما مقدار حداقل کوچکی از حافظه همچنان رزرو خواهد شد.

**بازگشت:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ تنها وقتی که این حد برسد، مکانیسم‌های جایگزین (مانند فایل‌های موقت) به‌کار گرفته می‌شود. نگهداری BLOBها در حافظه عملکرد را حداکثر می‌کند اما می‌تواند منجر به استفادهٔ زیاد از حافظه شود. از این ویژگی برای تنظیم رفتار متناسب با محیط یا نیازهای خود استفاده کنید.

--------------------

این ویژگی نادیده گرفته می‌شود اگر \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) روی false تنظیم شود، زیرا در آن حالت حافظه تنها مکان ذخیره‌سازی در دسترس است و محدود کردن استفاده از BLOBها در حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض 629,145,600 بایت (600 مگابایت) است.

--------------------

می‌توانید این ویژگی را روی صفر تنظیم کنید، اما مقدار حداقل کوچکی از حافظه همچنان رزرو خواهد شد.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | long |  |