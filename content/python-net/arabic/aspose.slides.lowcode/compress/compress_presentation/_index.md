---
title: compress_presentation method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
يقلل حجم العرض التقديمي عن طريق تطبيق جميع خطوات الضغط المتاحة:
            
* يزيل الشرائح الرئيسة غير المستخدمة **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* يزيل الشرائح التخطيطية غير المستخدمة **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* يبقي فقط الرموز المستخدمة فعليًا في الخطوط المدمجة **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* يخفض دقة الصورة إلى 150 DPI ويحذف المناطق المقتصة من الصور **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المراد ضغطه. |

### ملاحظات

لتخصيص عملية الضغط، على سبيل المثال لاستخدام دقة صورة مختلفة أو لتجاوز خطوة، استدعِ الطرق المذكورة أعلاه بشكل فردي بدلاً من هذه الطريقة. المناطق المقتصة من الصور تُحذف بشكل دائم ولا يمكن استعادتها في PowerPoint.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` هو `None`. |



### انظر أيضًا
* الفئة [`Compress`](/slides/python-net/ar/aspose.slides.lowcode/compress)
* الفئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* الوحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* المكتبة [`Aspose.Slides`](/slides/python-net)