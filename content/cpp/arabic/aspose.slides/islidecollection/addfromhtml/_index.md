---
title: AddFromHtml()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.
type: docs
weight: 144
url: /ar/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

ينشئ الشرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null جميع الكائنات الخارجية سيتم تجاهلها. |
| uri | [System::String](../../../system/string/) | عنوان URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::AddFromHtml(System::String) طريقة

ينشئ الشرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

ينشئ الشرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null جميع الكائنات الخارجية سيتم تجاهلها. |
| uri | [System::String](../../../system/string/) | عنوان URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) طريقة

ينشئ الشرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

ينشئ الشرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null جميع الكائنات الخارجية سيتم تجاهلها. |
| uri | [System::String](../../../system/string/) | عنوان URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) طريقة

ينشئ الشرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)