---
title: Collect
second_title: Aspose.Slides for Android via Java API Referansı
description: Farklı türde model nesnelerini ...'den toplamak amaçlı bir yöntem grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/collect/
---
**Kalıtım:**
java.lang.Object
```
public class Collect
```

Farklı türde model nesnelerini [Presentation](../../com.aspose.slides/presentation)'den toplamak amacıyla tasarlanmış bir yöntem grubunu temsil eder.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... şekil biçimlendirmesini veya diğer özellikleri değiştirin
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Collect()](#Collect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) içindeki [Shape](../../com.aspose.slides/shape) tüm örneklerini toplar. |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


[Presentation](../../com.aspose.slides/presentation) içindeki [Shape](../../com.aspose.slides/shape) tüm örneklerini toplar.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // eğer şekil AutoShape ise, siyah katı bir kenarlık ekle
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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Şekilleri toplamak için Presentation |

**Dönüş:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Sunumda bulunan tüm şekillerin koleksiyonu