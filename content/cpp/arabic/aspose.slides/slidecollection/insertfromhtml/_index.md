---
title: InsertFromHtml()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.
type: docs
weight: 209
url: /ar/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlText | [System::String](../../../system/string/) | HTML لإضافته. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | URI لملف HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlText | [System::String](../../../system/string/) | HTML لإضافته. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | URI لملف HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::InsertFromHtml(int32_t, System::String) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlText | [System::String](../../../system/string/) | HTML لإضافته. |

### قيمة الإرجاع

الشرائح المضافة

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlText | [System::String](../../../system/string/) | HTML لإضافته. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | URI لملف HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | URI لملف HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | URI لملف HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) طريقة

ينشئ شرائح من نص HTML ويُدرجها في التجميع في الموضع المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع للإدراج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [String](../../../system/string/)
* فئة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* فئة [SlideCollection](../)
* فئة [TextReader](../../../system.io/textreader/)
* فئة [Stream](../../../system.io/stream/)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)