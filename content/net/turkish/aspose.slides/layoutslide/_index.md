---
title: LayoutSlide
second_title: Aspose.Sildes için .NET API Referansı
description: Bir yerleşim slaytını temsil eder.
type: docs
weight: 7640
url: /tr/aspose.slides/layoutslide/
---
## LayoutSlide sınıfı

Bir yerleşim slaytını temsil eder.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Salt okunur [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Bir slayttaki ActiveX kontrol koleksiyonunu döndürür. Salt okunur [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verilerini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Yerleşim slaytı için çizim kılavuzları koleksiyonunu döndürür. Salt okunur [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Bu yerleşim slaytına bağımlı en az bir slayt varsa true döndürür. Salt okunur Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Yerleşim slaytının HeaderFooter yöneticisini döndürür. Salt okunur [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerdiği hipermetin bağlantılarına kolay erişim sağlar. Salt okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Bu yerleşim slaytının yerleşim tipini döndürür. Salt okunur [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Bir yerleşim için ana slaytı döndürür veya ayarlar. Okunur/Yazılabilir [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Bir slaytın adını döndürür veya ayarlar. Okunur/Yazılabilir String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Yerleşim slaytının yer tutucu yöneticisini döndürür. Salt okunur [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Salt okunur [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Bir slaytın şekillerini döndürür. Salt okunur [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Okunur/Yazılabilir Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Bir slaytın kimliğini (ID) döndürür. Salt okunur UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Belirtilen slaytın slayt gösterisi sırasında nasıl ilerlediğiyle ilgili bilgileri içeren Transition nesnesini döndürür. Salt okunur [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Geçersiz kılan tema yöneticisini döndürür. Salt okunur [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Salt okunur [`IAnimationTimeLine`](../ianimationtimeline). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için etkili bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer, slaytın yapısı ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip ilk şekli bulur. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Bu yerleşim slaytına bağımlı tüm slaytları içeren bir dizi döndürür. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Tüm paragraf ve uygun şekillerde aynı biçimlendirmeye sahip run'ları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm uygun şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Yerleşimi sunumdan kaldırır. |

### Ayrıca Bakınız

* sınıf [BaseSlide](../baseslide)
* arayüz [ILayoutSlide](../ilayoutslide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->