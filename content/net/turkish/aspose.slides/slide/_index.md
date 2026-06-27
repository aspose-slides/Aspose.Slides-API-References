---
title: Slide
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumdaki slaytı temsil eder.
type: docs
weight: 9940
url: /tr/aspose.slides/slide/
---
## Slide sınıfı

Bir sunumdaki slaytı temsil eder.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Slaytın arka planını döndürür. Salt okunur [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Salt okunur [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Slaytın özel verilerini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Slaytın HeaderFooter yöneticisini döndürür. Salt okunur [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Belirtilen slaytın slayt gösterisi sırasında gizlenip gizlenmeyeceğini belirler. Okuma/yazma Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | İçerilen köprü bağlantılarına kolay erişim sağlar. Salt okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Geçerli slayt için yerleşim slaytını döndürür veya ayarlar. Okuma/yazma [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Slaytın adını döndürür veya ayarlar. Okuma/yazma String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Not slaytına erişim sağlar, ekler ve kaldırır. Salt okunur [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation arayüzünü döndürür. Salt okunur [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Slayttaki şekilleri döndürür. Salt okunur [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okuma/yazma Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Slaytın kimliğini (ID) döndürür. Salt okunur UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Slayt numarasını döndürür. [`Slides`](../presentation/slides) koleksiyonundaki slayt indeksi her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir. Okuma/yazma Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Slayt gösterisi sırasında slaytın nasıl ilerleyeceği hakkında bilgi içeren Transition nesnesini döndürür. Salt okunur [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Geçersiz kılan tema yöneticisini döndürür. Salt okunur [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Animasyon zaman çizelgesi nesnesini döndürür. Salt okunur [`IAnimationTimeLine`](../ianimationtimeline). |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Bu slayt için geçerli bir temayı döndürür. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer slaytın yapısı ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse slaytlar eşittir. Karşılaştırma, SlideId gibi benzersiz kimlik değerlerini ve Dinamik içerik (ör. Tarih Yer Tutucusunda geçerli tarih değeri) dikkate almaz. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Belirtilen alternatif metne sahip ilk şekli bulur. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Gerçek boyutunun %20'si kadar bir Thumbnail Image nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Bir Thumbnail Image nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Belirtilen parametrelerle bir Thumbnail tiff görüntüsü nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Belirtilen boyutta bir Thumbnail Image nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Belirtilen boyutta bir Thumbnail Image nesnesi döndürür. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [Remove](../../aspose.slides/slide/remove)() | Slaytı sunumdan kaldırır. |
| [Reset](../../aspose.slides/slide/reset)() | LayoutSlide üzerinde bir prototipine sahip her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Slayt içeriğini EMF dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Slayt içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Slayt içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [BaseSlide](../baseslide)
* arayüz [ISlide](../islide)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->