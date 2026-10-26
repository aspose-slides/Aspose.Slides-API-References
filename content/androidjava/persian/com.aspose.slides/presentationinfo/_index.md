---
title: PresentationInfo
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: اطلاعات درباره فایل ارائه
type: docs
url: /fa/com.aspose.slides/presentationinfo/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

اطلاعات درباره فایل ارائه
## متدها

| متد | توضیح |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | True را برمی‌گرداند اگر ارائهٔ بایند شده رمزگذاری شده باشد، در غیر این صورت False. |
| [isPasswordProtected()](#isPasswordProtected--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده با رمز عبور برای باز کردن محافظت شده است یا خیر. |
| [isWriteProtected()](#isWriteProtected--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده از نوشتن محافظت شده است یا خیر. |
| [getLoadFormat()](#getLoadFormat--) | فرمت ارائهٔ بایند شده را برمی‌گرداند. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | بررسی می‌کند که آیا رمز عبور برای ارائه‌ای که با رمز عبور باز کردن محافظت شده است درست است یا نه. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | بررسی می‌کند که آیا رمز عبور برای تغییر برای یک ارائهٔ محافظت‌شده از نوشتن درست است یا نه. |
| [readDocumentProperties()](#readDocumentProperties--) | خصوصیات سند ارائهٔ بایند شده را برمی‌گرداند. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | خصوصیات ارائهٔ بایند شده را به‌روزرسانی می‌کند. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | ارائهٔ بایند شده را به جریان می‌نویسد. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | ارائهٔ بایند شده را به فایل می‌نویسد. |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

True را برمی‌گرداند اگر ارائهٔ بایند شده رمزگذاری شده باشد، در غیر این صورت False. فقط-خواندنی boolean.

**بازگشت:**
boolean

### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده با رمز عبور برای باز کردن محافظت شده است یا خیر.

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

مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ بایند شده از نوشتن محافظت شده است یا خیر.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

اگر ارائه با رمز عبور برای باز کردن محافظت شود، مقدار ویژگی برابر با NotDefined می‌شود.

**بازگشت:**
byte

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

فرمت ارائهٔ بایند شده را برمی‌گرداند. فقط-خواندنی [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**
int

### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

بررسی می‌کند که آیا رمز عبور برای ارائه‌ای که با رمز عبور باز کردن محافظت شده است درست است یا نه.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| password | java.lang.String | رمز عبور برای بررسی. |

--------------------

زمانی که رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**
boolean - True اگر ارائه با رمز عبور باز کردن محافظت شده باشد و رمز عبور صحیح باشد، در غیر این صورت false.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

بررسی می‌کند که آیا رمز عبور برای تغییر برای یک ارائهٔ محافظت‌شده از نوشتن درست است یا نه.

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
| password | java.lang.String | رمز عبور برای بررسی. |

--------------------

1. قبل از فراخوانی این متد باید ویژگی (\#isWriteProtected.isWriteProtected) را بررسی کنید. 2. وقتی رمز عبور null یا خالی باشد، این متد false برمی‌گرداند. |

**بازگشت:**
boolean - True اگر ارائه از نوشتن محافظت شده باشد و رمز عبور صحیح باشد. False در غیر این صورت.

### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

خصوصیات سند ارائهٔ بایند شده را برمی‌گرداند.

**بازگشت:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

خصوصیات ارائهٔ بایند شده را به‌روزرسانی می‌کند.

--------------------

> ```
> این نمونه نشان می‌دهد چگونه متد #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) را برای
>  به‌روزرسانی خصوصیات سندی که توسط فراخوانی متد #readDocumentProperties.readDocumentProperties برگردانده شده است.
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

ارائهٔ بایند شده را به جریان می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان باید قابلیت جستجو و نوشتن داشته باشد. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

ارائهٔ بایند شده را به فایل می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ارائه. |