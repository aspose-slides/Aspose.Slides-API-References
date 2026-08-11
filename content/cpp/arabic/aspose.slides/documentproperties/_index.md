---
title: DocumentProperties
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل خصائص العرض التقديمي.
type: docs
weight: 794
url: /ar/aspose.slides/documentproperties/
---
## فئة DocumentProperties


يمثل خصائص العرض التقديمي.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## الطرق

| Method | الوصف |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | يزيل جميع الخصائص المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ الكائن الحالي |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | ينسخ الكائن الحالي |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
|  [DocumentProperties](./documentproperties/)() | يبادر إنشاء نسخة جديدة من الفئة [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-انّان متساويتين بالرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-انّان متساويتين بالرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | يعيد قالب التطبيق. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | يعيد نسخة التطبيق. قراءة فقط [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | يعيد مؤلف العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | يعيد فئة العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | يعيد تعليقات العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | يعيد خاصية الشركة. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | يعيد حالة محتوى العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | يعيد نوع محتوى العرض التقديمي. اقرأ [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | يعيد عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. قراءة فقط **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | يعيد تاريخ إنشاء العرض التقديمي. القيم بالتوقيت UTC. اقرأ [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | يوضح تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. قراءة فقط [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | يعيد عدد الشرائح المخفية في مستند العرض التقديمي. قراءة فقط **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | يعيد خاصية HyperlinkBase للمستند. اقرأ [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | يحدد أن ارتباطًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. يجب على المنتج التالي فتح هذا المستند أن يُحدّث علاقات الارتباط بالارتباطات الجديدة المحددة في هذا الجزء. اقرأ **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | يعيد كلمات المفتاح للعرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | يعيد تاريخ طباعة العرض التقديمي آخر مرة. اقرأ [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | يعيد اسم آخر شخص عدّل العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | يعيد تاريخ تعديل العرض التقديمي آخر مرة. القيم بالتوقيت UTC. قراءة فقط في حالة [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (لأنها ستُحدّث داخليًا أثناء عملية حفظ كائن [IPresentation](../ipresentation/)). يمكن تغييره عبر المثيل [DocumentProperties](./) الذي تُعيده الطريقة [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). يرجى الاطلاع على المثال في ملخص الطريقة [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | يوضح ما إذا كانت الارتباطات في المستند محدثة. ضع هذا العنصر **true** للإشارة إلى أن الارتباطات محدثة. ضع هذا العنصر **false** للإشارة إلى أن الارتباطات قديمة. اقرأ **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | يعيد خاصية المدير. اقرأ [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | يعيد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. قراءة فقط **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | يعيد اسم التطبيق. اقرأ [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | يعيد عدد الشرائح في عرض تقديمي يحتوي على ملاحظات. قراءة فقط **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | يعيد إجمالي عدد الفقرات الموجودة في مستند إذا كان ذلك ممكنًا. قراءة فقط **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | يعيد الصيغة المقصودة للعرض التقديمي. اقرأ [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | يعيد رقم نسخة العرض التقديمي. اقرأ **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | يحدد وضع عرض صورة المصغرة للمستند. ضع هذا العنصر **true** لتمكين تكبير صورة المصغرة لتناسب العرض. وضعه **false** لتمكين قص صورة المصغرة لإظهار الأقسام التي تتناسب مع العرض. اقرأ **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. اقرأ **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | يعيد إجمالي عدد الشرائح في مستند العرض التقديمي. قراءة فقط **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | يعيد موضوع العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | يعيد عنوان العرض التقديمي. اقرأ [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | يحدد عنوان كل جزء من المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفاهيمية لأقسام المستند. قراءة فقط [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | إجمالي وقت تحرير العرض التقديمي. اقرأ [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | يعيد إجمالي عدد الكلمات الموجودة في المستند. قراءة فقط **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المراجع المرتبطة بالكائن. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | يعيد اسم خاصية مخصصة في الفهرس المحدد. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | يحصل على قيمة منطقية مسماة من الخصائص المخصصة. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | يحصل على قيمة عددية صحيحة مسماة من الخصائص المخصصة. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | يحصل على قيمة DateTime مسماة من الخصائص المخصصة. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | يحصل على قيمة سلسلة مسماة من الخصائص المخصصة. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | يحصل على قيمة عائمة مسماة من الخصائص المخصصة. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | يحصل على قيمة مزدوجة مسماة من الخصائص المخصصة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | يعيد الخاصية المخصصة المرتبطة بالاسم المحدد. اقرأ [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد الخاصية المخصصة المرتبطة بالاسم المحدد. اكتب [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير معامل C# ‎'is'‎. |
| void [Lock](../../system/object/lock/)() | ينفّذ بيان C# lock() للقفل. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يتهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، بل يتهيء كائنًا جديدًا ويمكّن بناؤه في الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يتهيء كائنًا جديدًا ويمكّن بناؤه في الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | يزيل خاصية مخصصة مرتبطة بالاسم المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | يحدد قالب التطبيق. اكتب [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | يحدد مؤلف العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | يحدد فئة العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | يحدد تعليقات العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | يحدد خاصية الشركة. اكتب [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | يحدد حالة محتوى العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | يحدد نوع محتوى العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | يحدد تاريخ إنشاء العرض التقديمي. القيم بالتوقيت UTC. اكتب [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | يحدد خاصية HyperlinkBase للمستند. اكتب [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | يحدد أن ارتباطًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. يجب على المنتج التالي فتح هذا المستند أن يُحدّث علاقات الارتباط بالارتباطات الجديدة المحددة في هذا الجزء. اكتب **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | يحدد كلمات المفتاح للعرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | يحدد تاريخ طباعة العرض التقديمي آخر مرة. اكتب [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | يحدد اسم آخر شخص عدّل العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | يحدد تاريخ تعديل العرض التقديمي آخر مرة. القيم بالتوقيت UTC. قراءة فقط في حالة [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (لأنها ستُحدّث داخليًا أثناء عملية حفظ كائن [IPresentation](../ipresentation/)). يمكن تغييره عبر المثيل [DocumentProperties](./) الذي تُعيده الطريقة [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). يرجى الاطلاع على المثال في ملخص الطريقة [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | يوضح ما إذا كانت الارتباطات في المستند محدثة. ضع هذا العنصر **true** للإشارة إلى أن الارتباطات محدثة. ضع هذا العنصر **false** للإشارة إلى أن الارتباطات قديمة. اكتب **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | يحدد خاصية المدير. اكتب [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | يحدد اسم التطبيق. اكتب [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | يحدد الصيغة المقصودة للعرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | يحدد رقم نسخة العرض التقديمي. اكتب **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | يحدد وضع عرض صورة المصغرة للمستند. ضع هذا العنصر **true** لتمكين تكبير صورة المصغرة لتناسب العرض. وضعه **false** لتمكين قص صورة المصغرة لإظهار الأقسام التي تتناسب مع العرض. اكتب **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. اكتب **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | يحدد موضوع العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | يحدد عنوان العرض التقديمي. اكتب [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | إجمالي وقت تحرير العرض التقديمي. اكتب [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | يحدد خاصية منطقية مخصصة مسماة. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | يحدد خاصية عددية صحيحة مخصصة مسماة. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | يحدد خاصية DateTime مخصصة مسماة. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | يحدد خاصية سلسلة مخصصة مسماة. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | يحدد خاصية عائمة مخصصة مسماة. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | يحدد خاصية مزدوجة مخصصة مسماة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد الإشارة المشتركة ويعيده. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ بيان C# lock() لإلغاء القفل. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يفرغ جميع بنى البيانات الداخلية. |

## ملاحظات


يوضح المثال التالي كيفية الوصول إلى الخصائص المدمجة في PowerPoint [Presentation](../presentation/). 
```cpp
// إنشاء مثيل لفئة Presentation التي تمثل العرض التقديمي
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
يوضح المثال التالي كيفية تعديل الخصائص المدمجة في PowerPoint [Presentation](../presentation/). 
```cpp
// إنشاء مثيل لفئة Presentation التي تمثل العرض التقديمي
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Set the builtin properties
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* فئة [IDocumentProperties](../idocumentproperties/)
* فئة [IGenericCloneable](../igenericcloneable/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)