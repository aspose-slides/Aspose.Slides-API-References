---
title: SlideCollection
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل مجموعة من الشرائح.
type: docs
weight: 5188
url: /ar/aspose.slides/slidecollection/
---
## SlideCollection الفئة

يمثل مجموعة من الشرائح.

```cpp
class SlideCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Presentation>>,
                        public Aspose::Slides::ISlideCollection
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, **bool**) override | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم مثل تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم رفع استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddEmptySlide](./addemptyslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>) override | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::String](../../system/string/)) override | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::PdfImportOptions](../../aspose.slides.import/pdfimportoptions/)\>) override | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع الأخذ في الاعتبار خيارات استيراد PDF. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::PdfImportOptions](../../aspose.slides.import/pdfimportoptions/)\>) override | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [iterator](./iterator/) [begin](./begin/)() | يحصل على مؤشّر يشير إلى العنصر الأول (إن وجد) في المجموعة. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | يحصل على مؤشّر يشير إلى العنصر الأول (إن وجد) من نسخة المجموعة المؤهلة بثابت. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | يحصل على مؤشّر يشير إلى العنصر الأول المؤهل بثابت (إن وجد) في المجموعة. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | يحصل على مؤشّر يشير مباشرة بعد العنصر الأخير المؤهل بثابت (إن وجد) في المجموعة. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>, **int32_t**) override | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [iterator](./iterator/) [end](./end/)() | يحصل على مؤشّر يشير مباشرة بعد العنصر الأخير (إن وجد) في المجموعة. |
| [const_iterator](./const_iterator/) [end](./end/)() const | يحصل على مؤشّر يشير مباشرة بعد العنصر الأخير (إن وجد) من نسخة المجموعة المؤهلة بثابت. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن وفقًا لمعيار IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن وفقًا لمعيار IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_Count](./get_count/)() override | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط **int32_t**. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | يرجع جذر المزامنة. للقراءة فقط [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>\> [GetEnumerator](./getenumerator/)() override | يرجع عدّادًا يتنقل عبر المجموعة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح إنشاء تجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [idx_get](./idx_get/)(**int32_t**) override | يحصل على العنصر عند الفهرس المحدد. للقراءة فقط [Slide](../slide/). |
| **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | يرجع فهرس الشريحة المحددة في المجموعة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, **bool**) override | يدرج نسخة من شريحة مصدر محددة إلى الموضع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم مثل تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم رفع استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertEmptySlide](./insertemptyslide/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/), **bool**) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), **bool**) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/), **bool**) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, **bool**) override | ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الوصفي بواسطة targetType. مماثل لمشغل C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة المُراكم على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تحقق شرطًا. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان هناك أي عنصر في التسلسل أو إذا كان يحقق شرطًا. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب متوسط قائمة من القيم الرقمية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط قائمة من القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يحوِّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يربط تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع عدد العناصر في التسلسل التي تحقق الشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يرجع العنصر عند فهرس محدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يرجع العنصر عند فهرس محدد في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يرجع العنصر الأول في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع العنصر الأول في التسلسل الذي يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يرجع العنصر الأول في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرجع العنصر الأول في التسلسل الذي يحقق شرطًا أو قيمة افتراضية إذا لم يُعثر على أي عنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يُجَمِّع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يُجَمِّع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | يرجع العنصر الأخير في التسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | يرجع العنصر الأخير في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | يصفي عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل بترتيب تصاعدي وفقًا لقيم المفتاح التي يختارها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح التي يختارها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر من التسلسل إلى صيغة جديدة من خلال دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يَProj… (يُسقط) عناصر التسلسل ويجمع المجموعات الناتجة في مجموعة واحدة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية التسلسل ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يرجع عددًا محددًا من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يصفي تسلسلًا بناءً على العبارة الشرطية المحددة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يتهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يتهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | يزيل أول ظهور لكائن معين من المجموعة. |
| void [RemoveAt](./removeat/)(**int32_t**) override | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | ينقل شريحة من المجموعة إلى الموضع المحدد. |
| void [Reorder](./reorder/)(**int32_t**, const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>\&) override | ينقل شرائح من المجموعة إلى الموضع المحدد. سيتم وضع [Slides](../) بدءًا من الفهرس وفقًا للترتيب الذي تظهر به في القائمة. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط معامل القالب الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استبدله باستخدام المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استبدله باستخدام المؤشرات الذكية أو ThisProtector. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [ToArray](./toarray/)() override | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على مؤشّر يشير إلى العنصر الأول (إن وجد) من نسخة المجموعة المؤهلة بثابت. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على مؤشّر يشير إلى العنصر الأول (إن وجد) في المجموعة. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على مؤشّر يشير مباشرة بعد العنصر الأخير (إن وجد) من نسخة المجموعة المؤهلة بثابت. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على مؤشّر يشير مباشرة بعد العنصر الأخير (إن وجد) في المجموعة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استبدله باستخدام المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استبدله باستخدام المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمّر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## التعريفات

| تعريف نوع | وصف |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | نوع مجموعة يُستخدم نوع مؤشّره كمؤشرات في المجموعة الحالية. |
| [iterator](./iterator/) | نوع المؤشر. |
| [const_iterator](./const_iterator/) | نوع المؤشر الثابت. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | نوع العنصر الافتراضي. |
| [virtualized_iterator](./virtualized_iterator/) | النوع الافتراضي. |

## راجع أيضا

* الفئة [DomObject](../domobject/)
* الفئة [ISlideCollection](../islidecollection/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)