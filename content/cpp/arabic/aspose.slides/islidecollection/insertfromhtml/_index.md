---
title: InsertFromHtml()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.
type: docs
weight: 157
url: /ar/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | معرف URI الخاص بـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::InsertFromHtml(int32_t, System::String) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader يُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | معرف URI الخاص بـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | كائن TextReader يُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream يُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | معرف URI الخاص بـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream يُستخدم كمصدر لملف HTML. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlText | [System::String](../../../system/string/) | HTML للإضافة. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | معرف URI الخاص بـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream يُستخدم كمصدر لملف HTML. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) طريقة

يقوم بإنشاء شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج العنصر. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | كائن Stream يُستخدم كمصدر لملف HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | [System::String](../../../system/string/) | معرف URI الخاص بـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

### قيمة الإرجاع

الشرائح المضافة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [String](../../../system/string/)
* فئة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* فئة [ISlideCollection](../)
* فئة [TextReader](../../../system.io/textreader/)
* فئة [Stream](../../../system.io/stream/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)