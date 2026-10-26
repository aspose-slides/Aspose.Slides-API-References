---
title: Collect
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: نمایانگر گروهی از متدها است که برای جمع‌آوری اشیای مدل از انواع مختلف از . طراحی شده‌اند
type: docs
url: /fa/com.aspose.slides/collect/
---
**ارث‌بری:**
java.lang.Object
```
public class Collect
```

نمایشگر گروهی از متدها است که برای جمع‌آوری اشیای مدل از انواع مختلف از [Presentation](../../com.aspose.slides/presentation) طراحی شده‌اند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... قالب‌بندی شکل یا سایر ویژگی‌ها را تغییر دهید
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Collect()](#Collect--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | تمام نمونه‌های [Shape](../../com.aspose.slides/shape) را در [Presentation](../../com.aspose.slides/presentation) جمع‌آوری می‌کند. |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


تمام نمونه‌های [Shape](../../com.aspose.slides/shape) را در [Presentation](../../com.aspose.slides/presentation) جمع‌آوری می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // اگر شکل AutoShape باشد، یک حاشیه مشکی ثابت اضافه کنید
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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای جمع‌آوری اشکال |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - مجموعه‌ای از تمام شکل‌ها که در ارائه وجود دارد