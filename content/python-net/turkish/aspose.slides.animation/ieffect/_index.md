---
title: IEffect class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/ieffect/
---
## IEffect sınıfı

Animasyon etkisini temsil eder.

IEffect türü aşağıdaki üyeleri ortaya koyar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`sequence`](/slides/python-net/tr/aspose.slides.animation/ieffect/sequence/) | Bir etki için bir dizi döndürür.<br/>            Yalnızca okunur [`ISequence`](/slides/python-net/tr/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/tr/aspose.slides.animation/ieffect/text_animation/) | Metin animasyonunu döndürür.<br/>            Yalnızca okunur [`ITextAnimation`](/slides/python-net/tr/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/tr/aspose.slides.animation/ieffect/preset_class_type/) | Etkinin sınıfını tanımlar.<br/>            Okunur/yazılabilir [`EffectPresetClassType`](/slides/python-net/tr/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/tr/aspose.slides.animation/ieffect/type/) | Etkinin türünü tanımlar.<br/>            Okunur/yazılabilir [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/tr/aspose.slides.animation/ieffect/subtype/) | Etkinin alt türünü tanımlar.<br/>            Okunur/yazılabilir [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/tr/aspose.slides.animation/ieffect/behaviors/) | Etkinin davranış koleksiyonunu döndürür.<br/>            Okunur/yazılabilir [`IBehaviorCollection`](/slides/python-net/tr/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/tr/aspose.slides.animation/ieffect/timing/) | Etkinin zamanlama değerini tanımlar.<br/>            Okunur/yazılabilir [`ITiming`](/slides/python-net/tr/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/tr/aspose.slides.animation/ieffect/target_shape/) | Etkinin hedef şekli döndürür.<br/>            Yalnızca okunur [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`sound`](/slides/python-net/tr/aspose.slides.animation/ieffect/sound/) | Etkin için gömülü sesi tanımlar.<br/>            Okunur/yazılabilir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/tr/aspose.slides.animation/ieffect/stop_previous_sound/) | Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmadığını belirtir.<br/>            Okunur/yazılabilir **bool**. |
| [`after_animation_type`](/slides/python-net/tr/aspose.slides.animation/ieffect/after_animation_type/) | Etkin için bir sonrası animasyon türünü tanımlar.<br/>            Okunur/yazılabilir [`IEffect.after_animation_type`](/slides/python-net/tr/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/tr/aspose.slides.animation/ieffect/after_animation_color/) | Etkin için bir sonrası animasyon rengini tanımlar.<br/>            Okunur/yazılabilir [`IColorFormat`](/slides/python-net/tr/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/tr/aspose.slides.animation/ieffect/animate_text_type/) | Etkin için bir animasyon metin türü tanımlar. <br/>            Şekil metni harf, kelime veya tümü birden animasyon yapılabilir.<br/>            Okunur/yazılabilir [`IEffect.animate_text_type`](/slides/python-net/tr/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/tr/aspose.slides.animation/ieffect/delay_between_text_parts/) | Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar.<br/>            Pozitif bir değer, etki süresinin yüzdesini belirtir.<br/>            Negatif bir değer, gecikmeyi saniye cinsinden belirtir.<br/>            Okunur/yazılabilir **float**. |

### Bakınız
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)