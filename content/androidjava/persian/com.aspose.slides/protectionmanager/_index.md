---
title: ProtectionManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مدیریت حفاظت با رمز عبور ارائه.
type: docs
url: /fa/com.aspose.slides/protectionmanager/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

مدیریت حفاظت با رمز عبور ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | این ویژگی معنای دارد، اگر ارائه با رمز عبور محافظت شود. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | این ویژگی معنای دارد، اگر ارائه با رمز عبور محافظت شود. |
| [isEncrypted()](#isEncrypted--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا این نمونه رمزنگاری شده است یا نه. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | این ویژگی معنای دارد، اگر فایل ارائه با رمز عبور محافظت شود و ویژگی‌های سند این فایل عمومی باشند. |
| [isWriteProtected()](#isWriteProtected--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است یا نه. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | ارائه را با رمز عبور مشخص شده رمزنگاری می‌کند. |
| [removeEncryption()](#removeEncryption--) | رمزنگاری را حذف می‌کند. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | حفاظت از نوشتن برای این ارائه را با رمز عبور مشخص شده تنظیم می‌کند. |
| [removeWriteProtection()](#removeWriteProtection--) | حفاظت از نوشتن برای این ارائه را حذف می‌کند. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | تعیین می‌کند که آیا یک ارائه برای ویرایش با رمز عبور محافظت می‌شود یا نه. |
| [getEncryptionPassword()](#getEncryptionPassword--) | رمز عبوری را برمی‌گرداند که برای رمزنگاری ارائه استفاده می‌شود. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

این ویژگی معنای دارد، اگر ارائه با رمز عبور محافظت شود. اگر true باشد، ویژگی‌های سند در فایل ارائه رمزنگاری می‌شوند. اگر false باشد، ویژگی‌های سند عمومی هستند در حالی که ارائه رمزنگاری شده است. بولی خواندنی/نوشتنی.

**بازگشت:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

این ویژگی معنای دارد، اگر ارائه با رمز عبور محافظت شود. اگر true باشد، ویژگی‌های سند در فایل ارائه رمزنگاری می‌شوند. اگر false باشد، ویژگی‌های سند عمومی هستند در حالی که ارائه رمزنگاری شده است. بولی خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا این نمونه رمزنگاری شده است یا نه. بولی فقط-خواندنی.

Value: true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**بازگشت:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

این ویژگی معنای دارد، اگر فایل ارائه با رمز عبور محافظت شده و ویژگی‌های سند این فایل عمومی باشند. مقدار true به این معنی است که فقط ویژگی‌های سند از یک فایل ارائه رمزنگاری‌شده بدون استفاده از رمز عبور بارگذاری می‌شوند. مقدار false به این معنی است که کل ارائه رمزنگاری‌شده با استفاده از رمز عبور صحیح بارگذاری می‌شود و نه تنها ویژگی‌های سند. اگر ارائه رمزنگاری نشده باشد، مقدار ویژگی همیشه false است. اگر ویژگی‌های سند یک فایل رمزنگاری‌شده عمومی نباشند، مقدار ویژگی همیشه false است. اگر Presentation.EncryptDocumentProperties true باشد، مقدار ویژگی IsOnlyDocumentPropertiesLoaded همیشه false است. بولی فقط-خواندنی.

**بازگشت:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است یا نه. بولی فقط-خواندنی.

**بازگشت:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

ارائه را با رمز عبور مشخص شده رمزنگاری می‌کند.

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

رمزنگاری را حذف می‌کند.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

حفاظت از نوشتن برای این ارائه را با رمز عبور مشخص شده تنظیم می‌کند.

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

حفاظت از نوشتن برای این ارائه را حذف می‌کند.

--------------------

> ```
> این نمونه کد نشان می‌دهد چگونه حفاظت نوشتن را از یک ارائهٔ PowerPoint حذف کنید.
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

تعیین می‌کند که آیا یک ارائه برای ویرایش با رمز عبور محافظت می‌شود یا نه.

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

--------------------
1. باید پیش از فراخوانی این متد، ویژگی (#isWriteProtected.isWriteProtected) را بررسی کنید. 2. وقتی رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**
boolean - True اگر رمز عبور معتبر باشد؛ در غیر این صورت، false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

رمز عبوری را برمی‌گرداند که برای رمزنگاری ارائه استفاده می‌شود. رشته فقط-خواندنی.

**بازگشت:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. بولی خواندنی/نوشتنی.

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

توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. بولی خواندنی/نوشتنی.

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