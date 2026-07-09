---
title: DocumentProperties
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل خصائص عرض تقديمي.
type: docs
weight: 2790
url: /ar/aspose.slides/documentproperties/
---
## DocumentProperties فئة

يمثل خصائص عرض تقديمي.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [DocumentProperties](documentproperties)() | يهيء مثلاً جديداً للفئة [`DocumentProperties`](../documentproperties). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | يقوم بإرجاع أو تعيين قالب تطبيق. قراءة/كتابة String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | يعيد إصدار التطبيق. قراءة فقط String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | يقوم بإرجاع أو تعيين مؤلف العرض التقديمي. قراءة/كتابة String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | يقوم بإرجاع أو تعيين فئة العرض التقديمي. قراءة/كتابة String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | يقوم بإرجاع أو تعيين تعليقات العرض التقديمي. قراءة/كتابة String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | يقوم بإرجاع أو تعيين خاصية الشركة. قراءة/كتابة String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | يقوم بإرجاع أو تعيين حالة محتوى العرض التقديمي. قراءة/كتابة String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | يقوم بإرجاع أو تعيين نوع محتوى العرض التقديمي. قراءة/كتابة String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | يعيد عدد الخصائص المخصصة الموجودة فعلياً في مجموعة. قراءة فقط Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | يعيد تاريخ إنشاء العرض التقديمي. القيم بتوقيت UTC. قراءة/كتابة DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | يشير إلى تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. قراءة فقط IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | يعيد عدد الشرائح المخفية في مستند العرض التقديمي. قراءة فقط Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | يقوم بإرجاع أو تعيين خاصية المستند HyperlinkBase. قراءة/كتابة String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | يحدد أن رابطًا أو أكثر في هذا الجزء تم تحديثه حصريًا في هذا الجزء من قبل منتج. المنتج التالي الذي يفتح هذا المستند سيقوم بتحديث علاقات الروابط باستخدام الروابط الجديدة المحددة في هذا الجزء. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | يقوم بإرجاع أو تعيين الخاصية المخصصة المرتبطة باسم محدد. قراءة/كتابة Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | يقوم بإرجاع أو تعيين كلمات مفتاحية للعرض التقديمي. قراءة/كتابة String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | يعيد تاريخ آخر طباعة للعرض التقديمي. قراءة/كتابة DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | يقوم بإرجاع أو تعيين اسم آخر شخص عدل العرض التقديمي. قراءة/كتابة String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | يعيد تاريخ آخر تعديل للعرض التقديمي. القيم بتوقيت UTC. قراءة فقط في حالة Presentation.DocumentProperties (لأنه سيتم تحديثه داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties الذي تُرجعه الطريقة [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). يرجى الاطلاع على المثال في ملخص الطريقة [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | يشير إلى ما إذا كانت الروابط في المستند محدثة. ضع هذا العنصر **true** للدلالة على أن الروابط محدثة. ضع هذا العنصر **false** للدلالة على أن الروابط قديمة. قراءة/كتابة Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | يقوم بإرجاع أو تعيين خاصية المدير. قراءة/كتابة String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | يعيد العدد الإجمالي لمقاطع الصوت أو الفيديو الموجودة في المستند. قراءة فقط Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | يقوم بإرجاع أو تعيين اسم التطبيق. قراءة/كتابة String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | يعيد عدد الشرائح في عرض تقديمي يحتوي على ملاحظات. قراءة فقط Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | يعيد العدد الإجمالي للفقرات الموجودة في المستند إذا كان ذلك مناسبًا. قراءة فقط Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | يقوم بإرجاع أو تعيين الصيغة المقصودة للعرض التقديمي. قراءة/كتابة String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | يقوم بإرجاع أو تعيين رقم مراجعة العرض التقديمي. قراءة/كتابة Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | يشير إلى وضع عرض مصغرة المستند. ضع هذا العنصر **true** لتمكين تحجيم مصغرة المستند إلى العرض. ضع هذا العنصر **false** لتمكين قص مصغرة المستند لإظهار الأقسام التي تناسب العرض فقط. قراءة/كتابة Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. قراءة/كتابة Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | يعيد العدد الإجمالي للشرائح في مستند عرض تقديمي. قراءة فقط Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | يقوم بإرجاع أو تعيين موضوع العرض التقديمي. قراءة/كتابة String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | يقوم بإرجاع أو تعيين عنوان العرض التقديمي. قراءة/كتابة String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | يحدد عنوان كل جزء من المستند. هذه الأجزاء ليست أجزاء مستند فعلية بل تمثيلات مفهومية لأقسام المستند. قراءة فقط string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | الوقت الإجمالي للتحرير للعرض التقديمي. قراءة/كتابة TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | يعيد العدد الإجمالي للكلمات الموجودة في مستند. قراءة فقط Int32. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | يزيل جميع الخصائص المخصصة. |
| [Clone](../../aspose.slides/documentproperties/clone)() | ينسخ الكائن الحالي |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | ينسخ الكائن الحالي |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | يعيد اسم الخاصية المخصصة عند الفهرس المحدد. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | يحصل على قيمة منطقية مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | يحصل على قيمة DateTime مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | يحصل على قيمة double مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | يحصل على قيمة float مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | يحصل على قيمة عددية مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | يحصل على قيمة سلسلة مسماة من الخصائص المخصصة. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | يحصل على مصفوفة من تسميات الحساسية من الخصائص المخصصة للمستند (بيانات تعريف SDK لحماية المعلومات من مايكروسوفت). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | يزيل خاصية مخصصة مرتبطة باسم محدد. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | يضبط خاصية مخصصة منطقية مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | يضبط خاصية مخصصة من نوع DateTime مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | يضبط خاصية مخصصة من نوع double مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | يضبط خاصية مخصصة من نوع float مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | يضبط خاصية مخصصة من نوع integer مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | يضبط خاصية مخصصة من نوع string مسماة. |

### أمثلة

يوضح المثال التالي كيفية الوصول إلى الخصائص المدمجة لعرض PowerPoint.

```csharp
[C#]
// إنشاء كائن من الفئة Presentation التي تمثل العرض التقديمي
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

يوضح المثال التالي كيفية تعديل الخصائص المدمجة لعرض PowerPoint.

```csharp
[C#]
// إنشاء كائن من الفئة Presentation التي تمثل العرض التقديمي
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
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->