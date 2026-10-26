---
title: PresentationInfo
second_title: مرجع API Aspose.Slides برای جاوا
description: اطلاعات دربارهٔ فایل ارائه
type: docs
url: /fa/com.aspose.slides/presentationinfo/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

اطلاعات درباره فایل ارائه
## متدها

| متد | توضیح |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | اگر ارائه باند شده رمزنگاری شده باشد True بر می‌گرداند، در غیر این صورت False. |
| [isPasswordProtected()](#isPasswordProtected--) | مقداری که نشان می‌دهد آیا ارائه باند شده با گذرواژه‌ای برای باز کردن محافظت شده است یا نه را بر می‌گرداند. |
| [isWriteProtected()](#isWriteProtected--) | مقدار نشان‌دهنده این که آیا ارائه باند شده محافظت نوشتنی دارد یا خیر را بر می‌گرداند. |
| [getLoadFormat()](#getLoadFormat--) | قالب ارائه باند شده را بر می‌گرداند. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | بررسی می‌کند آیا گذرواژه برای ارائه‌ای که با گذرواژه باز محافظت شده صحیح است یا نه. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | بررسی می‌کند آیا گذرواژه برای اصلاح یک ارائه محافظت نوشتنی صحیح است یا نه. |
| [readDocumentProperties()](#readDocumentProperties--) | ویژگی‌های سند ارائه باند شده را بر می‌گرداند. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | ویژگی‌های ارائه باند شده را به‌روزرسانی می‌کند. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | ارائه باند شده را به‌صورت جریان می‌نویسد. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | ارائه باند شده را به‌صورت فایل می‌نویسد. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


اگر ارائه باند شده رمزنگاری شده باشد True بر می‌گرداند، در غیر این صورت False. فقط-خواندنی boolean.

**بازگشت:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


مقداری که نشان می‌دهد آیا ارائه باند شده با گذرواژه‌ای برای باز کردن محافظت شده است یا نه را بر می‌گرداند.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**بازگشت:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```


مقداری که نشان می‌دهد آیا ارائه باند شده محافظت نوشتنی دارد یا نه را بر می‌گرداند.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

اگر ارائه با گذرواژه‌ای برای باز کردن محافظت شده باشد، مقدار ویژگی برابر NotDefined است.

**بازگشت:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


قالب ارائه باند شده را بر می‌گرداند. فقط-خواندنی [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```


بررسی می‌کند آیا گذرواژه برای ارائه‌ای که با گذرواژه باز محافظت شده صحیح است یا نه.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | گذرواژه‌ای که باید بررسی شود. |

--------------------

زمانی که گذرواژه null یا خالی باشد، این متد False بر می‌گرداند.

**بازگشت:**
boolean - True اگر ارائه با گذرواژه باز محافظت شده باشد و گذرواژه صحیح باشد و در غیر این صورت False.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


بررسی می‌کند آیا گذرواژه برای اصلاح یک ارائه محافظت نوشتنی صحیح است یا نه.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | گذرواژه‌ای که باید بررسی شود. |

--------------------

1. قبل از فراخوانی این متد باید ویژگی (\#isWriteProtected.isWriteProtected) را بررسی کنید. 2. زمانی که گذرواژه null یا خالی باشد، این متد False بر می‌گرداند.

**بازگشت:**
boolean - True اگر ارائه محافظت نوشتنی باشد و گذرواژه صحیح باشد. False در غیر این صورت.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```


ویژگی‌های سند ارائه باند شده را بر می‌گرداند.

**بازگشت:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```


ویژگی‌های ارائه باند شده را به‌روزرسانی می‌کند.

--------------------

> ```
> این نمونه نشان می‌دهد چگونه متد #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) را فراخوانی کنید تا
>  ویژگی‌های سند را که توسط فراخوانی متد #readDocumentProperties.readDocumentProperties برگردانده شده است، به‌روز کنید.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```


ارائه باند شده را به‌صورت جریان می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان باید قابلیت جستجو و نوشتن داشته باشد. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```


ارائه باند شده را به‌صورت فایل می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ارائه. |