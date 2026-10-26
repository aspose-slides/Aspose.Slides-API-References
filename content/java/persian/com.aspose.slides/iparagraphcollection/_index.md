---
title: IParagraphCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک مجموعه از پاراگراف‌ها.
type: docs
url: /fa/com.aspose.slides/iparagraphcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

نمایشگر مجموعه‌ای از پاراگراف‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر مورد نظر در ایندکس مشخص را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد واقعی عناصر موجود در مجموعه را دریافت می‌کند. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | یک Paragraph را به انتهای مجموعه اضافه می‌کند. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | محتوای ParagraphCollection را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | یک Paragraph را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | محتوای ParagraphCollection را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص را از مجموعه حذف می‌کند. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | اولین رخداد یک پاراگراف خاص را حذف می‌کند. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | متن را از رشته html مشخص شده به مجموعه اضافه می‌کند. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | متن را از رشته html مشخص شده به مجموعه اضافه می‌کند. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | پاراگراف‌های مشخص شده را به HTML تبدیل کرده و به‌صورت شیء String برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

عنصر مورد نظر در ایندکس مشخص را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IParagraph](../../com.aspose.slides/iparagraph)

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد واقعی عناصر موجود در مجموعه را دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

یک Paragraph را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که باید به انتهای مجموعه اضافه شود. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

محتوای ParagraphCollection را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollectionی که باید به انتهای مجموعه اضافه شود. |

**بازگشت:**
int - شاخصی که Paragraph در آن اضافه شده است یا -1 اگر چیزی برای اضافه کردن وجود نداشته باشد.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

یک Paragraph را در ایندکس مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنای که Paragraph باید در آن وارد شود. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که باید وارد شود. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

محتوای ParagraphCollection را در ایندکس مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنای که پاراگراف‌ها باید در آن وارد شوند. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | پاراگراف‌هایی که باید وارد شوند. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر موجود در ایندکس مشخص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنای عنصری که باید حذف شود. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

اولین رخداد یک پاراگراف خاص را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | پاراگرافی که باید از مجموعه حذف شود. |

**بازگشت:**
boolean - true اگر آیتم با موفقیت حذف شد؛ در غیر این صورت false.

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

متن را از رشته html مشخص شده به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

متن را از رشته html مشخص شده به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback Resolver که URIها را حل می‌کند و اشیای ارجاع‌شده را بازیابی می‌نماید. |
| uri | java.lang.String | URI برای افزودن سند HTML. برای حل لینک‌های نسبی استفاده می‌شود.

--------------------

مشخص کردن resolver می‌تواند به‌طور بالقوه آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

پاراگراف‌های مشخص شده را به HTML تبدیل کرده و به‌صورت شیء String برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstParagraphIndex | int | ایندکس اولین پاراگراف (int) |
| paragraphsCount | int | تعداد پاراگراف (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | گزینه‌های تبدیل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**بازگشت:**
java.lang.String - HTML تولید شده.