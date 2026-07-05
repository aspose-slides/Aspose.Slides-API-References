---
title: IDocumentProperties
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل خصائص عرض تقديمي.
type: docs
weight: 5710
url: /ar/aspose.slides/idocumentproperties/
---
## واجهة IDocumentProperties

يمثل خصائص العرض التقديمي.

```csharp
public interface IDocumentProperties
```

## الخصائص

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | يعيد أو يحدد قالب التطبيق. قراءة/كتابة String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | يعيد نسخة التطبيق. قراءة فقط String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | يعيد أو يحدد مؤلف العرض التقديمي. قراءة/كتابة String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | يعيد أو يحدد فئة العرض التقديمي. قراءة/كتابة String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | يعيد أو يحدد تعليقات العرض التقديمي. قراءة/كتابة String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | يعيد أو يحدد خاصية الشركة. قراءة/كتابة String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | يعيد أو يحدد حالة محتوى العرض التقديمي. قراءة/كتابة String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | يعيد أو يحدد نوع محتوى العرض التقديمي. قراءة/كتابة String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | يعيد عدد الخصائص المخصصة الموجودة فعلياً في المجموعة. قراءة فقط Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | يعيد تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قراءة/كتابة DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | يوضح تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. قراءة فقط IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | يحدد عدد الشرائح المخفية في مستند العرض التقديمي. قراءة فقط Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | يعيد أو يحدد خاصية HyperlinkBase للمستند. قراءة/كتابة String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | يحدد أن أحد الروابط أو أكثر في هذا الجزء تم تحديثه حصراً في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذا المستند بتحديث علاقات الروابط بالروابط الجديدة المحددة في هذا الجزء. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | يعيد أو يحدد الخاصية المخصصة المرتبطة باسم محدد. قراءة/كتابة Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | يعيد أو يحدد كلمات مفتاحية للعرض التقديمي. قراءة/كتابة String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | يعيد تاريخ آخر طباعة للعرض التقديمي. قراءة/كتابة DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | يعيد أو يحدد اسم آخر شخص عدّل العرض التقديمي. قراءة/كتابة String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | يعيد تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. قراءة فقط في حالة Presentation.DocumentProperties (لأنها تُحدّث داخلياً أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر كائن DocumentProperties الذي تُعيده الطريقة [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). يرجى الاطلاع على المثال في ملخص الطريقة [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | يوضح ما إذا كانت الروابط في المستند محدثة. ضع هذه القيمة **true** للدلالة على أن الروابط محدثة. ضعها **false** للدلالة على أن الروابط قديمة. قراءة/كتابة Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | يعيد أو يحدد خاصية المدير. قراءة/كتابة String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | يحدد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. قراءة فقط Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | يعيد أو يحدد اسم التطبيق. قراءة/كتابة String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | يحدد عدد الشرائح التي تحتوي على ملاحظات في العرض التقديمي. قراءة فقط Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | يحدد إجمالي عدد الفقرات الموجودة في المستند إذا كان ذلك ممكناً. قراءة فقط Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | يعيد أو يحدد الصيغة المقصودة للعرض التقديمي. قراءة/كتابة String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | يعيد أو يحدد رقم مراجعة العرض التقديمي. قراءة/كتابة Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | يوضح وضع عرض صورة مصغرة للمستند. ضع هذه القيمة **true** لتمكين تحجيم الصورة المصغرة لتناسب العرض. ضعها **false** لتمكين قص الصورة المصغرة لعرض الأقسام التي تتناسب مع العرض فقط. قراءة/كتابة Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | يحدد ما إذا كان العرض التقديمي مشتركاً بين عدة أشخاص. قراءة/كتابة Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | يحدد إجمالي عدد الشرائح في مستند العرض التقديمي. قراءة فقط Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | يعيد أو يحدد موضوع العرض التقديمي. قراءة/كتابة String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | يعيد أو يحدد عنوان العرض التقديمي. قراءة/كتابة String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | يحدد عنوان كل جزء من أجزاء المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفهومية لأقسام المستند. قراءة فقط string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | إجمالي وقت تحرير العرض التقديمي. قراءة/كتابة TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | يحدد إجمالي عدد الكلمات الموجودة في المستند. قراءة فقط Int32. |

## الأساليب

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | يزيل جميع الخصائص المخصصة. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | يرجع اسم الخاصية المخصصة عند الفهرس المحدد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | يحصل على قيمة منطقية مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | يحصل على قيمة DateTime مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | يحصل على قيمة double مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | يحصل على قيمة float مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | يحصل على قيمة int مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | يحصل على قيمة string مسماة من الخصائص المخصصة. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | يزيل خاصية مخصصة مرتبطة بالاسم المحدد. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | يحدد خاصية منطقية مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | يحدد خاصية DateTime مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | يحدد خاصية double مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | يحدد خاصية float مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | يحدد خاصية int مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | يحدد خاصية string مخصصة مسماة. |

### انظر أيضاً

* النطاق [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->