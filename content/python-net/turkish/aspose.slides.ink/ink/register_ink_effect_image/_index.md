---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Bir görseli, mürekkep fırçaları için görsel efektleri simüle etmek amacıyla kullanılan özel görseller koleksiyonuna kaydeder.
Bu görseller, mürekkebi belirli [`InkEffectType`](/slides/python-net/tr/aspose.slides.ink/inkeffecttype) değerleriyle işlerken kullanılır,
örneğin Galaxy, Rainbow vb. Kendi görsellerinizi sağlayarak her bir mürekkep efektinin nasıl görüneceğini kontrol edebilirsiniz.

```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/tr/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/tr/aspose.slides/iimage) |  |

### Açıklamalar

Bu yöntem, varsayılan mürekkep efekti dokularını kullanıcı tanımlı olanlarla değiştirmeyi sağlar, bu özellikle varsayılan varlıklar lisans nedeniyle kısıtlı olduğunda veya çalışma zamanında mevcut olmadığında faydalıdır. Kayıtlı her değer çifti bir [`InkEffectType`](/slides/python-net/tr/aspose.slides.ink/inkeffecttype) değerini ilgili bir [`IImage`](/slides/python-net/tr/aspose.slides/iimage) nesnesiyle (ör. Bitmap veya bir Aspose görüntü arayüzü) ilişkilendirmelidir.

### Diğer Bağlantılar
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* sınıf [`Ink`](/slides/python-net/tr/aspose.slides.ink/ink)
* enumeration [`InkEffectType`](/slides/python-net/tr/aspose.slides.ink/inkeffecttype)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)