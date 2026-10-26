---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
url: /fa/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

اطلاعات دربارهٔ فایل ارائه
## متدها

| متد | توضیح |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | True برمی‌گرداند اگر ارائهٔ پیوست‌شده رمزنگاری شده باشد، در غیر این صورت False. |
| [isPasswordProtected()](#isPasswordProtected--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوست‌شده با رمز عبور برای باز کردن محافظت شده است یا خیر. |
| [isWriteProtected()](#isWriteProtected--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوست‌شده از نوشتن محافظت شده است یا خیر. |
| [getLoadFormat()](#getLoadFormat--) | قالب ارائهٔ پیوست‌شده را برمی‌گرداند. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | بررسی می‌کند آیا رمز عبور برای ارائه‌ای که با رمز عبور باز شدن محافظت شده است، صحیح است یا خیر. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | بررسی می‌کند آیا رمز عبور برای ویرایش برای ارائه‌ای که از نوشتن محافظت شده است، صحیح است یا خیر. |
| [readDocumentProperties()](#readDocumentProperties--) | ویژگی‌های سند ارائهٔ پیوست‌شده را برمی‌گرداند. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | ویژگی‌های ارائهٔ پیوست‌شده را به‌روز می‌کند. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | ارائهٔ پیوست‌شده را در جریان می‌نویسد. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | ارائهٔ پیوست‌شده را در فایل می‌نویسد. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

True برمی‌گرداند اگر ارائهٔ پیوست‌شده رمزنگاری شده باشد، در غیر این صورت False. فقط-خواندنی boolean.

**بازگشت:**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوست‌شده با رمز عبور برای باز کردن محافظت شده است یا خیر.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**بازگشت:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوست‌شده از نوشتن محافظت شده است یا خیر.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

اگر ارائه با رمز عبور برای باز کردن محافظت شده باشد، مقدار ویژگی برابر NotDefined است. به شمارش [NullableBool](../../com.aspose.slides/nullablebool) نگاه کنید.

**بازگشت:**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

قالب ارائهٔ پیوست‌شده را برمی‌گرداند. فقط-خواندنی [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

بررسی می‌کند آیا رمز عبور برای ارائه‌ای که با رمز عبور باز شدن محافظت شده است، صحیح است یا خیر.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور برای بررسی. |

--------------------

هنگامی که رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**  
boolean - True اگر ارائه با رمز عبور باز شدن محافظت شده باشد و رمز عبور صحیح باشد، و در غیر این صورت false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

بررسی می‌کند آیا رمز عبور برای ویرایش برای ارائه‌ای که از نوشتن محافظت شده است، صحیح است یا خیر.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور برای بررسی. |

--------------------

1. شما باید قبل از فراخوانی این متد، ویژگی (\#isWriteProtected.isWriteProtected) را بررسی کنید. 2. هنگامی که رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**  
boolean - True اگر ارائه از نوشتن محافظت شده باشد و رمز عبور صحیح باشد. False در غیر این صورت.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

ویژگی‌های سند ارائهٔ پیوست‌شده را برمی‌گرداند.

**بازگشت:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - ویژگی‌های سند [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

ویژگی‌های ارائهٔ پیوست‌شده را به‌روز می‌کند.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | ویژگی‌های سند [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

ارائهٔ پیوست‌شده را در جریان می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان باید قابل جستجو و قابل نوشتن باشد. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

ارائهٔ پیوست‌شده را در فایل می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ارائه. |