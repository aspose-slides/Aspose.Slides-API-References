---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation password protection management.
type: docs
url: /fa/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

مدیریت حفاظت رمز عبور ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | این ویژگی منطقی است، اگر ارائه با رمز عبور محافظت شده باشد. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | این ویژگی منطقی است، اگر ارائه با رمز عبور محافظت شده باشد. |
| [isEncrypted()](#isEncrypted--) | یک مقدار دریافت می‌کند که نشان می‌دهد آیا این نمونه رمزگذاری شده است. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | این ویژگی منطقی است، اگر فایل ارائه با رمز عبور محافظت شده باشد و ویژگی‌های سند این فایل عمومی باشند. |
| [isWriteProtected()](#isWriteProtected--) | یک مقدار دریافت می‌کند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است. |
| [getEncryptionPassword()](#getEncryptionPassword--) | رمز عبور رمزنگاری را برمی‌گرداند. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | توصیه فقط-خواندنی را دریافت یا تنظیم می‌کند. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | توصیه فقط-خواندنی را دریافت یا تنظیم می‌کند. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | ارائه را با رمز عبور مشخص شده رمزنگاری می‌کند. |
| [removeEncryption()](#removeEncryption--) | رمزنگاری را حذف می‌کند. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | حفاظت نوشتن برای این ارائه را با رمز عبور مشخص شده تنظیم می‌کند. |
| [removeWriteProtection()](#removeWriteProtection--) | حفاظت نوشتن برای این ارائه را حذف می‌کند. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | تعیین می‌کند که آیا ارائه برای ویرایش با رمز عبور محافظت شده است یا خیر. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

این ویژگی منطقی است، اگر ارائه با رمز عبور محافظت شده باشد. اگر true باشد ویژگی‌های سند در فایل ارائه رمزگذاری می‌شوند. اگر false باشد ویژگی‌های سند عمومی هستند در حالی که ارائه رمزگذاری شده است. بولی خواند/نوشتن.

**باز می‌گرداند:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

این ویژگی منطقی است، اگر ارائه با رمز عبور محافظت شده باشد. اگر true باشد ویژگی‌های سند در فایل ارائه رمزگذاری می‌شوند. اگر false باشد ویژگی‌های سند عمومی هستند در حالی که ارائه رمزگذاری شده است. بولی خواند/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

یک مقدار دریافت می‌کند که نشان می‌دهد آیا این نمونه رمزگذاری شده است. بولی فقط-خواندنی.

مقدار: true اگر ارائه از فایل رمزگذاری شده بارگذاری شده باشد یا متد \#encrypt(String).encrypt(String) فراخوانی شده باشد؛ در غیر این صورت، false.

**باز می‌گرداند:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

این ویژگی منطقی است، اگر فایل ارائه با رمز عبور محافظت شده باشد و ویژگی‌های سند این فایل عمومی باشند. مقدار true به این معنی است که فقط ویژگی‌های سند بدون استفاده از رمز عبور از یک فایل ارائه رمزگذاری شده بارگذاری می‌شوند. مقدار false به این معنی است که کل ارائه رمزگذاری شده با استفاده از رمز صحیح بارگذاری می‌شود و نه تنها ویژگی‌های سند. اگر ارائه رمزگذاری نشده باشد مقدار ویژگی همیشه false است. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند مقدار ویژگی همیشه false است. اگر PresentationEx.EncryptDocumentProperties برابر true باشد مقدار IsOnlyDocumentPropertiesLoaded همیشه false است. بولی فقط-خواندنی.

**باز می‌گرداند:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

یک مقدار دریافت می‌کند که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است. بولی فقط-خواندنی.

**باز می‌گرداند:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

رمز عبور رمزنگاری را برمی‌گرداند. رشته فقط-خواندنی.

**باز می‌گرداند:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

توصیه فقط-خواندنی را دریافت یا تنظیم می‌کند. بولی خواند/نوشتن.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**باز می‌گرداند:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

توصیه فقط-خواندنی را دریافت یا تنظیم می‌کند. بولی خواند/نوشتن.

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

ارائه را با رمز عبور مشخص شده رمزنگاری می‌کند.

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

حفاظت نوشتن برای این ارائه را با رمز عبور مشخص شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

حفاظت نوشتن برای این ارائه را حذف می‌کند.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

تعیین می‌کند که آیا ارائه برای ویرایش با رمز عبور محافظت شده است یا خیر.

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

1. باید قبل از فراخوانی این متد، ویژگی (\#isWriteProtected.isWriteProtected) را بررسی کنید. 2. زمانی که رمز عبور خالی یا null باشد، این متد false برمی‌گرداند. |

**باز می‌گرداند:**
boolean - True if the password is valid; otherwise, false.