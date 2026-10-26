---
title: IHyperlink class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ihyperlink/
---
## IHyperlink sınıfı

Bir köprüyü temsil eder.

IHyperlink türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/tr/aspose.slides/ihyperlink/action_type/) | HyperLinkEx'in eylem türünü döndürür.<br/>            Salt okunur [`HyperlinkActionType`](/slides/python-net/tr/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/tr/aspose.slides/ihyperlink/external_url/) | Harici URL'yi belirtir<br/>            Bu özellik None olmaktan çıkar ise TargetSlide özelliği None olur.<br/>            Salt okunur **str**. |
| [`external_url_original`](/slides/python-net/tr/aspose.slides/ihyperlink/external_url_original/) | Bu bölüm için ayarlanan, bölümün gerçek içeriği dikkate alınmadan bir hiperbağ'ı temsil eder.<br/>            <br/>            PowerPoint, bir bölümdeki bağlantılar ve ilgili metinler için özel bir şekilde davranır. Bağlantı için geçerli bir URL biçiminde metin oluşturulmasına izin verir, bu da bağlantının gerçek adresinden farklıdır. Bu durumda, düzenleme penceresinde bağlantıyı görüntülediğinizde, metin bölümüne uygun şekilde değiştirilecektir. Bu özellik, hiperbağ'ın orijinal değerini temsil eder. |
| [`target_slide`](/slides/python-net/tr/aspose.slides/ihyperlink/target_slide/) | HyperlinkEx belirli bir slaytı hedefliyorsa bu slaytı döndürür.<br/>            Özellik None olmaktan çıkar ise ExternalUrl özelliği None olur.<br/>            Salt okunur [`ISlide`](/slides/python-net/tr/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/tr/aspose.slides/ihyperlink/target_frame/) | Üst hiperbağın hedefi için, mevcut olduğunda üst HTML çerçeve kümesindeki çerçeveyi döndürür.<br/>            Okunur/yazılabilir **str**. |
| [`tooltip`](/slides/python-net/tr/aspose.slides/ihyperlink/tooltip/) | Üst hiperbağ ile ilişkili olarak bir kullanıcı arabiriminde gösterilebilecek dizeyi döndürür.<br/>            Okunur/yazılabilir **str**. |
| [`history`](/slides/python-net/tr/aspose.slides/ihyperlink/history/) | Üst hiperbağın hedefinin, çağrıldığında görüntülenen hiperbağlar listesine eklenip eklenmeyeceğini belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`highlight_click`](/slides/python-net/tr/aspose.slides/ihyperlink/highlight_click/) | Hiperbağın tıklandığında vurgulanıp vurgulanmayacağını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`stop_sound_on_click`](/slides/python-net/tr/aspose.slides/ihyperlink/stop_sound_on_click/) | Hiperbağ tıklandığında sesin durdurulup durdurulmayacağını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`sound`](/slides/python-net/tr/aspose.slides/ihyperlink/sound/) | Hiperbağın çalan sesini temsil eder.<br/>            Okunur/yazılabilir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/tr/aspose.slides/ihyperlink/color_source/) | Hiperbağ renginin kaynağını temsil eder - ya stiller ya da bölüm biçimi.<br/>            Okunur/yazılabilir [`HyperlinkColorSource`](/slides/python-net/tr/aspose.slides/hyperlinkcolorsource). |

## Yöntemler

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/tr/aspose.slides/ihyperlink/equals/#ihyperlink) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |

### Diğer Bağlantılar
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)