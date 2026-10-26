---  
title: IPresentationFactory  
second_title: Aspose.Slides for Android via Java API Reference  
description: Allows to create presentation via COM interface  
type: docs  
url: /fa/com.aspose.slides/ipresentationfactory/  
---```
public interface IPresentationFactory
```

اجازه می‌دهد تا ارائه را از طریق رابط COM ایجاد کنید.

## متدها

| متد | توضیح |
| --- | --- |
| [createPresentation()](#createPresentation--) | یک ارائه جدید ایجاد می‌کند. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | یک ارائه جدید با گزینه‌های بارگذاری اضافی ایجاد می‌کند. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | اطلاعات درباره ارائه در فایل مشخص‌شده را دریافت می‌کند. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | اطلاعات درباره ارائه در جریان مشخص‌شده را دریافت می‌کند. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | یک ارائه موجود را از آرایه می‌خواند |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافی می‌خواند |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | یک ارائه موجود را از جریان می‌خواند |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | یک ارائه موجود را از فایل می‌خواند |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | متن خام اسلایدها را بازیابی می‌کند |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | متن خام اسلایدها را بازیابی می‌کند |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | متن خام اسلایدها را بازیابی می‌کند |

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

یک ارائه موجود را از فایل با گزینه‌های بارگذاری اضافی می‌خواند

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
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که شامل آرایه SlideText است و متن خام اسلایدها را نمایندگی می‌کند

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
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که شامل آرایه SlideText است و متن خام اسلایدها را نمایندگی می‌کند

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
[IPresentationText](../../com.aspose.slides/ipresentationtext) - نمونه‌ای از PresentationText که شامل آرایه SlideText است و متن خام اسلایدها را نمایندگی می‌کند