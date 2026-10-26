---
title: PortionFormat
second_title: Aspose.Slides Android için Java API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/portionformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)'un aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Bir sunum dosyasını temsil eden bir sunum nesnesi örnekleyin
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides bu özel tanımlayıcıları kullanır (PowerPoint'te kullanılanlara benzer):
>      // +mn-lt -Gövde Yazı Tipi Latin (Küçük Latin Yazı Tipi)
>      // +mj-lt -Başlık Yazı Tipi Latin (Büyük Latin Yazı Tipi)
>      // +mn-ea -Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
>      // +mj-ea -Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda değerler “tanımsız” anlamına gelir.

Kalıtım dahil olmak üzere etkili biçimlendirme parametresi değerlerini elde etmek için [getEffective](../../com.aspose.slides/portionformat\#getEffective) yöntemini kullanmanız gerekir; bu yöntem bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) örneği döndürür.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Yeni bir [PortionFormat](../../com.aspose.slides/portionformat) sınıfının örneğini başlatır. |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Yer imi tanımlayıcısını döndürür veya ayarlar. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Yer imi tanımlayıcısını döndürür veya ayarlar. |
| [getSmartTagClean()](#getSmartTagClean--) | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Fare üzerindeyken tanımlanan köprüyü döndürür veya ayarlar. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Fare üzerindeyken tanımlanan köprüyü döndürür veya ayarlar. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Köprü yöneticisi. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili bölüm biçimlendirme verilerini alır. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Yeni bir [PortionFormat](../../com.aspose.slides/portionformat) sınıfının örneğini başlatır.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Yer imi tanımlayıcısını döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Yer imi tanımlayıcısını döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Kalıtım uygulanmaz. Okuma/yazma boolean .

**Döndürür:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Kalıtım uygulanmaz. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar. Okuma/yazma [IHyperlink](../../com.aspose.slides/ihyperlink).

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar. Okuma/yazma [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Fare üzerindeyken tanımlanan köprüyü döndürür veya ayarlar. Okuma/yazma [IHyperlink](../../com.aspose.slides/ihyperlink).

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Fare üzerindeyken tanımlanan köprüyü döndürür veya ayarlar. Okuma/yazma [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Köprü yöneticisi. Salt okunur [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Döndürür:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Kalıtım uygulanmış etkili bölüm biçimlendirme verilerini alır.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).