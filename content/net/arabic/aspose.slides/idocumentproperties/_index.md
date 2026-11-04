---
title: IDocumentProperties
second_title: Aspose.Sildes لواجهة برمجة تطبيقات .NET
description: يمثل خصائص عرض تقديمي.
type: docs
weight: 5730
url: /ar/aspose.slides/idocumentproperties/
---
## IDocumentProperties واجهة

يمثل خصائص عرض تقديمي.

```csharp
public interface IDocumentProperties
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | إرجاع أو تعيين قالب تطبيق. قراءة/كتابة String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | إرجاع نسخة التطبيق. قراءة فقط String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | إرجاع أو تعيين مؤلف عرض تقديمي. قراءة/كتابة String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | إرجاع أو تعيين فئة عرض تقديمي. قراءة/كتابة String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | إرجاع أو تعيين تعليقات عرض تقديمي. قراءة/كتابة String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | إرجاع أو تعيين خاصية الشركة. قراءة/كتابة String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | إرجاع أو تعيين حالة محتوى عرض تقديمي. قراءة/كتابة String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | إرجاع أو تعيين نوع محتوى عرض تقديمي. قراءة/كتابة String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | إرجاع عدد الخصائص المخصصة الموجودة فعليًا في مجموعة. قراءة فقط Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | إرجاع تاريخ إنشاء عرض تقديمي. القيم بالتوقيت العالمي UTC. قراءة/كتابة DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | تشير إلى تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. قراءة فقط IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | تحديد عدد الشرائح المخفية في مستند عرض تقديمي. قراءة فقط Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | إرجاع أو تعيين خاصية HyperlinkBase للمستند. قراءة/كتابة String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | تحديد أن رابطًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة مُنتج. يجب على المُنتج التالي الذي يفتح هذا المستند تحديث علاقات الروابط باستخدام الروابط الجديدة المحددة في هذا الجزء. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | إرجاع أو تعيين الخاصية المخصصة المرتبطة باسم محدد. قراءة/كتابة Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | إرجاع أو تعيين كلمات مفتاحية لعرض تقديمي. قراءة/كتابة String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | إرجاع تاريخ طباعة عرض تقديمي آخر مرة. قراءة/كتابة DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | إرجاع أو تعيين اسم آخر شخص قام بتعديل عرض تقديمي. قراءة/كتابة String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | إرجاع تاريخ آخر تعديل لعرض تقديمي. القيم بالتوقيت العالمي UTC. قراءة فقط في حالة Presentation.DocumentProperties (لأنه سيتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر نسخة DocumentProperties التي تُرجعها الطريقة [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). يرجى الاطلاع على المثال في ملخص الطريقة [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | تشير إلى ما إذا كانت الروابط في المستند محدثة. اضبط هذا العنصر على **true** للدلالة على أن الروابط محدثة. اضبط هذا العنصر على **false** للدلالة على أن الروابط قديمة. قراءة/كتابة Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | إرجاع أو تعيين خاصية المدير. قراءة/كتابة String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | تحديد العدد الكلي لمقاطع الصوت أو الفيديو الموجودة في المستند. قراءة فقط Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | إرجاع أو تعيين اسم التطبيق. قراءة/كتابة String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | تحديد عدد الشرائح في عرض تقديمي تحتوي على ملاحظات. قراءة فقط Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | تحديد العدد الكلي للفقرات الموجودة في المستند إذا كان ذلك قابلًا للتطبيق. قراءة فقط Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | إرجاع أو تعيين الصيغة المقصودة لعرض تقديمي. قراءة/كتابة String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | إرجاع أو تعيين رقم مراجعة العرض التقديمي. قراءة/كتابة Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | تشير إلى وضع عرض الصورة المصغرة للمستند. اضبط هذا العنصر على **true** لتمكين تكبير الصورة المصغرة لتناسب الشاشة. اضبط هذا العنصر على **false** لتمكين قص الصورة المصغرة لإظهار الأقسام التي تتناسب مع الشاشة. قراءة/كتابة Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | تحديد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. قراءة/كتابة Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | تحديد العدد الكلي للشرائح في مستند عرض تقديمي. قراءة فقط Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | إرجاع أو تعيين موضوع عرض تقديمي. قراءة/كتابة String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | إرجاع أو تعيين عنوان عرض تقديمي. قراءة/كتابة String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | تحديد عنوان كل جزء من المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفاهيمية لأقسام المستند. قراءة فقط string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | إجمالي وقت تحرير عرض تقديمي. قراءة/كتابة TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | تحديد عدد الكلمات الكلي الموجود في المستند. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | يزيل جميع الخصائص المخصصة. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | التحقق من وجود خاصية مخصصة باسم محدد. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | إرجاع اسم خاصية مخصصة عند الفهرس المحدد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | الحصول على قيمة منطقية مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | الحصول على قيمة DateTime مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | الحصول على قيمة double مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | الحصول على قيمة float مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | الحصول على قيمة عددية (int) مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | الحصول على قيمة سلسلة (string) مسماة من الخصائص المخصصة. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | الحصول على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | إزالة خاصية مخصصة مرتبطة باسم محدد. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ضبط خاصية مخصصة منطقية مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ضبط خاصية مخصصة من نوع DateTime مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ضبط خاصية مخصصة من نوع double مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ضبط خاصية مخصصة من نوع float مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ضبط خاصية مخصصة من نوع int مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ضبط خاصية مخصصة من نوع string مسماة. |

### انظر أيضاً

* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->