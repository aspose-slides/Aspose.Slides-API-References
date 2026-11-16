---
title: Slide
second_title: Aspose.Sildes for .NET API Referansı
description: Bir sunumda bir slaytı temsil eder.
type: docs
weight: 9980
url: /tr/aspose.slides/slide/
---
## Slide sınıfı

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Salt okunur [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Salt okunur [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verisini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Slaytın HeaderFooter yöneticisini döndürür. Salt okunur [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Belirtilen slaydın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerilen hiperlinklere kolay erişim sağlar. Salt okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Geçerli slayt için düzen slaydını döndürür veya ayarlar. Okunur/yazılabilir [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Bir slaydın adını döndürür veya ayarlar. Okunur/yazılabilir String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Not slaytına erişime, eklemeye ve kaldırmaya izin verir. Salt okunur [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Salt okunur [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Bir slaydın şekillerini döndürür. Salt okunur [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunur/yazılabilir Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Bir slaydın kimliğini döndürür. Salt okunur UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Bir slaydın numarasını döndürür. [`Slides`](../presentation/slides) koleksiyonundaki slayd indeksi her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir. Okunur/yazılabilir Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Belirtilen slaydın slayt gösterisi sırasında nasıl ilerleyeceğiyle ilgili bilgileri içeren Transition nesnesini döndürür. Salt okunur [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Üstüne yazılan tema yöneticisini döndürür. Salt okunur [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Salt okunur [`IAnimationTimeLine`](../ianimationtimeline). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için etkili bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Döndürülen değer, slaydın yapısı ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse slaydlar eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerlerini ve Date Placeholder içindeki geçerli tarih değerini dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Gerçek boyutun %20'si kadar bir Küçük Resim nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Bir Küçük Resim nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Belirtilen parametrelerle bir Küçük tiff görüntü nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Belirtilen boyutta bir Küçük Resim nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Özel ölçeklendirme ile bir Küçük Resim nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Belirtilen boyutta bir Küçük Resim nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Özel ölçeklendirme ile bir Küçük Resim nesnesi döndürür. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [Remove](../../aspose.slides/slide/remove)() | Slaytı sunumdan kaldırır. |
| [Reset](../../aspose.slides/slide/reset)() | LayoutSlide üzerinde prototipe sahip her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Slayt içeriğini EMF dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Slayt içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Slayt içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [BaseSlide](../baseslide)
* arayüz [ISlide](../islide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->