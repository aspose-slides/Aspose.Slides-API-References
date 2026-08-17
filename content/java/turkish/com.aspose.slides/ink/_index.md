---
title: Ink
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytta mürekkep nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/ink/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Bir slayt üzerindeki mürekkep nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTraces()](#getTraces--) | IInk öğesinde bulunan tüm izleri alır [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Mürekkep fırçaları için görsel efektleri taklit etmek amacıyla kullanılan özel görüntülerin koleksiyonunu alır. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

IInk öğesinde bulunan tüm izleri alır [IInkTrace](../../com.aspose.slides/iinktrace). Salt okunur.

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

Mürekkep fırçaları için görsel efektleri taklit etmek amacıyla kullanılan özel görüntülerin koleksiyonunu alır. Bu görüntüler, Galaxy, Rainbow vb. gibi belirli [InkEffectType](../../com.aspose.slides/inkeffecttype) değerleriyle mürekkep işlenirken kullanılır. Kendi görüntülerinizi sağlayarak her mürekkep efektinin nasıl görüneceğini kontrol edebilirsiniz.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Bu özellik, varsayılan mürekkep efekti dokularını kullanıcı tanımlı olanlarla değiştirmeye olanak tanır; bu, varsayılan varlıkların lisans sınırlamaları nedeniyle kullanılamadığı ya da çalışma zamanında mevcut olmadığı durumlarda özellikle yararlıdır. Sözlükteki her giriş, bir [InkEffectType](../../com.aspose.slides/inkeffecttype) değerini ilgili bir [IImage](../../com.aspose.slides/iimage) nesnesiyle (ör. Bitmap veya bir Aspose görüntü arabirimi) eşleştirmelidir.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>