---
title: SetGeometryPaths
second_title: Aspose.Sildes برای .NET مرجع API
description: ژئومتری شکل را از آرایه‌ای از IGeometryPathaspose.slides/igeometrypath به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل نسبت‌دار باشند. نوع شکل ShapeTypeaspose.slides/igeometryshape/shapetype را به Custom تغییر می‌دهد.
type: docs
weight: 80
url: /fa/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape.SetGeometryPaths متد

ژئومتری شکل را از آرایه‌ای از [`IGeometryPath`](../../igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل نسبت‌دار باشند. نوع شکل ([`ShapeType`](../shapetype)) را به Custom تغییر می‌دهد.

```csharp
public void SetGeometryPaths(IGeometryPath[] geometryPaths)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| geometryPaths | IGeometryPath[] | آرایه مسیرهای هندسی |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | مسیر یافت نشد |
| ArgumentException | مسیر خالی |

### نمونه‌ها

مثال:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    GeometryShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 200, 100) as GeometryShape;

    GeometryPath geometryPath = shape.GetGeometryPaths()[0];

    geometryPath.LineTo(100, 50, 1);
    geometryPath.LineTo(100, 50, 4);

    shape.SetGeometryPath(geometryPath);

    pres.Save("output.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [IGeometryPath](../../igeometrypath)
* رابط [IGeometryShape](../../igeometryshape)
* فضای نام [Aspose.Slides](../../igeometryshape)
* مجمع [Aspose.Slides](../../../)

<!-- ویرایش نکنید: توسط xmldocmd برای Aspose.Slides.dll تولید شده است -->