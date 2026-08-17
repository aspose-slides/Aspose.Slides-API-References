---
title: BaseSlide
second_title: Aspose.Slides for Java API Referansı
description: Tüm slayt tipleri için ortak verileri temsil eder.
type: docs
url: /tr/com.aspose.slides/baseslide/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Tüm slayt türleri için ortak verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShapes()](#getShapes--) | Bir slaydın şekillerini döndürür. |
| [getControls()](#getControls--) | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. |
| [getName()](#getName--) | Bir slaydın adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir slaydın adını döndürür veya ayarlar. |
| [getSlideId()](#getSlideId--) | Bir slaydın kimliğini döndürür. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm paragraf ve tüm uygun şekillerde aynı biçimlendirmeye sahip bölümleri birleştirir. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Tüm paragraf ve tüm uygun şekillerde aynı biçimlendirmeye sahip bölümleri birleştirir. |
| [createThemeEffective()](#createThemeEffective--) | Bu slayt için geçerli bir temayı döndürür. |
| [getCustomData()](#getCustomData--) | Slaydın özel verilerini döndürür. |
| [getTimeline()](#getTimeline--) | Animasyon zaman çizelgesi nesnesini döndürür. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Belirtilen slaydın sunum sırasında nasıl ilerlediği hakkında bilgi içeren Transition nesnesini döndürür. |
| [getBackground()](#getBackground--) | Slaydın arka planını döndürür. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | İçerilen köprü adreslerine kolay erişim sağlar. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Belirtilen alternatif metne sahip ilk şekli bulur. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | IPresentation arayüzünü döndürür. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Bir slaydın şekillerini döndürür. Yalnızca okuma [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Döndürür:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Yalnızca okuma [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Döndürür:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Bir slaydın adını döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Bir slaydın adını döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Bir slaydın kimliğini döndürür. Yalnızca okuma long.

**Döndürür:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer, slaydın yapısı ve statik içeriği temel alınarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerleri ve Date Placeholder içindeki geçerli tarih değeri gibi dinamik içeriği dikkate almaz.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Mevcut IBaseSlide ile karşılaştırılacak IBaseSlide. |

**Döndürür:**
boolean -  **true**  belirtilen IBaseSlide, mevcut IBaseSlide ile eşitse; aksi takdirde,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Tüm paragraf ve tüm uygun şekillerde aynı biçimlendirmeye sahip bölümleri birleştirir.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Tüm paragraf ve tüm uygun şekillerde aynı biçimlendirmeye sahip bölümleri birleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Bu slayt için geçerli bir temayı döndürür.

**Döndürür:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Slaydın özel verilerini döndürür. Yalnızca okuma [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Animasyon zaman çizelgesi nesnesini döndürür. Yalnızca okuma [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Döndürür:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Belirtilen slaydın sunum sırasında nasıl ilerlediği hakkında bilgi içeren Transition nesnesini döndürür. Yalnızca okuma [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Döndürür:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Slaydın arka planını döndürür. Yalnızca okuma [IBackground](../../com.aspose.slides/ibackground).

**Döndürür:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

İçerilen köprü adreslerine kolay erişim sağlar. Yalnızca okuma [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman false döndürür. Okuma/yazma boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman false döndürür. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Belirtilen alternatif metne sahip ilk şekli bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| altText | java.lang.String | Alternatif metin. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Shape nesnesi veya null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

IPresentation arayüzünü döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Temel slaytı döndürür. Yalnızca okuma [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)