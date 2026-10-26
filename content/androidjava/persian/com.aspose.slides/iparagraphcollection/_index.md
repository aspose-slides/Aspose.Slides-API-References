---
title: IParagraphCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک مجموعه از پاراگراف‌ها.
type: docs
url: /fa/com.aspose.slides/iparagraphcollection/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

نمایش یک مجموعه از پاراگراف‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در شاخص مشخص‌شده دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | یک Paragraph را به انتهای مجموعه اضافه می‌کند. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | محتویات ParagraphCollection را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | یک Paragraph را در شاخص مشخص‌شده به مجموعه وارد می‌کند. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | محتویات ParagraphCollection را در شاخص مشخص‌شده به مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در شاخص مشخص‌شده از مجموعه حذف می‌کند. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | نخستین رخداد یک پاراگراف مخصوص را حذف می‌کند. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | متن را از رشته HTML مشخص به مجموعه اضافه می‌کند. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | متن را از رشته HTML مشخص به مجموعه اضافه می‌کند. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | پاراگراف‌های مشخص‌شده را به HTML تبدیل می‌کند و به‌عنوان شیء String بازمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

عنصر را در شاخص مشخص‌شده دریافت می‌کند.

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

تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط-خواندنی int.

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
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که به انتهای مجموعه اضافه می‌شود. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

محتویات ParagraphCollection را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollectionی که به انتهای مجموعه اضافه می‌شود. |

**بازگشت:**
int - اندیسی که Paragraph در آن اضافه شده است یا -1 اگر چیزی برای اضافه کردن موجود نباشد.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

یک Paragraph را در شاخص مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که Paragraph باید در آن وارد شود. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که باید وارد شود. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

محتویات ParagraphCollection را در شاخص مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که پاراگراف‌ها باید در آن وارد شوند. |
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

عنصر را در شاخص مشخص‌شده از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا برای عنصر قابل حذف. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

نخستین رخداد یک پاراگراف مشخص را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | پاراگرافی که باید از مجموعه حذف شود. |

**بازگشت:**
boolean - true اگر مورد با موفقیت حذف شد؛ در غیر این صورت false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

متن را از رشته HTML مشخص به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

متن را از رشته HTML مشخص به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback Resolver که URIها را حل می‌کند و اشیاء ارجاع-داده‌شده را بازیابی می‌نماید. |
| uri | java.lang.String | URI برای افزودن سند HTML. برای حل لینک‌های نسبی استفاده می‌شود.

--------------------

مشخص کردن resolver ممکن است آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

پاراگراف‌های مشخص‌شده را به HTML تبدیل می‌کند و به‌عنوان شیء String بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstParagraphIndex | int | شاخص اولین پاراگراف int |
| paragraphsCount | int | تعداد پاراگراف‌ها int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | گزینه‌های تبدیل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**بازگشت:**
java.lang.String - HTML تولید شده.