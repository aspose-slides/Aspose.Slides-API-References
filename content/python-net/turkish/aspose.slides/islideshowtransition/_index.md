---
title: ISlideShowTransition class
second_title: Aspose.Slides for Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islideshowtransition/
---
## ISlideShowTransition sınıfı

Slayt gösterisi geçişini temsil eder.

ISlideShowTransition türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/tr/aspose.slides/islideshowtransition/sound/) | Gömülü ses verilerini döndürür veya ayarlar.<br/>            Okuma-yazma [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/tr/aspose.slides/islideshowtransition/sound_mode/) | Slayt geçişi için ses modunu ayarlar veya döndürür.<br/>            Okuma-yazma [`TransitionSoundMode`](/slides/python-net/tr/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/tr/aspose.slides/islideshowtransition/sound_loop/) | Bu öznitelik, sesin bir sonraki ses etkinliği gerçekleşene kadar döngüde olup olmayacağını belirtir.<br/>            Okuma-yazma **bool**. |
| [`advance_on_click`](/slides/python-net/tr/aspose.slides/islideshowtransition/advance_on_click/) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirler. Bu öznitelik belirtilmemişse, true değeri varsayılır.<br/>            Okuma-yazma **bool**. |
| [`advance_after`](/slides/python-net/tr/aspose.slides/islideshowtransition/advance_after/) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir.<br/>            Okuma/yazma **bool**. |
| [`advance_after_time`](/slides/python-net/tr/aspose.slides/islideshowtransition/advance_after_time/) | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar, advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmemişse, otomatik ilerlemenin olmayacağı varsayılır.<br/>            Okuma-yazma **int**. |
| [`speed`](/slides/python-net/tr/aspose.slides/islideshowtransition/speed/) | Mevcut slayttan sonraki slayta geçerken kullanılacak geçiş hızını belirtir.<br/>            Okuma-yazma [`TransitionSpeed`](/slides/python-net/tr/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/tr/aspose.slides/islideshowtransition/value/) | Slayt gösterisi geçiş değeri.<br/>            Salt-okunur [`ITransitionValueBase`](/slides/python-net/tr/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/tr/aspose.slides/islideshowtransition/type/) | Geçiş türü.<br/>            Okuma-yazma [`TransitionType`](/slides/python-net/tr/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/tr/aspose.slides/islideshowtransition/sound_is_built_in/) | Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, üreten uygulama bu ses için yerleşik sesler listesindeki name özniteliğini kontrol etmesi gerektiği konusunda uyarılır ve gerektiğinde özel bir isim veya kullanıcı arayüzü gösterebilir.<br/>            Okuma-yazma **bool**. |
| [`sound_name`](/slides/python-net/tr/aspose.slides/islideshowtransition/sound_name/) | Geçiş sesinin insanlar tarafından okunabilir bir adını belirtir. Ses adını almak veya ayarlamak için [`ISlideShowTransition.sound`](/slides/python-net/tr/aspose.slides/islideshowtransition/sound) özelliği atanmalıdır.<br/>            Okuma-yazma **str**. |
| [`duration`](/slides/python-net/tr/aspose.slides/islideshowtransition/duration/) | Slayt geçiş etkisinin süresini milisaniye cinsinden alır veya ayarlar.<br/>            Okuma/yazma **int**. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)