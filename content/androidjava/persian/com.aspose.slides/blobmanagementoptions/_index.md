---
title: BlobManagementOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گزینه‌هایی است که می‌توان برای مدیریت قوانین پردازش BLOB و تنظیمات دیگر BLOB استفاده کرد.
type: docs
url: /fa/com.aspose.slides/blobmanagementoptions/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

نمایانگر گزینه‌هایی است که می‌توان برای مدیریت قوانین پردازش BLOB و تنظیمات دیگر BLOB استفاده کرد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | گزینه‌های پیش‌فرض مدیریت blob را ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما نیاز به اجازه ایجاد فایل‌ها دارد. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما نیاز به اجازه ایجاد فایل‌ها دارد. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | حداکثر اندازه کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | حداکثر اندازه کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

گزینه‌های پیش‌فرض مدیریت blob را ایجاد می‌کند.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) در طول عمر نمونه Presentation نمی‌تواند تغییر کند.

**بازگشت:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان - در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) در طول عمر نمونه Presentation نمی‌تواند تغییر کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما نیاز به اجازه ایجاد فایل‌ها دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد.

**بازگشت:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما نیاز به اجازه ایجاد فایل‌ها دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف خواهند شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشه موقت سیستم استفاده می‌شود. فرایند میزبانی باید دسترسی ایجاد فایل و پوشه در آنجا را داشته باشد.

**بازگشت:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد می‌شوند. به‌طور پیش‌فرض از پوشه موقت سیستم استفاده می‌شود. فرایند میزبانی باید دسترسی ایجاد فایل و پوشه در آنجا را داشته باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

حداکثر اندازه کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ فقط زمانی که این محدودیت رسیده باشد، مکانیسم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را حداکثر می‌کند اما می‌تواند منجر به مصرف بالای حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید.

--------------------

این ویژگی نادیده گرفته می‌شود اگر \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) روی false تنظیم شده باشد، زیرا در آن حالت حافظه تنها مکان ذخیره‌سازی موجود است و محدود کردن استفاده از BLOBهای در-حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض ۶۲۹٬۱۴۵٬۶۰۰ بایت (۶۰۰ مگابایت) است.

--------------------

شما می‌توانید این ویژگی را روی صفر تنظیم کنید، اما مقدار حداقل کوچکی از حافظه هنوز محفوظ خواهد ماند.

**بازگشت:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

حداکثر اندازه کل (به بایت) که تمام BLOBها می‌توانند در حافظه اشغال کنند را تعریف می‌کند. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ فقط زمانی که این محدودیت رسیده باشد، مکانیسم‌های جایگزین (مانند فایل‌های موقت) به کار گرفته می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را حداکثر می‌کند اما می‌تواند منجر به مصرف بالای حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید.

--------------------

این ویژگی نادیده گرفته می‌شود اگر \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) روی false تنظیم شده باشد، زیرا در آن حالت حافظه تنها مکان ذخیره‌سازی موجود است و محدود کردن استفاده از BLOBهای در-حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض ۶۲۹٬۱۴۵٬۶۰۰ بایت (۶۰۰ مگابایت) است.

--------------------

شما می‌توانید این ویژگی را روی صفر تنظیم کنید، اما مقدار حداقل کوچکی از حافظه هنوز محفوظ خواهد ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |