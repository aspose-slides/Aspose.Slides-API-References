---
title: LayoutSlide
second_title: Aspose.Sildes için .NET API Referansı
description: Bir yerleşim slaydını temsil eder.
type: docs
weight: 7620
url: /tr/aspose.slides/layoutslide/
---
## LayoutSlide sınıf

Bir yerleşim slaytını temsil eder.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Yalnızca okunabilir [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Yalnızca okunabilir [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verilerini döndürür. Yalnızca okunabilir [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Yerleşim slaytı için çizim kılavuzlarının koleksiyonunu döndürür. Yalnızca okunabilir [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Bu yerleşim slaytına bağlı en az bir slayt varsa doğru döndürür. Yalnızca okunabilir Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Yerleşim slaytının HeaderFooter yöneticisini döndürür. Yalnızca okunabilir [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerilen köprülerde kolay erişim sağlar. Yalnızca okunabilir [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Bu yerleşim slaytının yerleşim türünü döndürür. Yalnızca okunabilir [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Bir yerleşim için ana slaytı döndürür veya ayarlar. Okunabilir/yazılabilir [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Bir slaytın adını döndürür veya ayarlar. Okunabilir/yazılabilir String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Yerleşim slaytının yer tutucu yöneticisini döndürür. Yalnızca okunabilir [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Yalnızca okunabilir [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Bir slaytın şekillerini döndürür. Yalnızca okunabilir [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Okunabilir/yazılabilir Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Bir slaytın kimliğini döndürür. Yalnızca okunabilir UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Belirtilen slaytın bir slayt gösterisi sırasında nasıl ilerleyeceğiyle ilgili bilgileri içeren Transition nesnesini döndürür. Yalnızca okunabilir [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Geçersiz kılan tema yöneticisini döndürür. Yalnızca okunabilir [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Yalnızca okunabilir [`IAnimationTimeLine`](../ianimationtimeline). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için etkili bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Döndürülen değer, slaytın yapısı ve sabit içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerlerini ve Tarih Yer Tutucusundaki mevcut tarih değeri gibi dinamik içeriği dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip ilk şekli bulur. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Bu yerleşim slaydına bağlı tüm slaytları içeren bir dizi döndürür. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Yerleşimi sunumdan kaldırır. |

### Bkz.

* class [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->