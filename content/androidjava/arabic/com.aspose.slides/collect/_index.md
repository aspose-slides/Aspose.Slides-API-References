---
title: Collect
second_title: Aspose.Slides للأندرويد عبر مرجع Java API
description: يمثل مجموعة من الأساليب المقصود منها جمع كائنات النموذج من .
type: docs
url: /ar/com.aspose.slides/collect/
---
**الوراثة:**
java.lang.Object
```
public class Collect
```

يمثل مجموعةً من الأساليب المقصود منها جمع كائنات النموذج من أنواع مختلفة من [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... تغيير تنسيق الشكل أو خصائص أخرى
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Collect()](#Collect--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | يجمع جميع حالات [Shape](../../com.aspose.slides/shape) في [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


يجمع جميع حالات [Shape](../../com.aspose.slides/shape) في [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // إذا كان الشكل AutoShape، أضف حدًا صلبًا أسود
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض لجمع الأشكال |

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - مجموعة جميع الأشكال الموجودة في العرض