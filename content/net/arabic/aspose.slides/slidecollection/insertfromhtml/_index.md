---
title: InsertFromHtml
second_title: Aspose.Sildes لـ .NET مرجع API
description: ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.
type: docs
weight: 140
url: /ar/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlText | String | الـ Html للإضافة. |
| resolver | IExternalResourceResolver | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الواجهة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlText | String | الـ Html للإضافة. |
| resolver | IExternalResourceResolver | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | Boolean | يحدد هذا العلم طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة التي لها الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

### قيمة الإرجاع

الشرائح المضافة.

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الواجهة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlText | String | الـ Html للإضافة. |

### قيمة الإرجاع

الشرائح المضافة

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlText | String | الـ Html للإضافة. |
| useSlideWithIndexAsStart | Boolean | يحدد هذا العلم طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة التي لها الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

### قيمة الإرجاع

الشرائح المضافة

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlReader | TextReader | كائن TextReader سيُستخدم كمصدر لملف HTML. |
| resolver | IExternalResourceResolver | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الواجهة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlReader | TextReader | كائن TextReader سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlStream | Stream | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | IExternalResourceResolver | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الواجهة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في المووقع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlStream | Stream | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | IExternalResourceResolver | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | Boolean | يحدد هذا العلم طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة التي لها الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

### قيمة الإرجاع

الشرائح المضافة.

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الواجهة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlStream | Stream | كائن Stream سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الموضع للإدراج. |
| htmlStream | Stream | كائن Stream سيُستخدم كمصدر لملف HTML. |
| useSlideWithIndexAsStart | Boolean | يحدد هذا العلم طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة التي لها الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

### قيمة الإرجاع

الشرائح المضافة

### انظر أيضاً

* الواجهة [ISlide](../../islide)
* الفئة [SlideCollection](../../slidecollection)
* مساحة الاسم [Aspose.Slides](../../slidecollection)
* التجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->