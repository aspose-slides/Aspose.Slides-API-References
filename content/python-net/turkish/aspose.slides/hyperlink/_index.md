---
title: Hyperlink class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/hyperlink/
---
## Hyperlink sınıfı

Bir köprüyi temsil eder.

**Inheritance:**[`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/tr/aspose.slides/pviobject)

The Hyperlink type exposes the following members:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/tr/aspose.slides/hyperlink/__init__/#str) | Bir köprünün bir örneğini oluşturur. |
| [`__init__(self, slide)`](/slides/python-net/tr/aspose.slides/hyperlink/__init__/#islide) | Belirli bir slayta işaret eden bir köprünün örneğini oluşturur.<br/>            Not: oluşturulan köprü aynı sunumdan bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/tr/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Başka bir köprüyü kaynak olarak kullanarak, ikincil özellikleri geçersiz kılan bir köprünün örneğini oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`no_action`](/slides/python-net/tr/aspose.slides/hyperlink/no_action/) | "hiçbir şey yapmayan" özel bir köprüyü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/tr/aspose.slides/hyperlink/media/) | "medya dosyası çal" özel bir köprüyü döndürür. AudioFrame ve VideoFrame içinde kullanılır.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/tr/aspose.slides/hyperlink/next_slide/) | Sonraki slayta bir köprü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/tr/aspose.slides/hyperlink/previous_slide/) | Önceki slayta bir köprü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/tr/aspose.slides/hyperlink/first_slide/) | Sunumun ilk slaytına bir köprü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/tr/aspose.slides/hyperlink/last_slide/) | Sunumun son slaytına bir köprü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/tr/aspose.slides/hyperlink/last_vieved_slide/) | Son görüntülenen slayta bir köprü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/tr/aspose.slides/hyperlink/end_show/) | Gösteriyi sonlandıran bir köprü döndürür.<br/>            Yalnızca okuma [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/tr/aspose.slides/hyperlink/action_type/) | Hyperlink'in eylem tipini döndürür.<br/>            Yalnızca okuma [`HyperlinkActionType`](/slides/python-net/tr/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/tr/aspose.slides/hyperlink/external_url/) | Dış URL'yi belirtir.<br/>            Yalnızca okuma **str**. |
| [`target_slide`](/slides/python-net/tr/aspose.slides/hyperlink/target_slide/) | Hyperlink belirli bir slaytı hedefliyorsa bu slaytı döndürür.<br/>            Yalnızca okuma [`ISlide`](/slides/python-net/tr/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/tr/aspose.slides/hyperlink/external_url_original/) | Bu bölüme, bölümün gerçek içeriğine bakılmaksızın ayarlanmış bir köprüyü temsil eder.<br/>            <br/>            PowerPoint, bir bölümdeki bağlantılar ve buna karşılık gelen metin için özel davranır. Bağlantı için geçerli bir URL biçiminde metin oluşturulmasına izin verir, bu gerçek bağlantı adresinden farklıdır. Bu durumda, düzenleme penceresinde bağlantıyı görüntülediğinizde, metin bölümüne uyması için değiştirilecektir. Bu özellik, köprünün orijinal değerini temsil eder. |
| [`target_frame`](/slides/python-net/tr/aspose.slides/hyperlink/target_frame/) | Var olduğunda, ana hyperlink'in hedefi için ana HTML çerçeve kümesindeki çerçeveyi döndürür.<br/>            Okunabilir/Yazılabilir **str**. |
| [`tooltip`](/slides/python-net/tr/aspose.slides/hyperlink/tooltip/) | Ana hyperlink ile ilişkili olarak bir kullanıcı arayüzünde gösterilebilecek dizeyi döndürür.<br/>            Okunabilir/Yazılabilir **str**. |
| [`history`](/slides/python-net/tr/aspose.slides/hyperlink/history/) | Ana hyperlink'in hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler.<br/>            Okunabilir/Yazılabilir **bool**. |
| [`highlight_click`](/slides/python-net/tr/aspose.slides/hyperlink/highlight_click/) | Köprünün tıklandığında vurgulanıp vurgulanmayacağını belirler.<br/>            Okunabilir/Yazılabilir **bool**. |
| [`stop_sound_on_click`](/slides/python-net/tr/aspose.slides/hyperlink/stop_sound_on_click/) | Köprünün tıklandığında sesin durdurulup durdurulmayacağını belirler.<br/>            Okunabilir/Yazılabilir **bool**. |
| [`sound`](/slides/python-net/tr/aspose.slides/hyperlink/sound/) | Köprünün çalan sesini temsil eder.<br/>            Okunabilir/Yazılabilir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/tr/aspose.slides/hyperlink/color_source/) | Köprü renginin kaynağını temsil eder - stil ya da bölüm formatı.<br/>            Okunabilir/Yazılabilir [`HyperlinkColorSource`](/slides/python-net/tr/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/tr/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/hyperlink/presentation/) |  |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/tr/aspose.slides/hyperlink/equals/#ihyperlink) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |

### İlgili
* sınıf [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink)
* sınıf [`PVIObject`](/slides/python-net/tr/aspose.slides/pviobject)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)