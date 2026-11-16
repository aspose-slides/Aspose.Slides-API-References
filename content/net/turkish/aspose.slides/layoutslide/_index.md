---
title: LayoutSlide
second_title: Aspose.Sildes için .NET API Referansı
description: Bir düzen slaytını temsil eder.
type: docs
weight: 7660
url: /tr/aspose.slides/layoutslide/
---
## LayoutSlide sınıf

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Yalnızca okuma [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Yalnızca okuma [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verilerini döndürür. Yalnızca okuma [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Düzen slaytı için çizim kılavuzlarının koleksiyonunu döndürür. Yalnızca okuma [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. Yalnızca okuma Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Düzen slaytının HeaderFooter yöneticisini döndürür. Yalnızca okuma [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerilen köprülerin kolay erişimini sağlar. Yalnızca okuma [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Bu düzen slaytının düzen türünü döndürür. Yalnızca okuma [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Bir düzen için ana slaytı döndürür veya ayarlar. Okuma/yazma [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Bir slaytın adını döndürür veya ayarlar. Okuma/yazma String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Düzen slaytının yer tutucu yöneticisini döndürür. Yalnızca okuma [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Yalnızca okuma [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Bir slaytın şekillerini döndürür. Yalnızca okuma [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okuma/yazma Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Bir slaytın kimliğini (ID) döndürür. Yalnızca okuma UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Belirtilen slaytın bir slayt gösterisi sırasında nasıl ilerlediğine dair bilgileri içeren Transition nesnesini döndürür. Yalnızca okuma [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Geçersiz kılma tema yöneticisini döndürür. Yalnızca okuma [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Yalnızca okuma [`IAnimationTimeLine`](../ianimationtimeline). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için geçerli bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönüş değeri slaytın yapısı ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma benzersiz kimlik değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Bu düzen slaytına bağımlı tüm slaytları içeren bir dizi döndürür. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Düzeni sunumdan kaldırır. |

### Ayrıca Bakınız

* sınıf [BaseSlide](../baseslide)
* arayüz [ILayoutSlide](../ilayoutslide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->