---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /fa/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

یک شیء باینری بزرگ (BLOB) داده باینری است که به‌صورت یک واحد ذخیره می‌شود - به‌عبارت‌دیگر BLOB می‌تواند یک صدا، ویدئو یا خود ارائه باشد. برای بهینه‌سازی مصرف حافظه هنگام کار با BLOBها از چندین تکنیک استفاده می‌شود – که می‌تواند قبلاً در ارائه ذخیره شده یا بعدها به‌صورت برنامه‌نویسی اضافه شود. با استفاده از [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) می‌توانید جنبه‌های مختلف رفتار مربوط به مدیریت BLOBها را برای طول عمر نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) تغییر دهید.
## Methods

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | این خصوصیت مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول زمان‌فعالیت نمونه باشد. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | این خصوصیت مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول زمان‌فعالیت نمونه باشد. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | این خصوصیت مشخص می‌کند که آیا می‌توان هنگام کار با BLOBها فایل‌های موقت ایجاد کرد، که به‌طور چشمگیری مصرف حافظه را کاهش می‌دهد اما برای ایجاد فایل‌ها نیاز به مجوز دارد. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | این خصوصیت مشخص می‌کند که آیا می‌توان هنگام کار با BLOBها فایل‌های موقت ایجاد کرد، که به‌طور چشمگیری مصرف حافظه را کاهش می‌دهد اما برای ایجاد فایل‌ها نیاز به مجوز دارد. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعیین می‌کند. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعیین می‌کند. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

این خصوصیت مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول زمان‌فعالیت نمونه باشد. اگر نمونه مالک باشد، منبع قفل می‌شود. این کمک می‌کند تا مصرف حافظه و کارآیی هنگام کار با BLOBها بهبود یابد، اما منبع (جریان یا فایل) در طول عمر نمونهٔ Presentation قابل تغییر نیست. این یک مثال است:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException به دلیل قفل بودن pres.pptx برای طول عمر Presentation پرتاب خواهد شد
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // پس از آزاد شدن شی Presentation، فایل قفل‌برداشته می‌شود و می‌تواند حذف شود
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**بازگشت:**  
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

این خصوصیت مشخص می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول زمان‌فعالیت نمونه باشد. اگر نمونه مالک باشد، منبع قفل می‌شود. این کمک می‌کند تا مصرف حافظه و کارآیی هنگام کار با BLOBها بهبود یابد، اما منبع (جریان یا فایل) در طول عمر نمونهٔ Presentation قابل تغییر نیست. این یک مثال است:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException به دلیل قفل بودن pres.pptx برای طول عمر Presentation پرتاب خواهد شد
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // پس از آزاد شدن شی Presentation، فایل قفل‌برداشته می‌شود و می‌تواند حذف شود
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

این خصوصیت مشخص می‌کند که آیا می‌توان هنگام کار با BLOBها فایل‌های موقت ایجاد کرد، که به‌طور چشمگیری مصرف حافظه را کاهش می‌دهد اما برای ایجاد فایل‌ها نیاز به مجوز دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد.

**بازگشت:**  
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

این خصوصیت مشخص می‌کند که آیا می‌توان هنگام کار با BLOBها فایل‌های موقت ایجاد کرد، که به‌طور چشمگیری مصرف حافظه را کاهش می‌دهد اما برای ایجاد فایل‌ها نیاز به مجوز دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشهٔ موقت سیستم استفاده می‌شود. فرآیند میزبانی باید مجوز ایجاد فایل و پوشه در این مسیر را داشته باشد.

**بازگشت:**  
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشهٔ موقت سیستم استفاده می‌شود. فرآیند میزبانی باید مجوز ایجاد فایل و پوشه در این مسیر را داشته باشد.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعیین می‌کند. به‌طور پیش‌فرض تمام BLOBها در حافظه بارگذاری می‌شوند؛ تنها پس از رسیدن به این حد از مکانیزم‌های جایگزین (مانند فایل‌های موقت) استفاده می‌شود. نگه داشتن BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما می‌تواند منجر به مصرف زیاد حافظه شود. از این خصوصیت برای تنظیم رفتار مطابق با محیط یا نیازهای خود استفاده کنید.

--------------------

این خصوصیت در صورتی که \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) به false تنظیم شود، نادیده گرفته می‌شود، زیرا در این حالت حافظه تنها محل ذخیره‌سازی موجود است و محدود کردن مصرف BLOBها در حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض ۶۲۹٬۱۴۵٬۶۰۰ بایت (۶۰۰ مب) است.

--------------------

ممکن است این خصوصیت را به صفر تنظیم کنید، اما مقدار حداقلی کوچک از حافظه همچنان رزرو خواهد شد.

**بازگشت:**  
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

حداکثر اندازهٔ کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعیین می‌کند. به‌طور پیش‌فرض تمام BLOBها در حافظه بارگذاری می‌شوند؛ تنها پس از رسیدن به این حد از مکانیزم‌های جایگزین (مانند فایل‌های موقت) استفاده می‌شود. نگه داشتن BLOBها در حافظه عملکرد را به حداکثر می‌رساند اما می‌تواند منجر به مصرف زیاد حافظه شود. از این خصوصیت برای تنظیم رفتار مطابق با محیط یا نیازهای خود استفاده کنید.

--------------------

این خصوصیت در صورتی که \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) به false تنظیم شود، نادیده گرفته می‌شود، زیرا در این حالت حافظه تنها محل ذخیره‌سازی موجود است و محدود کردن مصرف BLOBها در حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض ۶۲۹٬۱۴۵٬۶۰۰ بایت (۶۰۰ مب) است.

--------------------

ممکن است این خصوصیت را به صفر تنظیم کنید، اما مقدار حداقلی کوچک از حافظه همچنان رزرو خواهد شد.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |