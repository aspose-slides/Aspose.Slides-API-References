---
title: BaseSlide
second_title: Aspose.Slides for Android Java API Referansı
description: Tüm slayt türleri için ortak verileri temsil eder.
type: docs
url: /tr/com.aspose.slides/baseslide/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Tüm slayt türleri için ortak verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShapes()](#getShapes--) | Bir slaydın şekillerini döndürür. |
| [getControls()](#getControls--) | Bir slayd üzerindeki ActiveX denetimlerinin koleksiyonunu döndürür. |
| [getName()](#getName--) | Bir slaydın adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir slaydın adını döndürür veya ayarlar. |
| [getSlideId()](#getSlideId--) | Bir slaydın kimliğini döndürür. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | İki IBaseSlide örneğinin eşit olup olmadığını belirler. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri tüm uygun şekillerde birleştirir. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri tüm uygun şekillerde birleştirir. |
| [createThemeEffective()](#createThemeEffective--) | Bu slayt için etkili bir temayı döndürür. |
| [getCustomData()](#getCustomData--) | Slaytın özel verilerini döndürür. |
| [getTimeline()](#getTimeline--) | Animasyon zaman çizelgesi nesnesini döndürür. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içeren Transition nesnesini döndürür. |
| [getBackground()](#getBackground--) | Slaytın arka planını döndürür. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | İçerilen köprü bağlantılarına kolay erişim sağlar. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | IPresentation arabirimini döndürür. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Bir slaydın şekillerini döndürür. Yalnızca okunur [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Döndürür:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Bir slayd üzerindeki ActiveX denetimlerinin koleksiyonunu döndürür. Yalnızca okunur [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Döndürür:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Bir slaydın adını döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Bir slaydın adını döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Bir slaydın kimliğini döndürür. Yalnızca okunur long.

**Döndürür:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer, slaydın yapısı ve statik içeriğine dayanarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayd eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (örneğin SlideId) ve dinamik içeriği (örneğin Tarih Yer Tutucusundaki mevcut tarih değeri) dikkate almaz.

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
boolean -  **true**  belirtilen IBaseSlide mevcut IBaseSlide ile eşitse; aksi takdirde,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri tüm uygun şekillerde birleştirir.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri tüm uygun şekillerde birleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Bu slayt için etkili bir temayı döndürür.

**Döndürür:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Slaytın özel verilerini döndürür. Yalnızca okunur [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Animasyon zaman çizelgesi nesnesini döndürür. Yalnızca okunur [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Döndürür:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içeren Transition nesnesini döndürür. Yalnızca okunur [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Döndürür:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Slaytın arka planını döndürür. Yalnızca okunur [IBackground](../../com.aspose.slides/ibackground).

**Döndürür:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

İçerilen köprü bağlantılarına kolay erişim sağlar. Yalnızca okunur [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman false döndürür. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman false döndürür. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| altText | java.lang.String | Alternatif metin. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Şekil nesnesi veya null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

IPresentation arabirimini döndürür. Yalnızca okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Temel slaytı döndürür. Yalnızca okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)