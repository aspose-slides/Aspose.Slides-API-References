---
title: ParagraphCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ یک مجموعه از پاراگراف‌ها.
type: docs
url: /fa/com.aspose.slides/paragraphcollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

نمایش‌دهندهٔ مجموعه‌ای از پاراگراف‌ها.
## متدها

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است یا نه. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص را برمی‌گرداند. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | یک Paragraph را به انتهای مجموعه اضافه می‌کند. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | محتوای ParagraphCollection را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | شاخص یک مورد خاص را در List تعیین می‌کند. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | یک Paragraph را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | محتوای ParagraphCollection را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | مشخص می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک ایندکس خاص آرایه. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص را از مجموعه حذف می‌کند. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator را برمی‌گرداند که در مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد مجموعه پاراگراف‌ها را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد مجموعه پاراگراف‌ها را برمی‌گرداند. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | متن را از رشتهٔ html مشخص به مجموعه اضافه می‌کند. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | متن را از رشتهٔ html مشخص به مجموعه اضافه می‌کند. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | پاراگراف‌های مشخص شده را به HTML تبدیل کرده و به‌صورت شیء String برمی‌گرداند. |
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. int فقط-خواندنی.

**بازمی‌گرداند:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است یا نه. boolean فقط-خواندنی.

**بازمی‌گرداند:**
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی باشد؛ در غیر این صورت false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

عنصر موجود در ایندکس مشخص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
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

**بازمی‌گرداند:**
int - شاخصی که Paragraph در آن اضافه شده یا -1 اگر چیزی برای اضافه کردن وجود نداشته باشد.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

شاخص یک مورد خاص را در List تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | شیء مورد جستجو در List. |

**بازمی‌گرداند:**
int - شاخص مورد اگر در لیست یافت شود؛ در غیر این صورت -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

یک Paragraph را در ایندکس مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنای که Paragraph باید در آن وارد شود. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraphی که باید وارد شود. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

محتوای ParagraphCollection را در ایندکس مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنای که پاراگراف‌ها باید در آن وارد شوند. |
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

مشخص می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | شیء مورد جستجو در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازمی‌گرداند:**
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) پیدا شود؛ در غیر این صورت false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک ایندکس خاص آرایه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | آرایهٔ یک‌بعدی که مقصد عناصر کپی-شده از [IGenericCollection](../../com.aspose.slides/igenericcollection) است. آرایه باید ایندکس صفر-مبنای داشته باشد. |
| arrayIndex | int | ایندکس صفر-مبنای در آرایه که کپی از آنجا شروع می‌شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنای عنصری که باید حذف شود. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | شیءی که باید از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شود. |

**بازمی‌گرداند:**
boolean - true اگر مورد با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شود؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

یک enumerator را برمی‌گرداند که در مجموعه پیمایش می‌کند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumeratorی که می‌توان برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator برای کل مجموعه.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد مجموعه پاراگراف‌ها را برمی‌گرداند. [BaseSlide](../../com.aspose.slides/baseslide) فقط-خواندنی.

**بازمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد مجموعه پاراگراف‌ها را برمی‌گرداند. [IPresentation](../../com.aspose.slides/ipresentation) فقط-خواندنی.

**بازمی‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

متن را از رشتهٔ html مشخص به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

متن را از رشتهٔ html مشخص به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback حل‌کننده که URIها را حل می‌کند و اشیای ارجاعی را دریافت می‌کند. |
| uri | java.lang.String | URI برای افزودن سند HTML. برای حل لینک‌های نسبی استفاده می‌شود.

--------------------

مشخص کردن resolver می‌تواند به‌طور بالقوه یک آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

پاراگراف‌های مشخص شده را به HTML تبدیل کرده و به‌صورت شیء String برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstParagraphIndex | int | ایندکس اولین پاراگراف |
| paragraphsCount | int | تعداد پاراگراف‌ها |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | گزینه‌های تبدیل [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**بازمی‌گرداند:**
java.lang.String - HTML تولید شده.