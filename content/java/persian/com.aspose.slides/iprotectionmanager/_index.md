---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: مدیریت حفاظت با رمز عبور ارائه.
type: docs
url: /fa/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

مدیریت حفاظت با رمز عبور ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | این ویژگی معنادار است، اگر ارائه با رمز عبور محافظت شده باشد. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | این ویژگی معنادار است، اگر ارائه با رمز عبور محافظت شده باشد. |
| [isEncrypted()](#isEncrypted--) | یک مقدار را برمی‌گرداند که نشان می‌دهد این نمونه رمزنگاری شده است. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | این ویژگی معنادار است، اگر فایل ارائه با رمز عبور محافظت شده باشد و خواص سند این فایل عمومی باشد. |
| [isWriteProtected()](#isWriteProtected--) | یک مقدار را برمی‌گرداند که نشان می‌دهد این ارائه محافظت نوشتاری دارد. |
| [getEncryptionPassword()](#getEncryptionPassword--) | رمز عبور رمزنگاری را برمی‌گرداند. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | ارائه را با رمز عبور مشخص رمزگذاری می‌کند. |
| [removeEncryption()](#removeEncryption--) | رمزنگاری را حذف می‌کند. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | محافظت نوشتاری برای این ارائه را با رمز عبور مشخص تنظیم می‌کند. |
| [removeWriteProtection()](#removeWriteProtection--) | محافظت نوشتاری برای این ارائه را حذف می‌کند. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | تعیین می‌کند که آیا یک ارائه برای تغییر با رمز عبور محافظت شده است یا خیر. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


این ویژگی معنادار است، اگر ارائه با رمز عبور محافظت شده باشد. اگر true باشد، خواص سند در فایل ارائه رمزگذاری می‌شود. اگر false باشد، خواص سند عمومی است در حالی که ارائه رمزگذاری شده است. Boolean قابل‌خواندن/نوشتن.

**بازگشت:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


این ویژگی معنادار است، اگر ارائه با رمز عبور محافظت شده باشد. اگر true باشد، خواص سند در فایل ارائه رمزگذاری می‌شود. اگر false باشد، خواص سند عمومی است در حالی که ارائه رمزگذاری شده است. Boolean قابل‌خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


یک مقدار را برمی‌گرداند که نشان می‌دهد این نمونه رمزنگاری شده است. Boolean فقط-خواندنی.

مقدار: true اگر ارائه از فایل رمزگذاری شده بارگذاری شده باشد یا متد \#encrypt(String).encrypt(String) فراخوانی شده باشد؛ در غیر این صورت، false.

**بازگشت:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


این ویژگی معنادار است، اگر فایل ارائه با رمز عبور محافظت شده باشد و خواص سند این فایل عمومی باشد. مقدار true به این معنی است که فقط خواص سند از یک فایل ارائه رمزگذاری شده بدون استفاده از رمز عبور بارگذاری می‌شود. مقدار false به این معنی است که کل ارائه رمزگذاری شده با استفاده از رمز صحیح بارگذاری می‌شود، نه فقط خواص سند. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه false است. اگر خواص سند یک فایل رمزگذاری شده عمومی نباشد، مقدار ویژگی همیشه false است. اگر PresentationEx.EncryptDocumentProperties true باشد، مقدار IsOnlyDocumentPropertiesLoaded همیشه false است. Boolean فقط-خواندنی.

**بازگشت:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


یک مقدار را برمی‌گرداند که نشان می‌دهد این ارائه محافظت نوشتاری دارد. Boolean فقط-خواندنی.

**بازگشت:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


رمز عبور رمزنگاری را برمی‌گرداند. رشته فقط-خواندنی.

**بازگشت:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. Boolean قابل‌خواندن/نوشتن.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**بازگشت:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


توصیهٔ فقط-خواندنی را دریافت یا تنظیم می‌کند. Boolean قابل‌خواندن/نوشتن.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


ارائه را با رمز عبور مشخص رمزگذاری می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| encryptionPassword | java.lang.String | رمز عبور. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```


رمزنگاری را حذف می‌کند.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```


محافظت نوشتاری برای این ارائه را با رمز عبور مشخص تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


محافظت نوشتاری برای این ارائه را حذف می‌کند.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


تعیین می‌کند که آیا یک ارائه برای تغییر با رمز عبور محافظت شده است یا خیر.

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
| password | java.lang.String | رمز عبور برای بررسی. |

1. پیش از فراخوانی این متد باید ویژگی (\#isWriteProtected.isWriteProtected) را بررسی کنید. 2. وقتی رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**
boolean - True اگر رمز عبور معتبر باشد؛ در غیر این صورت، false.