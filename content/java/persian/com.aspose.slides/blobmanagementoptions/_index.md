---
title: BlobManagementOptions
second_title: Aspose.Slides برای Java مرجع API
description: گزینه‌هایی که می‌توانند برای مدیریت قوانین پردازش BLOB و سایر تنظیمات BLOB استفاده شوند.
type: docs
url: /fa/com.aspose.slides/blobmanagementoptions/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

نمایش گزینه‌هایی که می‌توانند برای مدیریت قوانین پردازش BLOB و سایر تنظیمات BLOB استفاده شوند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | گزینه‌های پیش‌فرض مدیریت Blob جدید ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند صاحب منبع - فایل یا جریان - در طول عمر نمونه باشد. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند صاحب منبع - فایل یا جریان - در طول عمر نمونه باشد. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما به اجازه ایجاد فایل‌ها نیاز دارد. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما به اجازه ایجاد فایل‌ها نیاز دارد. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد خواهند شد. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد خواهند شد. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | حداکثر اندازه کل (به بایت) که تمام BLOBها ممکن است در حافظه اشغال کنند، تعریف می‌شود. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | حداکثر اندازه کل (به بایت) که تمام BLOBها ممکن است در حافظه اشغال کنند، تعریف می‌شود. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

گزینه‌های پیش‌فرض مدیریت Blob جدید ایجاد می‌کند.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند صاحب منبع - فایل یا جریان - در طول عمر نمونه باشد. اگر نمونه صاحب باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) را در طول عمر نمونه Presentation نمی‌توان تغییر داد.

**بازگشت:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند صاحب منبع - فایل یا جریان - در طول عمر نمونه باشد. اگر نمونه صاحب باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) را در طول عمر نمونه Presentation نمی‌توان تغییر داد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما به اجازه ایجاد فایل‌ها نیاز دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف می‌شوند.

**بازگشت:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

این ویژگی تعیین می‌کند که آیا می‌توان فایل‌های موقت را هنگام کار با BLOBها ایجاد کرد، که به‌طرز چشمگیری مصرف حافظه را کاهش می‌دهد اما به اجازه ایجاد فایل‌ها نیاز دارد.

--------------------

تمام فایل‌ها پس از اتمام کار با ارائه حذف می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد خواهند شد. به‌طور پیش‌فرض از پوشه موقت سیستم استفاده می‌شود. فرآیند میزبانی باید اجازه ایجاد فایل و پوشه در آنجا را داشته باشد.

**بازگشت:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

مسیر ریشه‌ای که فایل‌های موقت در آن ایجاد خواهند شد. به‌طور پیش‌فرض از پوشه موقت سیستم استفاده می‌شود. فرآیند میزبانی باید اجازه ایجاد فایل و پوشه در آنجا را داشته باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

حداکثر اندازه کل (به بایت) که تمام BLOBها ممکن است در حافظه اشغال کنند، تعریف می‌شود. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ فقط وقتی این محدودیت رسید، مکانیزم‌های جایگزین (مانند فایل‌های موقت) استفاده می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را بیشینه می‌کند اما ممکن است منجر به استفاده زیاد از حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید.

--------------------

این ویژگی در صورتی که \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) برابر false تنظیم شود نادیده گرفته می‌شود، زیرا در این حالت حافظه تنها مکان ذخیره‌سازی قابل دسترس است و محدود کردن استفاده از BLOB در حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض 629,145,600 بایت (600 مگابایت) است.

--------------------

می‌توانید این ویژگی را روی صفر تنظیم کنید، اما مقدار حداقل کمی از حافظه همچنان رزرو خواهد شد.

**بازگشت:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

حداکثر اندازه کل (به بایت) که تمام BLOBها ممکن است در حافظه اشغال کنند، تعریف می‌شود. به‌طور پیش‌فرض، تمام BLOBها در حافظه بارگذاری می‌شوند؛ فقط وقتی این محدودیت رسید، مکانیزم‌های جایگزین (مانند فایل‌های موقت) استفاده می‌شوند. نگه داشتن BLOBها در حافظه عملکرد را بیشینه می‌کند اما ممکن است منجر به استفاده زیاد از حافظه شود. از این ویژگی برای تطبیق رفتار با محیط یا نیازهای خود استفاده کنید.

--------------------

این ویژگی در صورتی که \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) برابر false تنظیم شود نادیده گرفته می‌شود، زیرا در این حالت حافظه تنها مکان ذخیره‌سازی قابل دسترس است و محدود کردن استفاده از BLOB در حافظه تأثیری ندارد.

--------------------

مقدار پیش‌فرض 629,145,600 بایت (600 مگابایت) است.

--------------------

می‌توانید این ویژگی را روی صفر تنظیم کنید، اما مقدار حداقل کمی از حافظه همچنان رزرو خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |