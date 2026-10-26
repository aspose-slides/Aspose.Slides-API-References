---
title: Ink
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل كائن حبر على الشريحة.
type: docs
url: /ar/com.aspose.slides/ink/
---
**التورّث:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

يمثِّل كائن حبر على الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTraces()](#getTraces--) | يحصل على جميع الآثار الموجودة في عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | يحصل على مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرشاة الحبر. |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


يحصل على جميع الآثار الموجودة في عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace). للقراءة فقط.

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


**الإرجاع:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


يحصل على مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرشاة الحبر. تُستخدم هذه الصور عند عرض الحبر بقيم [InkEffectType](../../com.aspose.slides/inkeffecttype) محددة، مثل Galaxy، Rainbow، إلخ. من خلال توفير صورك الخاصة، يمكنك التحكم في كيفية ظهور كل تأثير حبر.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

تتيح هذه الخاصية استبدال قوام تأثير الحبر الافتراضية بالأنسجة المعرّفة من قبل المستخدم، وهو أمر مفيد بشكل خاص عندما تكون الأصول الافتراضية مقيدة بواسطة الترخيص أو غير متوفرة أثناء التشغيل. يجب أن يرتبط كل إدخال في القاموس بقيمة [InkEffectType](../../com.aspose.slides/inkeffecttype) مع كائن [IImage](../../com.aspose.slides/iimage) المقابل (مثال: Bitmap، أو واجهة صورة Aspose).

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>