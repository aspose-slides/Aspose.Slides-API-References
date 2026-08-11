---
title: IDocumentProperties
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يمثل خصائص عرض تقديمي.
type: docs
weight: 1977
url: /ar/aspose.slides/idocumentproperties/
---
## فئة IDocumentProperties

يمثل خصائص عرض تقديمي.

```cpp
class IDocumentProperties : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | يزيل جميع الخصائص المخصصة. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقاط عائمة على نمط C# حيث يُعتبر NaNين متساويين رغم أن IEC 60559:1989 يعتبر NaN غير متساوٍ مع أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقاط عائمة على نمط C# حيث يُعتبر NaNين متساويين رغم أن IEC 60559:1989 يعتبر NaN غير متساوٍ مع أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | يعيد قالب التطبيق. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | يعيد نسخة التطبيق. للقراءة فقط [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | يعيد مؤلف العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | يعيد فئة العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | يعيد تعليقات العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | يعيد خاصية الشركة. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | يعيد حالة محتوى العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | يعيد نوع محتوى العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | يعيد عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. للقراءة فقط **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | يعيد تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. اقرأ [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | يشير إلى تجميع أجزاء المستند وعدد الأجزاء في كل تجميع. للقراءة فقط [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | يحدد عدد الشرائح المخفية في مستند العرض التقديمي. للقراءة فقط **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | يعيد خاصية HyperlinkBase للمستند. اقرأ [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | يحدد أن ارتباطًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة مُنتج. يجب على المُنتج التالي الذي يفتح هذا المستند تحديث علاقات الارتباط بالروابط الجديدة المحددة في هذا الجزء. اقرأ **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | يعيد الكلمات المفتاحية للعرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | يعيد تاريخ طباعة العرض التقديمي آخر مرة. اقرأ [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | يعيد اسم آخر شخص عدل العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | يعيد تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. للقراءة فقط في حالة Presentation.DocumentProperties (لأنه سيتم تحديثها داخليًا أثناء عملية حفظ كائن [IPresentation](../ipresentation/)). يمكن تغييره عبر مثيل [DocumentProperties](../documentproperties/) الذي يرجعها الأسلوب [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). يرجى الاطلاع على المثال في ملخص الأسلوب [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | يوضح ما إذا كانت الروابط في المستند محدثة. عيّن هذا العنصر إلى **true** للدلالة على أن الروابط محدثة. عيّن هذا العنصر إلى **false** للدلالة على أن الروابط قديمة. اقرأ **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | يعيد خاصية المدير. اقرأ [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | يحدد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. للقراءة فقط **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | يعيد اسم التطبيق. اقرأ [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | يحدد عدد الشرائح التي تحتوي على ملاحظات في العرض التقديمي. للقراءة فقط **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | يحدد إجمالي عدد الفقرات الموجودة في المستند إذا كان ذلك مناسبًا. للقراءة فقط **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | يعيد الصيغة المقصودة للعرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | يعيد رقم مراجعة العرض التقديمي. اقرأ **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | يوضح وضع عرض صورة مصغرة للمستند. عيّن هذا العنصر إلى **true** لتمكين تحجيم الصورة المصغرة لتلائم العرض. عيّن هذا العنصر إلى **false** لتمكين قص الصورة المصغرة لعرض الأقسام التي تلائم العرض فقط. اقرأ **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. اقرأ **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | يحدد إجمالي عدد الشرائح في مستند العرض التقديمي. للقراءة فقط **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | يعيد موضوع العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | يعيد عنوان العرض التقديمي. اقرأ [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | يحدد عنوان كل جزء من أجزاء المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفهومية لأقسام المستند. للقراءة فقط [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | إجمالي وقت التحرير للعرض التقديمي. اقرأ [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | يحدد إجمالي عدد الكلمات الموجودة في المستند. للقراءة فقط **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | يرجع اسم خاصية مخصصة عند الفهرس المحدد. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | يحصل على قيمة منطقية مسماة من الخصائص المخصصة. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | يحصل على قيمة عددية صحيحة مسماة من الخصائص المخصصة. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | يحصل على قيمة DateTime مسماة من الخصائص المخصصة. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | يحصل على قيمة سلسلة مسماة من الخصائص المخصصة. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | يحصل على قيمة عائمة مسماة من الخصائص المخصصة. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | يحصل على قيمة مزدوجة مسماة من الخصائص المخصصة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لأسلوب C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | يعيد الخاصية المخصصة المرتبطة بالاسم المحدد. اقرأ [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يحدد الخاصية المخصصة المرتبطة بالاسم المحدد. اكتب [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع المحدد بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ جملة C# lock() لتأمين القفل. استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لأسلوب C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بنسخ الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بنسخ الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيم بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | يزيل خاصية مخصصة مرتبطة بالاسم المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | يحدد قالب التطبيق. اكتب [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | يحدد مؤلف العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | يحدد فئة العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | يحدد تعليقات العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | يحدد خاصية الشركة. اكتب [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | يحدد حالة محتوى العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | يحدد نوع محتوى العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | يعيد تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. اكتب [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | يحدد خاصية HyperlinkBase للمستند. اكتب [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | يحدد أن ارتباطًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة مُنتج. يجب على المُنتج التالي الذي يفتح هذا المستند تحديث علاقات الارتباط بالروابط الجديدة المحددة في هذا الجزء. اكتب **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | يحدد الكلمات المفتاحية للعرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | يعيد تاريخ طباعة العرض التقديمي آخر مرة. اكتب [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | يحدد اسم آخر شخص عدل العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | يعيد تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. للقراءة فقط في حالة Presentation.DocumentProperties (لأنه سيتم تحديثها داخليًا أثناء عملية حفظ كائن [IPresentation](../ipresentation/)). يمكن تغييره عبر مثيل [DocumentProperties](../documentproperties/) الذي يرجعها الأسلوب [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). يرجى الاطلاع على المثال في ملخص الأسلوب [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | يوضح ما إذا كانت الروابط في المستند محدثة. عيّن هذا العنصر إلى **true** للدلالة على أن الروابط محدثة. عيّن هذا العنصر إلى **false** للدلالة على أن الروابط قديمة. اكتب **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | يحدد خاصية المدير. اكتب [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | يحدد اسم التطبيق. اكتب [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | يحدد الصيغة المقصودة للعرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | يحدد رقم مراجعة العرض التقديمي. اكتب **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | يوضح وضع عرض صورة مصغرة للمستند. عيّن هذا العنصر إلى **true** لتمكين تحجيم الصورة المصغرة لتلائم العرض. عيّن هذا العنصر إلى **false** لتمكين قص الصورة المصغرة لعرض الأقسام التي تلائم العرض فقط. اكتب **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. اكتب **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | يحدد موضوع العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | يحدد عنوان العرض التقديمي. اكتب [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | إجمالي وقت التحرير للعرض التقديمي. اكتب [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | يحدد خاصية منطقية مخصصة مسماة. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | يحدد خاصية عددية صحيحة مخصصة مسماة. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | يحدد خاصية DateTime مخصصة مسماة. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | يحدد خاصية سلسلة مخصصة مسماة. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | يحدد خاصية عائمة مخصصة مسماة. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | يحدد خاصية مزدوجة مخصصة مسماة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرةً؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لأسلوب C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ جملة C# lock() لإلغاء القفل. استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)