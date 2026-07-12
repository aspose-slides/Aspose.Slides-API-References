---
title: Ink
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir slayttaki mürekkep nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/ink/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Bir slaytta mürekkep nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTraces()](#getTraces--) | IInk öğesindeki [IInkTrace](../../com.aspose.slides/iinktrace) içinde bulunan tüm izleri alır. |
| [getInkEffectImages()](#getInkEffectImages--) | Mürekkep fırçaları için görsel efektleri simüle etmek amacıyla kullanılan özel görüntülerin koleksiyonunu alır. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


IInk öğesindeki [IInkTrace](../../com.aspose.slides/iinktrace) içinde bulunan tüm izleri alır. Salt-okunur.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Mürekkep fırçaları için görsel efektleri simüle etmek amacıyla kullanılan özel görüntülerin koleksiyonunu alır. Bu görüntüler, Galaxy, Rainbow gibi belirli [InkEffectType](../../com.aspose.slides/inkeffecttype) değerleriyle mürekkep renderlandığında kullanılır. Kendi görüntülerinizi sağlayarak her bir mürekkep efektinin nasıl göründüğünü kontrol edebilirsiniz.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Bu özellik, varsayılan mürekkep efekt dokularını kullanıcı tanımlı olanlarla değiştirmeye olanak tanır; bu, varsayılan varlıklar lisans nedeniyle kısıtlandığında veya çalışma zamanında mevcut olmadığında özellikle faydalıdır. Sözlükteki her giriş, bir [InkEffectType](../../com.aspose.slides/inkeffecttype) değerini karşılık gelen bir [IImage](../../com.aspose.slides/iimage) nesnesiyle (ör. Bitmap veya bir Aspose resim arabirimi) ilişkilendirmelidir.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>