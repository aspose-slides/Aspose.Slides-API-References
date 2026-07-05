---
title: DocumentProperties
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثل خصائص العرض التقديمي.
type: docs
weight: 2790
url: /ar/aspose.slides/documentproperties/
---
## DocumentProperties الفئة

يمثل خصائص عرض تقديمي.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocumentProperties](documentproperties)() | إنشاء مثيل جديد من الفئة [`DocumentProperties`](../documentproperties). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | إرجاع أو تعيين قالب التطبيق. Read/write String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | إرجاع إصدار التطبيق. Read-only String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | إرجاع أو تعيين مؤلف العرض التقديمي. Read/write String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | إرجاع أو تعيين فئة العرض التقديمي. Read/write String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | إرجاع أو تعيين تعليقات العرض التقديمي. Read/write String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | إرجاع أو تعيين خاصية الشركة. Read/write String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | إرجاع أو تعيين حالة محتوى العرض التقديمي. Read/write String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | إرجاع أو تعيين نوع محتوى العرض التقديمي. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | إرجاع عدد الخصائص المخصصة الموجودة فعليًا في المجموعة. Read-only Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | إرجاع تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | يشير إلى تجميع أجزاء الوثيقة وعدد الأجزاء في كل مجموعة. Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | إرجاع عدد الشرائح المخفية في وثيقة العرض التقديمي. Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | إرجاع أو تعيين خاصية HyperlinkBase للوثيقة. Read/write String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | يحدد أن روابطًا تشعبية واحدة أو أكثر في هذا الجزء تم تحديثها حصريًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي الذي يفتح هذه الوثيقة بتحديث علاقات الروابط التشعبية بالروابط الجديدة المحددة في هذا الجزء. Read/write Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | إرجاع أو تعيين الخاصية المخصصة المرتبطة بالاسم المحدد. Read/write Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | إرجاع أو تعيين الكلمات المفتاحية للعرض التقديمي. Read/write String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | إرجاع تاريخ آخر طباعة للعرض التقديمي. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | إرجاع أو تعيين اسم آخر شخص عدل العرض التقديمي. Read/write String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | إرجاع تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. Read-only في حالة Presentation.DocumentProperties (لأنه سيتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties المرجع من الطريقة [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). يرجى الاطلاع على المثال في ملخص الطريقة [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | يحدد ما إذا كانت الروابط التشعبية في الوثيقة محدثة. اضبط هذا العنصر على **true** للدلالة على أن الروابط محدثة. اضبطه على **false** للدلالة على أن الروابط قديمة. Read/write Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | إرجاع أو تعيين خاصية المدير. Read/write String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | إرجاع إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في الوثيقة. Read-only Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | إرجاع أو تعيين اسم التطبيق. Read/write String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | إرجاع عدد الشرائح التي تحتوي على ملاحظات في العرض التقديمي. Read-only Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | إرجاع إجمالي عدد الفقرات الموجودة في الوثيقة إذا كان ذلك قابلًا للتطبيق. Read-only Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | إرجاع أو تعيين الصيغة المقصودة للعرض التقديمي. Read/write String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | إرجاع أو تعيين رقم مراجعة العرض التقديمي. Read/write Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | يحدد وضع عرض صورة مصغرة للوثيقة. اضبط هذا العنصر على **true** لتمكين تحجيم الصورة المصغرة لتناسب العرض. اضبطه على **false** لتمكين قص الصورة المصغرة لعرض الأقسام التي تتناسب مع العرض. Read/write Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. Read/write Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | إرجاع إجمالي عدد الشرائح في وثيقة العرض التقديمي. Read-only Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | إرجاع أو تعيين موضوع العرض التقديمي. Read/write String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | إرجاع أو تعيين عنوان العرض التقديمي. Read/write String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | يحدد عنوان كل جزء من أجزاء الوثيقة. هذه الأجزاء ليست أجزاء وثيقة فعلية بل تمثيلات مفهومية لأقسام الوثيقة. Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | إجمالي وقت تحرير العرض التقديمي. Read/write TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | إرجاع إجمالي عدد الكلمات الموجودة في الوثيقة. Read-only Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | يزيل جميع الخصائص المخصصة. |
| [Clone](../../aspose.slides/documentproperties/clone)() | نسخ كائن الحالي |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | نسخ كائن الحالي |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | التحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | إرجاع اسم الخاصية المخصصة عند الفهرس المحدد. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | الحصول على قيمة بوليانية مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | الحصول على قيمة DateTime مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | الحصول على قيمة double مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | الحصول على قيمة float مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | الحصول على قيمة integer مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | الحصول على قيمة string مسماة من الخصائص المخصصة. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | الحصول على مصفوفة من تسميات الحساسية من خصائص الوثيقة المخصصة (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | إزالة خاصية مخصصة مرتبطة بالاسم المحدد. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | تعيين خاصية بوليانية مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | تعيين خاصية DateTime مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | تعيين خاصية double مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | تعيين خاصية float مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | تعيين خاصية integer مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | تعيين خاصية string مخصصة مسماة. |

### أمثلة

المثال التالي يوضح كيفية الوصول إلى الخصائص المدمجة للعرض التقديمي في PowerPoint.

```csharp
[C#]
// إنشاء كائن من الفئة Presentation الذي يمثل العرض التقديمي
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// إنشاء مرجع إلى كائن IDocumentProperties المرتبط بالعرض التقديمي
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// عرض الخصائص المدمجة
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

المثال التالي يوضح كيفية تعديل الخصائص المدمجة للعرض التقديمي في PowerPoint.

```csharp
[C#]
// إنشاء كائن من الفئة Presentation الذي يمثل العرض التقديمي
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// إنشاء مرجع إلى كائن IDocumentProperties المرتبط بالعرض التقديمي
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// تعيين الخصائص المدمجة
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// حفظ العرض التقديمي إلى ملف
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* واجهة [IDocumentProperties](../idocumentproperties)
* واجهة [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->