---
title: MasterSlide
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumdaki ana slaytı temsil eder.
type: docs
weight: 8050
url: /tr/aspose.slides/masterslide/
---
## MasterSlide sınıfı

Bir sunumda ana slaytı temsil eder.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Özellikler

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Salt-okunur [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Gövde metninin stilini döndürür. Salt-okunur [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Salt-okunur [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verilerini döndürür. Salt-okunur [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Ana slayt için çizim kılavuzlarının koleksiyonunu döndürür. Salt-okunur [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Bu ana slayta bağlı en az bir slayt varsa true döndürür. Salt-okunur Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Ana slaytın HeaderFooter yöneticisini döndürür. Salt-okunur [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerdiği köprülerin kolay erişimini sağlar. Salt-okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür. Salt-okunur [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Bir ana slaytın adını döndürür veya ayarlar. Okunur-yazılabilir String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Başka bir metnin stilini döndürür. Salt-okunur [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Salt-okunur [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | İlgili ana slayt, onu izleyen tüm slaytlar silindiğinde silinir mi belirler. Not: Aspose.Slides hiçbir zaman kullanılmayan bir ana slaytı kendi başına kaldırmaz; kullanılmayan ana slaytları gerçekten kaldırmak için [`RemoveUnused`](../masterslidecollection/removeunused) çağırın. Okunur-yazılabilir Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Bir slaytın şekillerini döndürür. Salt-okunur [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman `false` döndürür. Okunur-yazılabilir Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Bir slaytın kimliğini (ID) döndürür. Salt-okunur UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Belirtilen slaytın slayt gösterisi sırasında nasıl ilerleyeceği hakkında bilgi içeren Transition nesnesini döndürür. Salt-okunur [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Tema yöneticisini döndürür. Salt-okunur [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Salt-okunur [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Başlık metninin stilini döndürür. Salt-okunur [`ITextStyle`](../itextstyle). |

## Yöntemler

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Mevcut ana slayta dayanarak yeni bir ana slayt oluşturur, ona dış bir tema uygular ve oluşturulan ana slaytı tüm bağımlı slaytlara uygular. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için etkili bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer slaytın yapısı ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşit olduğunda iki slayt eşittir. Karşılaştırma benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Bu ana slayta bağımlı tüm slaytların bir dizisini döndürür. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |

### Ayrıca Bakınız

* sınıf [BaseSlide](../baseslide)
* arayüz [IMasterSlide](../imasterslide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->