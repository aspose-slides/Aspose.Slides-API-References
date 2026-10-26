---
title: IMathBlockCollection
second_title: Aspose.Sildes لـ .NET مرجع API
description: مجموعة من كتل الرياضيات IMathBlock
type: docs
weight: 8150
url: /ar/aspose.slides.mathtext/imathblockcollection/
---
## IMathBlockCollection واجهة

```csharp
public interface IMathBlockCollection : IEnumerable<IMathBlock>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.mathtext/imathblockcollection/asienumerable) { get; } | يسمح بالحصول على واجهة IEnumerable الأساسية |
| [Count](../../aspose.slides.mathtext/imathblockcollection/count) { get; } | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط Int32. |
| [Item](../../aspose.slides.mathtext/imathblockcollection/item) { get; set; } | يحصل على العنصر في الفهرس المحدد. قراءة فقط [`IMathBlock`](../imathblock). |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.slides.mathtext/imathblockcollection/add)(IMathBlock) | يضيف IMathBlock إلى نهاية المجموعة. |
| [Clear](../../aspose.slides.mathtext/imathblockcollection/clear)() | يزيل جميع العناصر من المجموعة. |
| [Contains](../../aspose.slides.mathtext/imathblockcollection/contains)(IMathBlock) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [IndexOf](../../aspose.slides.mathtext/imathblockcollection/indexof)(IMathBlock) | يحدد فهرس IMathBlock معين في المجموعة. |
| [Insert](../../aspose.slides.mathtext/imathblockcollection/insert)(int, IMathBlock) | يدخل IMathBlock في المجموعة عند الفهرس المحدد. |
| [Remove](../../aspose.slides.mathtext/imathblockcollection/remove)(IMathBlock) | يزيل أول حدوث لكائن معين من المجموعة/&gt;. |
| [RemoveAt](../../aspose.slides.mathtext/imathblockcollection/removeat)(int) | يزيل عنصرًا عند الفهرس المحدد من المجموعة. |

### أمثلة

مثال:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
```

### انظر أيضًا

* واجهة [IMathBlock](../imathblock)
* مساحة الاسم [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* تجميع [Aspose.Slides](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ Aspose.Slides.dll -->