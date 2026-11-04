---
title: DocumentProperties
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل خصائص عرض تقديمي.
type: docs
weight: 2810
url: /ar/aspose.slides/documentproperties/
---
## فئة DocumentProperties

يمثل خصائص عرض تقديمي.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocumentProperties](documentproperties)() | يهيئ مثالًا جديدًا من الفئة [`DocumentProperties`](../documentproperties). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | يعيد أو يعيّن القالب الخاص بالتطبيق. قابل للقراءة والكتابة String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | يعيد نسخة التطبيق. قراءة فقط String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | يعيد أو يعيّن مؤلف العرض التقديمي. قابل للقراءة والكتابة String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | يعيد أو يعيّن فئة العرض التقديمي. قابل للقراءة والكتابة String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | يعيد أو يعيّن تعليقات العرض التقديمي. قابل للقراءة والكتابة String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | يعيد أو يعيّن خاصية الشركة. قابل للقراءة والكتابة String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | يعيد أو يعيّن حالة محتوى العرض التقديمي. قابل للقراءة والكتابة String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | يعيد أو يعيّن نوع محتوى العرض التقديمي. قابل للقراءة والكتابة String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | يعيد عدد الخصائص المخصصة الفعلية الموجودة في المجموعة. قراءة فقط Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | يعيد تاريخ إنشاء العرض التقديمي. القيم بالتوقيت العالمي UTC. قابل للقراءة والكتابة DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | يوضح تجميع أجزاء المستند وعدد الأجزاء في كل مجموعة. قراءة فقط IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | يعيد عدد الشرائح المخفية في مستند العرض التقديمي. قراءة فقط Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | يعيد أو يعيّن خاصية HyperlinkBase للمستند. قابل للقراءة والكتابة String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | يحدد أن أحد الروابط أو أكثر في هذا الجزء تم تحديثه حصيًا في هذا الجزء بواسطة منتج. سيقوم المنتج التالي بفتح هذا المستند بتحديث علاقات الروابط بالروابط الجديدة المحددة في هذا الجزء. قابل للقراءة والكتابة Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | يعيد أو يعيّن الخاصية المخصصة المرتبطة باسم محدد. قابل للقراءة والكتابة Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | يعيد أو يعيّن كلمات مفتاح العرض التقديمي. قابل للقراءة والكتابة String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | يعيد تاريخ آخر طباعة للعرض التقديمي. قابل للقراءة والكتابة DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | يعيد أو يعيّن اسم آخر شخص عدّل العرض التقديمي. قابل للقراءة والكتابة String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | يعيد تاريخ آخر تعديل للعرض التقديمي. القيم بالتوقيت العالمي UTC. قراءة فقط في حالة Presentation.DocumentProperties (لأنها تُحدَّث داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties يعود به الأسلوب [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). يرجى الاطلاع على المثال في ملخص الأسلوب [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | يوضح ما إذا كانت الروابط في المستند حديثة. ضع هذا العنصر على **true** للدلالة على أن الروابط محدثة. ضع هذا العنصر على **false** للدلالة على أن الروابط قديمة. قابل للقراءة والكتابة Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | يعيد أو يعيّن خاصية المدير. قابل للقراءة والكتابة String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | يعيد إجمالي عدد مقاطع الصوت أو الفيديو الموجودة في المستند. قراءة فقط Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | يعيد أو يعيّن اسم التطبيق. قابل للقراءة والكتابة String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | يعيد عدد الشرائح التي تحتوي على ملاحظات في العرض التقديمي. قراءة فقط Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | يعيد إجمالي عدد الفقرات الموجودة في المستند إذا كان ذلك مناسبًا. قراءة فقط Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | يعيد أو يعيّن الصيغة المستهدفة للعرض التقديمي. قابل للقراءة والكتابة String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | يعيد أو يعيّن رقم مراجعة العرض التقديمي. قابل للقراءة والكتابة Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | يوضح وضع عرض مصغرة المستند. ضع هذا العنصر على **true** لتمكين تحجيم مصغرة المستند لتلائم العرض. ضع هذا العنصر على **false** لتمكين قص مصغرة المستند لإظهار الأقسام التي تناسب العرض فقط. قابل للقراءة والكتابة Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | يحدد ما إذا كان العرض التقديمي مشتركًا بين عدة أشخاص. قابل للقراءة والكتابة Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | يعيد إجمالي عدد الشرائح في مستند العرض التقديمي. قراءة فقط Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | يعيد أو يعيّن موضوع العرض التقديمي. قابل للقراءة والكتابة String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | يعيد أو يعيّن عنوان العرض التقديمي. قابل للقراءة والكتابة String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | يحدد عنوان كل جزء من المستند. هذه الأجزاء ليست أجزاء مستند فعلية وإنما تمثيلات مفاهيمية لأقسام المستند. قراءة فقط string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | إجمالي وقت تحرير العرض التقديمي. قابل للقراءة والكتابة TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | يعيد إجمالي عدد الكلمات الموجودة في المستند. قراءة فقط Int32. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | يمسح ويضبط القيم الافتراضية لجميع الخصائص المدمجة. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | يزيل جميع الخصائص المخصصة. |
| [Clone](../../aspose.slides/documentproperties/clone)() | ينسخ الكائن الحالي |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | ينسخ الكائن الحالي |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | يتحقق من وجود خاصية مخصصة بالاسم المحدد. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | يرجع اسم خاصية مخصصة عند الفهرس المحدد. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | يحصل على قيمة منطقية مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | يحصل على قيمة DateTime مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | يحصل على قيمة مزدوجة مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | يحصل على قيمة عائمة مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | يحصل على قيمة عدد صحيح مسماة من الخصائص المخصصة. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | يحصل على قيمة سلسلة مسماة من الخصائص المخصصة. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | يزيل خاصية مخصصة مرتبطة باسم محدد. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | يعيّن خاصية منطقية مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | يعيّن خاصية DateTime مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | يعيّن خاصية مزدوجة مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | يعيّن خاصية عائمة مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | يعيّن خاصية عدد صحيح مخصصة مسماة. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | يعيّن خاصية سلسلة مخصصة مسماة. |

### الأمثلة

يوضح المثال التالي كيف يمكن الوصول إلى الخصائص المدمجة لعرض PowerPoint.

```csharp
[C#]
// إنشاء كائن من فئة Presentation الذي يمثل العرض التقديمي
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

يوضح المثال التالي كيف يمكن تعديل الخصائص المدمجة لعرض PowerPoint.

```csharp
[C#]
// إنشاء كائن من فئة Presentation الذي يمثل العرض التقديمي
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// إنشاء مرجع إلى كائن IDocumentProperties المرتبط بالعرض التقديمي
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// ضبط الخصائص المدمجة
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// حفظ العرض التقديمي إلى ملف
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### المزيد

* واجهة [IDocumentProperties](../idocumentproperties)
* واجهة [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->