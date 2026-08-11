---
title: AddFromHtml()
second_title: مرجع API Aspose.Slides لـ C++
description: ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.
type: docs
weight: 196
url: /ar/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن استدعاء رجعي يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | عنوان URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::AddFromHtml(System::String) method


ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |

### قيمة الإرجاع

الشرائح المضافة

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن استدعاء رجعي يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | عنوان URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method


ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن استدعاء رجعي يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | عنوان URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method


ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream سيُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة
## ملاحظات




```cpp
// إنشاء كائن من فئة Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // استدعاء طريقة AddFromHtml وتمرير ملف HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// استخدام طريقة Save لحفظ الملف كوثيقة PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [String](../../../system/string/)
* فئة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* فئة [SlideCollection](../)
* فئة [TextReader](../../../system.io/textreader/)
* فئة [Stream](../../../system.io/stream/)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)