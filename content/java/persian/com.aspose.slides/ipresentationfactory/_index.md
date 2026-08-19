---
title: IPresentationFactory
second_title: Aspose.Slides برای جاوا مرجع API
description: به شما امکان ایجاد ارائه از طریق رابط COM را می‌دهد
type: docs
url: /fa/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

به شما امکان ایجاد ارائه از طریق رابط COM را می‌دهد
## متدها

| متد | توضیح |
| --- | --- |
| [createPresentation()](#createPresentation--) | یک ارائه جدید ایجاد می‌کند. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | یک ارائه جدید با گزینه‌های بارگذاری اضافی ایجاد می‌کند |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | اطلاعات درباره ارائه در فایل مشخص‌شده را دریافت می‌کند. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | اطلاعات درباره ارائه در جریان مشخص‌شده را دریافت می‌کند. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


یک ارائه جدید ایجاد می‌کند.

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه جدید
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```


یک ارائه جدید با گزینه‌های بارگذاری اضافی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه جدید
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```


اطلاعات درباره ارائه در فایل مشخص‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ارائه. |

**بازگرداندن:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - اطلاعات ارائه
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


اطلاعات درباره ارائه در جریان مشخص‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ارائه. |

**بازگرداندن:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - اطلاعات ارائه.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


یک ارائه موجود را از آرایه می‌خواند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | آرایه برای خواندن |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافی می‌خواند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | آرایه برای خواندن |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


یک ارائه موجود را از جریان می‌خواند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی برای خواندن |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی برای خواندن |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


یک ارائه موجود را از فایل می‌خواند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | نام فایل |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | نام فایل |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation) - ارائه خوانده‌شده
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


متن خام اسلایدها را بازیابی می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ورودی |
| mode | int | حالت استخراج |

**بازگرداندن:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که شامل آرایه SlideText است و متن خام اسلایدها را نشان می‌دهد
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


متن خام اسلایدها را بازیابی می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی |
| mode | int | حالت استخراج |

**بازگرداندن:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که شامل آرایه SlideText است و متن خام اسلایدها را نشان می‌دهد
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


متن خام اسلایدها را بازیابی می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی |
| mode | int | حالت استخراج |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | گزینه‌های بارگذاری |

**بازگرداندن:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که شامل آرایه SlideText است و متن خام اسلایدها را نشان می‌دهد