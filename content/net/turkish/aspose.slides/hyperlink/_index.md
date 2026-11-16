---
title: Hyperlink
second_title: Aspose.Sildes için .NET API Referansı
description: Bir hyperlink'i temsil eder.
type: docs
weight: 5140
url: /tr/aspose.slides/hyperlink/
---
## Hyperlink sınıfı

Bir Hyperlink'i temsil eder.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Belirli bir slayta işaret eden bir hyperlink örneği oluşturur. Not: oluşturulan hyperlink aynı sunumdaki bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir. |
| [Hyperlink](hyperlink#constructor_2)(string) | Bir hyperlink örneği oluşturur. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Başka bir hyperlink'i kaynak olarak kullanarak, ikincil özellikleri geçersiz kılan bir hyperlink örneği oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Gösteriyi sonlandıran bir hyperlink döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Sunumun ilk slaytına bir hyperlink döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Sunumun son slaytına bir hyperlink döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Son görüntülenen slayta bir hyperlink döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Özel bir "medya dosyasını oynat" hyperlink'i döndürür. AudioFrame ve VideoFrame içinde kullanılır. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Sonraki slayta bir hyperlink döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Özel bir "hiçbir şey yapma" hyperlink'i döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Önceki slayta bir hyperlink döndürür. Yalnızca okunabilir [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Hyperlink'in eylem türünü döndürür. Yalnızca okunabilir [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Yalnızca okunabilir [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Hyperlink renginin kaynağını temsil eder – stil veya bölüm biçimi. Okunabilir/yazılabilir [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Harici URL'yi belirtir. Yalnızca okunabilir String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Bu bölümün gerçek içeriği dikkate alınmadan ayarlanan bir hyperlink'i temsil eder. PowerPoint, bölümlerdeki bağlantılar ve karşılık gelen metin için özel davranır. Geçerli bir URL biçiminde hyperlink metni oluşturmanıza izin verir, bu gerçek adresten farklıdır. Bu durumda, düzenleme penceresinde bağlantıyı görüntülediğinizde, metin bölümüne göre değiştirilir. Bu özellik hyperlink'in orijinal değerini temsil eder. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Hyperlink'in tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunabilir/yazılabilir Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Üst hyperlink'in hedefinin, çağrıldığında görüntülenmiş hyperlink listesine eklenip eklenmeyeceğini belirler. Okunabilir/yazılabilir Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Hyperlink'in çalan sesini temsil eder. Okunabilir/yazılabilir [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Sesin hyperlink tıklandığında durdurulup durdurulmayacağını belirler. Okunabilir/yazılabilir Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Üst hyperlink'in hedefi mevcut olduğunda, üst HTML çerçeve seti içinde hedef çerçeveyi döndürür. Okunabilir/yazılabilir String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Hyperlink belirli bir slaytı hedefliyorsa bu slaytı döndürür. Yalnızca okunabilir [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Üst hyperlink ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunabilir/yazılabilir String. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Belirli bir tür için bir karma işlevi sağlar; hash tabloları gibi veri yapılarında kullanılmak üzere uygundur. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | İki hyperlink'in eşitliğini test eder. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | İki hyperlink'in eşitsizliğini test eder. |

### Ayrıca

* sınıf [PVIObject](../pviobject)
* arayüz [IHyperlink](../ihyperlink)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->