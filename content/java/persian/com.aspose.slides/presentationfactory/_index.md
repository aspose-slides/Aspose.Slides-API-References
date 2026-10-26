---
title: PresentationFactory
second_title: مرجع API Aspose.Slides برای جاوا
description: به شما امکان می‌دهد ارائه را از طریق رابط COM ایجاد کنید
type: docs
url: /fa/com.aspose.slides/presentationfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

به شما امکان می‌دهد ارائه را از طریق رابط COM ایجاد کنید

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## سازندگان

| Constructor | Description |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## متدها

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation factory static instance. |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Creates new PresentationInfo object from stream and binds presentation to it. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Presentation factory static instance. Read-only [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Returns:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

ارائه جدیدی ایجاد می‌کند.

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ جدید
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

ارائه جدیدی با گزینه‌های بارگذاری اضافه ایجاد می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ جدید
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

یک شیء PresentationInfo جدید از فایل ایجاد می‌کند و ارائه را به آن پیوند می‌دهد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | فایل ارائه. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - اطلاعات ارائه که به ارائه پیوند خورده است.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

یک شیء PresentationInfo جدید از جریان ایجاد می‌کند و ارائه را به آن پیوند می‌دهد. اطلاعات مربوط به ارائه در جریان مشخص دیده می‌شود.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ارائه. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - اطلاعات ارائه که به ارائه پیوند خورده است.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

یک ارائه موجود را از آرایه می‌خواند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | آرایه برای خواندن |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ خوانده شده
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافه می‌خواند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | آرایه برای خواندن |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ خوانده شده
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

یک ارائه موجود را از جریان می‌خواند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی برای خواندن |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ خوانده شده
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافه می‌خواند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی برای خواندن |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ خوانده شده
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

یک ارائه موجود را از فایل می‌خواند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | نام فایل |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ خوانده شده
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPPresentation readPresentation(String file, ILoadOptions options)
```

یک ارائه موجود را از فایل با گزینه‌های بارگذاری اضافه می‌خواند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | نام فایل |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ خوانده شده
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

متن خام اسلایدها را دریافت می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | فایل ورودی |
| mode | int | حالت استخراج |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که آرایهٔ SlideText حاوی متن خام اسلایدها را دارد
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

متن خام اسلایدها را دریافت می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی |
| mode | int | حالت استخراج |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که آرایهٔ SlideText حاوی متن خام اسلایدها را دارد
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

متن خام اسلایدها را دریافت می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی |
| mode | int | حالت استخراج |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که آرایهٔ SlideText حاوی متن خام اسلایدها را دارد