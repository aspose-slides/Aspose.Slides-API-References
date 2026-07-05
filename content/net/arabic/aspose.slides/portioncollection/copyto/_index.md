---
title: CopyTo
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: ينسخ عناصر ICollection إلى مصفوفة Array بدءًا من فهرس Array معين.
type: docs
weight: 70
url: /ar/aspose.slides/portioncollection/copyto/
---
## PortionCollection.CopyTo طريقة

ينسخ عناصر الـ ICollection إلى مصفوفة Array، بدءًا من فهرس Array معين.

```csharp
public void CopyTo(IPortion[] array, int arrayIndex)
```

| معامل | نوع | وصف |
| --- | --- | --- |
| array | IPortion[] | المصفوفة أحادية البُعد التي هي وجهة العناصر المنسوخة من ICollection. يجب أن تكون المصفوفة ذات فهارس تبدأ من الصفر. |
| arrayIndex | Int32 | الفهرس الذي يبدأ من الصفر في *array* حيث يبدأ النسخ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *array* هو null. |
| ArgumentOutOfRangeException | *arrayIndex* أصغر من 0. |
| ArgumentException | عدد العناصر في الـ ICollection المصدر أكبر من المساحة المتاحة من *arrayIndex* إلى نهاية *array* الوجهة. |

### انظر أيضا

* واجهة [IPortion](../../iportion)
* فئة [PortionCollection](../../portioncollection)
* مساحة اسم [Aspose.Slides](../../portioncollection)
* تجميع [Aspose.Slides](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldoccmd لـ Aspose.Slides.dll -->