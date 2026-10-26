---
title: IDocumentProperties
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثّل خصائص عرض تقديمي.
type: docs
weight: 5710
url: /ar/aspose.slides/idocumentproperties/
---
## IDocumentProperties واجهة

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | إرجاع أو تعيين قالب التطبيق. قابل للقراءة/الكتابة String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | إرجاع إصدار التطبيق. للقراة فقط String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | إرجاع أو تعيين مؤلف العرض التقديمي. قابل للقراءة/الكتابة String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | إرجاع أو تعيين فئة العرض التقديمي. قابل للقراءة/الكتابة String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | إرجاع أو تعيين تعليقات العرض التقديمي. قابل للقراءة/الكتابة String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | إرجاع أو تعيين خاصية الشركة. قابل للقراءة/الكتابة String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | إرجاع أو تعيين حالة محتوى العرض التقديمي. قابل للقراءة/الكتابة String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | إرجاع أو تعيين نوع محتوى العرض التقديمي. قابل للقراءة/الكتابة String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | إرجاع عدد الخصائص المخصَّصة المتوفرة فعليًا في مجموعة. للقراة فقط Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | إرجاع تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قابل للقراءة/الكتابة DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | يُظهر تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. للقراة فقط IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | يحدد عدد الشرائح المخفية في مستند العرض التقديمي. للقراة فقط Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | إرجاع أو تعيين خاصية HyperlinkBase للمستند. قابل للقراءة/الكتابة String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | يحدد أن ارتباطًا تشعبيًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذا المستند بتحديث علاقات الارتباطات التشعبية باستخدام الارتباطات التشعبية الجديدة المحددة في هذا الجزء. قابل للقراءة/الكتابة Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | إرجاع أو تعيين الخاصية المخصَّصة المرتبطة باسم محدد. قابل للقراءة/الكتابة Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | إرجاع أو تعيين كلمات مفتاحية للعرض التقديمي. قابل للقراءة/الكتابة String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | إرجاع تاريخ آخر طباعة للعرض التقديمي. قابل للقراءة/الكتابة DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | إرجاع أو تعيين اسم آخر شخص عدّل العرض التقديمي. قابل للقراءة/الكتابة String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | إرجاع تاريخ تعديل العرض التقديمي الأخير. القيم بتوقيت UTC. للقراة فقط في حالة Presentation.DocumentProperties (لأنه سيُحدَّث داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties المُعاد بواسطة الطريقة [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). يرجى الاطلاع على المثال في ملخص الطريقة [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | يُشير ما إذا كانت الارتباطات التشعبية في المستند محدثة. اضبط هذا العنصر إلى **true** للدلالة على أن الارتباطات محدثة. اضبطه إلى **false** للدلالة على أن الارتباطات قديمة. قابل للقراءة/الكتابة Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | إرجاع أو تعيين خاصية المدير. قابل للقراءة/الكتابة String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | يحدد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. للقراة فقط Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | إرجاع أو تعيين اسم التطبيق. قابل للقراءة/الكتابة String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | يحدد عدد الشرائح في العرض التقديمي التي تحتوي على ملاحظات. للقراة فقط Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | يحدد إجمالي عدد الفقرات الموجودة في المستند إذا كان ذلك قابلًا للتطبيق. للقراة فقط Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | إرجاع أو تعيين الصيغة المطلوبة للعرض التقديمي. قابل للقراءة/الكتابة String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | إرجاع أو تعيين رقم مراجعة العرض التقديمي. قابل للقراءة/الكتابة Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | يُظهر وضع عرض الصورة المصغرة للمستند. اضبط هذا العنصر إلى **true** لتمكين تحجيم الصورة المصغرة لتناسب العرض. اضبطه إلى **false** لتمكين قص الصورة المصغرة لعرض الأقسام التي تناسب العرض فقط. قابل للقراءة/الكتابة Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | يحدد ما إذا كان العرض مشتركًا بين عدة أشخاص. قابل للقراءة/الكتابة Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | يحدد إجمالي عدد الشرائح في مستند العرض التقديمي. للقراة فقط Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | إرجاع أو تعيين موضوع العرض التقديمي. قابل للقراءة/الكتابة String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | إرجاع أو تعيين عنوان العرض التقديمي. قابل للقراءة/الكتابة String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | يحدد عنوان كل جزء من المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفهومية لأقسام المستند. للقراة فقط string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | إجمالي وقت تحرير العرض التقديمي. قابل للقراءة/الكتابة TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | يحدد إجمالي عدد الكلمات الموجودة في المستند. للقراة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | يزيل جميع الخصائص المخصَّصة. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | يتحقق من وجود خاصية مخصَّصة بالاسم المحدد. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | إرجاع اسم الخاصية المخصَّصة في الفهرس المحدد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | الحصول على قيمة منطقية مسماة من الخصائص المخصَّصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | الحصول على قيمة DateTime مسماة من الخصائص المخصَّصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | الحصول على قيمة double مسماة من الخصائص المخصَّسة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | الحصول على قيمة float مسماة من الخصائص المخصَّسة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | الحصول على قيمة عددية صحيحة مسماة من الخصائص المخصَّسة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | الحصول على قيمة سلسلة مسماة من الخصائص المخصَّسة. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | الحصول على مصفوفة من رؤوس الحساسية من الخصائص المخصَّصة للمستند (بيانات Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | إزالة خاصية مخصَّصة مرتبطة باسم محدد. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ضبط خاصية مخصَّصة منطقية مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ضبط خاصية مخصَّصة DateTime مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ضبط خاصية مخصَّصة double مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ضبط خاصية مخصَّصة float مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ضبط خاصية مخصَّسة عددية صحيحة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ضبط خاصية مخصَّسة سلسلة مسماة. |

### انظر أيضًا

* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->