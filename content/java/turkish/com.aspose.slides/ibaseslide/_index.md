---
title: IBaseSlide
second_title: Aspose.Slides for Java API Referansı
description: Tüm slayt tipleri için ortak verileri temsil eder.
type: docs
url: /tr/com.aspose.slides/ibaseslide/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Tüm slayt tipleri için ortak verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShapes()](#getShapes--) | Bir slaydın şekillerini döndürür. |
| [getControls()](#getControls--) | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. |
| [getName()](#getName--) | Bir slaydın adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir slaydın adını döndürür veya ayarlar. |
| [getSlideId()](#getSlideId--) | Bir slaydın kimliğini döndürür. |
| [getCustomData()](#getCustomData--) | Slaydın özel verisini döndürür. |
| [getTimeline()](#getTimeline--) | Animasyon zaman çizelgesi nesnesini döndürür. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içeren TransitionEx nesnesini döndürür. |
| [getBackground()](#getBackground--) | Slaydın arka planını döndürür. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | İçerilen köprü bağlantılarına kolay erişim sağlar. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Bir slaydın şekillerini döndürür. Salt-okunur [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Döndürür:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Salt-okunur [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Döndürür:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Bir slaydın adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Bir slaydın adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Bir slaydın kimliğini döndürür. Salt-okunur long.

**Döndürür:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Slaydın özel verisini döndürür. Salt-okunur [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Animasyon zaman çizelgesi nesnesini döndürür. Salt-okunur [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Döndürür:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içeren TransitionEx nesnesini döndürür. Salt-okunur [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Döndürür:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Slaydın arka planını döndürür. Salt-okunur [IBackground](../../com.aspose.slides/ibackground).

**Döndürür:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

İçerilen köprü bağlantılarına kolay erişim sağlar. Salt-okunur [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman false döndürür. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman false döndürür. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| altText | java.lang.String | Alternatif metin. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx nesnesi veya null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer, slaydın yapısı ve statik içeriği temel alınarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse slaytlar eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerlerini ve Dinamik içerik, örneğin Tarih Yer Tutucusundaki geçerli tarih değerini hesaba katmaz.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Karşılaştırılacak mevcut IBaseSlide. |

**Döndürür:**
boolean - **true** eğer belirtilen IBaseSlide mevcut IBaseSlide ile eşitse; aksi takdirde **false**.