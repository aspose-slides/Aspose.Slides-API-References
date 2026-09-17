---
title: register_ink_effect_image method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
يقوم بتسجيل صورة إلى مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرش الحبر.
            تُستخدم هذه الصور عند تصيير الحبر بقيم [`InkEffectType`](/slides/python-net/ar/aspose.slides.ink/inkeffecttype) محددة،
            مثل Galaxy وRainbow وغيرها. من خلال توفير صورك الخاصة، يمكنك التحكم في طريقة ظهور كل تأثير حبر.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/ar/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/ar/aspose.slides/iimage) |  |

### ملاحظات

تتيح هذه الطريقة استبدال الأنماط الافتراضية لتأثير الحبر بأنماط معرفة من قبل المستخدم،
            وهو أمر مفيد خصوصًا عندما تكون الأصول الافتراضية مقيدة بالترخيص أو غير متاحة أثناء التشغيل.
            يجب أن يرتبط كل زوج قيمة مسجل بقيمة [`InkEffectType`](/slides/python-net/ar/aspose.slides.ink/inkeffecttype) مع كائن [`IImage`](/slides/python-net/ar/aspose.slides/iimage) المقابل (مثال: Bitmap أو واجهة صورة Aspose).


### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* فئة [`Ink`](/slides/python-net/ar/aspose.slides.ink/ink)
* تعداد [`InkEffectType`](/slides/python-net/ar/aspose.slides.ink/inkeffecttype)
* وحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* مكتبة [`Aspose.Slides`](/slides/python-net)