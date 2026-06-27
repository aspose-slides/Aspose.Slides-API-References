---
title: Hyperlink
second_title: Aspose.Sildes for .NET API Referansı
description: Bir hiperbağlantıyı temsil eder.
type: docs
weight: 5100
url: /tr/aspose.slides/hyperlink/
---
## Hyperlink sınıfı

Bir hiperbağlantıyı temsil eder.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Belirli bir slayta işaret eden bir hiperbağlantı örneği oluşturur. Not: Oluşturulan hiperbağlantı aynı sunumdaki bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir. |
| [Hyperlink](hyperlink#constructor_2)(string) | Bir hiperbağlantı örneği oluşturur. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Başka bir hiperbağlantıyı kaynak olarak kullanarak, ikincil özellikleri geçersiz kılan bir hiperbağlantı örneği oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Sunumu sonlandıran bir hiperbağlantı döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Sunumun ilk slaydına bir hiperbağlantı döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Sunumun son slaydına bir hiperbağlantı döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Son görüntülenen slayta bir hiperbağlantı döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Özel bir "medya dosyasını oynat" hiperbağlantısını döndürür. AudioFrame ve VideoFrame içinde kullanılır. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Sonraki slayta bir hiperbağlantı döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Özel bir "hiçbir şey yapma" hiperbağlantısını döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Önceki slayta bir hiperbağlantı döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Hyperlink'in eylem türünü döndürür. Yalnızca okunabilir [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimine erişim sağlar. Yalnızca okunabilir [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Hipertablon renginin kaynağını temsil eder - ya stiller ya da bölüm biçimi. Okunabilir/yazılabilir [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Harici URL'yi belirtir. Yalnızca okunabilir String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Bu bölüm için, bölümün gerçek içeriği dikkate alınmadan ayarlanmış bir hiperbağlantıyı temsil eder. PowerPoint, bir bölümdeki bağlantılar ve ilgili metin için özel davranır. Bağlantı için gerçek adresinden farklı geçerli bir URL biçiminde metin oluşturulmasına izin verir. Bu durumda, düzenleme penceresinde bağlantıyı görüntülediğinizde, metin bölümüne uyması için değiştirilir. Bu özellik, hiperbağlantının orijinal değerini temsil eder. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Hiperbağlantının tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunabilir/yazılabilir Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Üst hiperbağlantının hedefinin, çağrıldığında görüntülenen hiperbağlantılar listesine eklenip eklenmeyeceğini belirler. Okunabilir/yazılabilir Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Hiperbağlantının oynatılan sesini temsil eder. Okunabilir/yazılabilir [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Sesin hiperbağlantı tıklandığında durdurulup durdurulmayacağını belirler. Okunabilir/yazılabilir Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Üst hiperbağlantının hedefi mevcut olduğunda, üst HTML çerçeve kümesindeki çerçeveyi döndürür. Okunabilir/yazılabilir String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Hyperlink belirli bir slayta hedeflendiğinde bu slaytı döndürür. Yalnızca okunabilir [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Üst hiperbağlantı ile ilişkilendirilen ve kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunabilir/yazılabilir String. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Belirli bir tür için bir karma işlevi görevi görür; karma algoritmaları ve hash tablo gibi veri yapılarında kullanılmaya uygundur. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | İki hiperbağlantıyı eşitlik açısından test eder. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | İki hiperbağlantıyı eşitsizlik açısından test eder. |

### İlgili

* sınıf [PVIObject](../pviobject)
* arayüz [IHyperlink](../ihyperlink)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->