---
title: ProtectionManager
second_title: مرجع API Aspose.Slides برای جاوا
description: مدیریت حفاظت با رمز عبور ارائه.
type: docs
url: /fa/com.aspose.slides/protectionmanager/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

مدیریت حفاظت با رمز عبور ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | این خصوصیت زمانی معنا دارد که ارائه دارای رمز عبور باشد. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | این خصوصیت زمانی معنا دارد که ارائه دارای رمز عبور باشد. |
| [isEncrypted()](#isEncrypted--) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا این نمونه رمزگذاری شده است یا خیر. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | این خصوصیت زمانی معنا دارد که فایل ارائه دارای رمز عبور باشد و ویژگی‌های سند این فایل عمومی باشند. |
| [isWriteProtected()](#isWriteProtected--) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است یا خیر. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | ارائه را با رمز عبور مشخص شده رمزگذاری می‌کند. |
| [removeEncryption()](#removeEncryption--) | رمزگذاری را حذف می‌کند. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | محافظت نوشتن برای این ارائه را با رمز عبور مشخص شده تنظیم می‌کند. |
| [removeWriteProtection()](#removeWriteProtection--) | محافظت نوشتن برای این ارائه را حذف می‌کند. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | تعیین می‌کند آیا یک ارائه از رمز عبور برای تغییر محافظت شده است یا خیر. |
| [getEncryptionPassword()](#getEncryptionPassword--) | رمز عبوری را برمی‌گرداند که برای رمزگذاری ارائه استفاده می‌شود. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | توصیه فقط-خواندنی را برمی‌گرداند یا تنظیم می‌کند. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | توصیه فقط-خواندنی را برمی‌گرداند یا تنظیم می‌کند. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

این خصوصیت زمانی معنا دارد که ارائه دارای رمز عبور باشد. اگر true باشد، ویژگی‌های سند در فایل ارائه رمزگذاری می‌شوند. اگر false باشد، ویژگی‌های سند عمومی هستند در حالی که ارائه رمزگذاری شده است. بولی خواندن/نوشتن.

**بازگشت:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

این خصوصیت زمانی معنا دارد که ارائه دارای رمز عبور باشد. اگر true باشد، ویژگی‌های سند در فایل ارائه رمزگذاری می‌شوند. اگر false باشد، ویژگی‌های سند عمومی هستند در حالی که ارائه رمزگذاری شده است. بولی خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

یک مقدار را برمی‌گرداند که نشان می‌دهد آیا این نمونه رمزگذاری شده است یا خیر. بولی فقط-خواندنی.

مقدار: true اگر ارائه از فایل رمزگذاری‌شده بارگذاری شده باشد یا متد \#encrypt(String).encrypt(String) فراخوانی شده باشد؛ در غیر این صورت false.

**بازگشت:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

این خصوصیت زمانی معنا دارد که فایل ارائه دارای رمز عبور باشد و ویژگی‌های سند این فایل عمومی باشند. مقدار true به این معناست که تنها ویژگی‌های سند بدون استفاده از رمز عبور از یک فایل ارائه رمزگذاری‌شده بارگذاری می‌شوند. مقدار false به این معناست که کل ارائه رمزگذاری‌شده با استفاده از رمز صحیح بارگذاری می‌شود و نه فقط ویژگی‌های سند. اگر ارائه رمزگذاری نشده باشد، مقدار خصوصیت همیشه false است. اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند، مقدار خصوصیت همیشه false است. اگر Presentation.EncryptDocumentProperties true باشد، مقدار IsOnlyDocumentPropertiesLoaded همیشه false است. بولی فقط-خواندنی.

**بازگشت:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

یک مقدار را برمی‌گرداند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است یا خیر. بولی فقط-خواندنی.

**بازگشت:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

ارائه را با رمز عبور مشخص شده رمزگذاری می‌کند.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| encryptionPassword | java.lang.String | رمز عبور. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

رمزگذاری را حذف می‌کند.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

محافظت نوشتن برای این ارائه را با رمز عبور مشخص شده تنظیم می‌کند.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

محافظت نوشتن برای این ارائه را حذف می‌کند.

--------------------

> ```
> This sample code shows you how to remove the write protection from a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

تعیین می‌کند آیا یک ارائه از رمز عبور برای تغییر محافظت شده است یا خیر.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور برای بررسی.

1. شما باید خصوصیت (\#isWriteProtected.isWriteProtected) را قبل از فراخوانی این متد بررسی کنید. 2. وقتی رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**
boolean - True اگر رمز عبور معتبر باشد؛ در غیر این صورت false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

رمز عبوری را برمی‌گرداند که برای رمزگذاری ارائه استفاده می‌شود. رشته فقط-خواندنی.

**بازگشت:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

توصیه فقط-خواندنی را برمی‌گرداند یا تنظیم می‌کند. بولی خواندن/نوشتن.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

توصیه فقط-خواندنی را برمی‌گرداند یا تنظیم می‌کند. بولی خواندن/نوشتن.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |