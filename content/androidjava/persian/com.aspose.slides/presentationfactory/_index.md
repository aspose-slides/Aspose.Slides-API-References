---
title: PresentationFactory
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: اجازه می‌دهد تا ارائه‌ای را از طریق رابط COM ایجاد کنید
type: docs
url: /fa/com.aspose.slides/presentationfactory/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)  
```
public class PresentationFactory implements IPresentationFactory
```

اجازۀ ایجاد ارائه از طریق رابط COM

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
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getInstance()](#getInstance--) | نمونهٔ ایستاتیک کارخانهٔ ارائه. |
| [createPresentation()](#createPresentation--) | یک ارائه جدید ایجاد می‌کند. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | یک ارائه جدید با گزینه‌های بارگذاری اضافی ایجاد می‌کند. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | یک شیء PresentationInfo از فایل ایجاد می‌کند و ارائه را به آن متصل می‌نماید. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | یک شیء PresentationInfo از جریان ایجاد می‌کند و ارائه را به آن متصل می‌نماید. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | یک ارائه موجود را از آرایه می‌خواند |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافی می‌خواند |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | یک ارائه موجود را از جریان می‌خواند |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | یک ارائه موجود را از فایل می‌خواند |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | متن خام اسلایدها را بازیابی می‌کند |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | متن خام اسلایدها را بازیابی می‌کند |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | متن خام اسلایدها را بازیابی می‌کند |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

نمونهٔ ایستاتیک کارخانهٔ ارائه. فقط-خواندنی [PresentationFactory](../../com.aspose.slides/presentationfactory).

**باز می‌گردد:**  
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

یک ارائه جدید ایجاد می‌کند.

**باز می‌گردد:**  
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ جدید
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

یک ارائه جدید با گزینه‌های بارگذاری اضافی ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائهٔ جدید
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

یک شیء PresentationInfo از فایل ایجاد می‌کند و ارائه را به آن متصل می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ارائه. |

**باز می‌گردد:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - اطلاعات ارائه متصل به ارائه.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

یک شیء PresentationInfo از جریان ایجاد می‌کند و ارائه را به آن متصل می‌نماید. اطلاعاتی دربارهٔ ارائه در جریان مشخص‌شده دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ارائه. |

**باز می‌گردد:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - اطلاعات ارائه متصل به ارائه.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

یک ارائه موجود را از آرایه می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | آرایه برای خواندن |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافی می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | آرایه برای خواندن |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

یک ارائه موجود را از جریان می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی برای خواندن |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی برای خواندن |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

یک ارائه موجود را از فایل می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | نام فایل |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

یک ارائه موجود را از فایل با گزینه‌های بارگذاری اضافی می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | نام فایل |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**باز می‌گردد:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

متن خام اسلایدها را بازیابی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ورودی |
| mode | int | حالت استخراج |

**باز می‌گردد:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونهٔ PresentationText که شامل آرایهٔ SlideText است و متن خام اسلایدها را نشان می‌دهد
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

متن خام اسلایدها را بازیابی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی |
| mode | int | حالت استخراج |

**باز می‌گردد:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونهٔ PresentationText که شامل آرایهٔ SlideText است و متن خام اسلایدها را نشان می‌دهد
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

متن خام اسلایدها را بازیابی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی |
| mode | int | حالت استخراج |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**باز می‌گردد:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونهٔ PresentationText که شامل آرایهٔ SlideText است و متن خام اسلایدها را نشان می‌دهد