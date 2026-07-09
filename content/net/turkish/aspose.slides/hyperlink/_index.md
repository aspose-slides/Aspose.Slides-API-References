---
title: Hyperlink
second_title: Aspose.Sildes for .NET API Referansı
description: Bir hyperlink'i temsil eder.
type: docs
weight: 5120
url: /tr/aspose.slides/hyperlink/
---
## Hyperlink sınıfı

Bir hyperlink'i temsil eder.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Belirli bir slayta işaret eden bir hyperlink örneği oluşturur. Not: Oluşturulan hyperlink aynı sunumdan bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir. |
| [Hyperlink](hyperlink#constructor_2)(string) | Bir hyperlink örneği oluşturur. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Başka bir hyperlink'i kaynak olarak kullanarak ve ikincil özellikleri geçersiz kılarak bir hyperlink örneği oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Gösterimi sonlandıran bir hyperlink döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Sunumun ilk slaydına bir hyperlink döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Sunumun son slaydına bir hyperlink döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Son görüntülenen slayta bir hyperlink döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Özel bir "play mediafile" hyperlink'i döndürür. AudioFrame ve VideoFrame'de kullanılır. Salt okunur [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Sonraki slayta bir hyperlink döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Özel bir "do nothing" hyperlink'i döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Önceki slayta bir hyperlink döndürür. Salt okunur [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Hyperlink'in eylem tipini döndürür. Salt okunur [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimini almayı sağlar. Salt okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Hyperlink renginin kaynağını temsil eder - stil veya bölüm formatı. Okunur/yazılabilir [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Dış URL'yi belirtir. Salt okunur String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Bu bölüm için, bölümün gerçek içeriği dikkate alınmadan ayarlanan bir hyperlink'i temsil eder. PowerPoint, bir bölümdeki bağlantılar ve karşılık gelen metin için özel davranır. Bağlantının gerçek adresinden farklı geçerli bir URL biçiminde hyperlink için metin oluşturulmasını sağlar. Bu durumda, düzenleme penceresinde bağlantıyı görüntülediğinizde, metin bölümüne uyacak şekilde değiştirilecektir. Bu özellik hyperlink'in orijinal değerini temsil eder. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Hyperlink'in tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunur/yazılabilir Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Üst hyperlink'in hedefinin çağrıldığında görüntülenen hyperlink'ler listesine eklenip eklenmeyeceğini belirler. Okunur/yazılabilir Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Hyperlink'in çalan sesini temsil eder. Okunur/yazılabilir [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Hyperlink tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunur/yazılabilir Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Üst hyperlink'in hedefi mevcut olduğunda, üst HTML çerçeve seti içindeki çerçeveyi döndürür. Okunur/yazılabilir String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Hyperlink belirli bir slayta hedefleniyorsa bu slaytı döndürür. Salt okunur [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Kullanıcı arayüzünde üst hyperlink ile ilişkili olarak görüntülenebilecek dizeyi döndürür. Okunur/yazılabilir String. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Belirli bir tip için hash işlevi olarak hizmet eder; hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | İki hyperlink'in eşitliğini test eder. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | İki hyperlink'in eşitsizliğini test eder. |

### Ayrıca Bakınız

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->