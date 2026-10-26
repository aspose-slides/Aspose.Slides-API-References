---
title: ParagraphCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از پاراگراف‌ها.
type: docs
url: /fa/com.aspose.slides/paragraphcollection/
---
**Inheritance:**  
ارث‌بری:  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
تمام رابط‌های پیاده‌سازی‌شده:  
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)  
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

نمایش‌دهنده یک مجموعه از پاراگراف‌ها.

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصری که واقعاً در مجموعه وجود دارند را دریافت می‌کند. |
| [isReadOnly()](#isReadOnly--) | مقداری را بر می‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | یک Paragraph را به انتهای مجموعه اضافه می‌کند. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | محتوای ParagraphCollection را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | اندیس یک مورد خاص در List را تعیین می‌کند. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | یک Paragraph را در اندیس مشخص‌شده به مجموعه وارد می‌کند. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | محتوای ParagraphCollection را در اندیس مشخص‌شده به مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | این‌که آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است را تعیین می‌کند. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک شاخص آرایه خاص. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد مجموعه پاراگراف‌ها را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد مجموعه پاراگراف‌ها را برمی‌گرداند. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | پاراگراف‌های مشخص‌شده را به HTML تبدیل می‌کند و به‌صورت شیء String برمی‌گرداند. |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصری که واقعاً در مجموعه وجود دارند را دریافت می‌کند. فقط‌خواندنی int.

**بازگشت:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را بر می‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. فقط‌خواندنی boolean.

**بازگشت:**  
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی باشد؛ در غیر این صورت false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

یک Paragraph را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که باید به انتهای مجموعه اضافه شود. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

محتوای ParagraphCollection را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollectionی که باید به انتهای مجموعه اضافه شود. |

**بازگشت:**  
int - اندیسی که Paragraph در آن اضافه شده یا -1 اگر چیزی برای اضافه کردن وجود نداشته باشد.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

اندیس یک مورد خاص در List را تعیین می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | شیء برای پیدا کردن در List. |

**بازگشت:**  
int - اندیس مورد اگر در لیست پیدا شود؛ در غیر این صورت -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

یک Paragraph را در اندیس مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که Paragraph باید در آن وارد شود. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که باید وارد شود. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

محتوای ParagraphCollection را در اندیس مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که پاراگراف‌ها باید در آن وارد شوند. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | پاراگراف‌هایی که باید وارد شوند. |

### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

این‌که آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است را تعیین می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | شیء برای پیدا کردن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**  
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) پیدا شود؛ در غیر این صورت false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک شاخص آرایه خاص.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | آرایه تک-بعدی که مقصد عناصر کپی‌شده از [IGenericCollection](../../com.aspose.slides/igenericcollection) است. آرایه باید شاخص صفر مبنا داشته باشد. |
| arrayIndex | int | اندیس صفر مبنا در آرایه که کپی از آن آغاز می‌شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا از عنصری که باید حذف شود. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | شیء برای حذف از [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**  
boolean - true اگر مورد با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شود؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - یک IGenericEnumerator که می‌توان از آن برای پیمایش مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - یک java.util.Iterator برای کل مجموعه.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد مجموعه پاراگراف‌ها را برمی‌گرداند. فقط‌خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد مجموعه پاراگراف‌ها را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback Resolver که URIها را حل می‌کند و اشیای ارجاع شده را دریافت می‌کند. |
| uri | java.lang.String | URI برای افزودن سند HTML. برای حل لینک‌های نسبی استفاده می‌شود. |

تعیین resolver می‌تواند به‌طور بالقوه یک آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

پاراگراف‌های مشخص‌شده را به HTML تبدیل می‌کند و به‌صورت شیء String برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstParagraphIndex | int | اندیس اولین پاراگراف (int) |
| paragraphsCount | int | تعداد پاراگراف (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | گزینه‌های تبدیل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**بازگشت:**  
java.lang.String - HTML تولید شده.