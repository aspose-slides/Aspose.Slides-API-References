---
title: MasterSlide
second_title: Aspose.Sildes for .NET API Referansı
description: Bir sunumdaki ana slaytı temsil eder.
type: docs
weight: 8030
url: /tr/aspose.slides/masterslide/
---
## MasterSlide sınıfı

Bir sunumdaki ana slaytı temsil eder.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Salt-okunur [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Gövde metninin stilini döndürür. Salt-okunur [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Salt-okunur [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verilerini döndürür. Salt-okunur [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Ana slayt için çizim kılavuzlarının koleksiyonunu döndürür. Salt-okunur [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Bu ana slayta bağlı en az bir slayt varsa true döndürür. Salt-okunur Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Ana slaytın HeaderFooter yöneticisini döndürür. Salt-okunur [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerdiği köprü bağlantılarına kolay erişim sağlar. Salt-okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür. Salt-okunur [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Bir ana slaydın adını döndürür ya da ayarlar. Okunur/yazılabilir String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Diğer bir metnin stilini döndürür. Salt-okunur [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Salt-okunur [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | İlgili ana slayd, bu ana slaytı izleyen tüm slaytlar silindiğinde silinir mi belirler. Not: Aspose.Slides hiçbir zaman kullanılmayan ana slaytı kendiliğinden kaldırmaz; kullanılmayan ana slaytları gerçekten kaldırmak için [`RemoveUnused`](../masterslidecollection/removeunused) çağırın. Okunur/yazılabilir Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Bir slaytın şekillerini döndürür. Salt-okunur [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman `false` döndürür. Okunur/yazılabilir Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Bir slaytın kimliğini döndürür. Salt-okunur UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Belirtilen slaytın bir slayt gösterisi sırasında nasıl ilerleyeceği hakkında bilgi içeren Transition nesnesini döndürür. Salt-okunur [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Tema yöneticisini döndürür. Salt-okunur [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Salt-okunur [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Başlık metninin stilini döndürür. Salt-okunur [`ITextStyle`](../itextstyle). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Mevcut ana slaytı temel alarak yeni bir ana slayt oluşturur, ona dış tema uygular ve oluşturulan ana slaytı tüm bağlı slaytlara uygular. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için etkili bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer, slaytın yapısı ve statik içeriğine dayanarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz kimlik değerlerini ve Tarih Yer Tutucusu'ndaki mevcut tarih değeri gibi dinamik içeriği dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip ilk şekli bulur. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Bu ana slayta bağlı tüm slaytları içeren bir dizi döndürür. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip runları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip runları birleştirir. |

### Ayrıca Bakınız

* sınıf [BaseSlide](../baseslide)
* arayüz [IMasterSlide](../imasterslide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->