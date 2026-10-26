---
title: Hyperlink
second_title: Aspose.Slides for Android Java API Referansı
description: Bir köprüyü temsil eder.
type: docs
url: /tr/com.aspose.slides/hyperlink/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Bir köprüyü temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Bir köprünün örneğini oluşturur. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Belirli bir slayta işaret eden bir köprünün örneğini oluşturur. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | İkincil özellikleri geçersiz kılarak başka bir köprüyü kaynak olarak kullanan bir köprünün örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Özel bir "hiçbir şey yapma" köprüsünü döndürür. |
| [getMedia()](#getMedia--) | Özel bir "ortam dosyası oynat" köprüsünü döndürür. |
| [getNextSlide()](#getNextSlide--) | Sonraki slayta bir köprüyü döndürür. |
| [getPreviousSlide()](#getPreviousSlide--) | Önceki slayta bir köprüyü döndürür. |
| [getFirstSlide()](#getFirstSlide--) | Sunumun ilk slaytına bir köprüyü döndürür. |
| [getLastSlide()](#getLastSlide--) | Sunumun son slaytına bir köprüyü döndürür. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Son görüntülenen slayta bir köprüyü döndürür. |
| [getEndShow()](#getEndShow--) | Gösteriyi sonlandıran bir köprüyü döndürür. |
| [getActionType()](#getActionType--) | Köprünün eylem tipini döndürür. |
| [getExternalUrl()](#getExternalUrl--) | Harici URL'yi belirtir. |
| [getTargetSlide()](#getTargetSlide--) | Köprü belirli bir slayta yöneliyorsa bu slaytı döndürür. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Parçanın gerçek içeriğine bakılmaksızın bu bölüm için ayarlanmış bir köprüyü temsil eder. |
| [getTargetFrame()](#getTargetFrame--) | Üst köprünün hedefi mevcutsa, üst HTML çerçeve setindeki hedef çerçeveyi döndürür. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Üst köprünün hedefi mevcutsa, üst HTML çerçeve setindeki hedef çerçeveyi döndürür. |
| [getTooltip()](#getTooltip--) | Üst köprünün ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Üst köprünün ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. |
| [getHistory()](#getHistory--) | Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. |
| [setHistory(boolean value)](#setHistory-boolean-) | Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. |
| [getHighlightClick()](#getHighlightClick--) | Köprünün tıklamada vurgulanıp vurgulanmayacağını belirler. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Köprünün tıklamada vurgulanıp vurgulanmayacağını belirler. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| [getSound()](#getSound--) | Köprünün çalan sesini temsil eder. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Köprünün çalan sesini temsil eder. |
| [getColorSource()](#getColorSource--) | Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. |
| [setColorSource(int value)](#setColorSource-int-) | Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | İki köprünün eşitliğini test eder. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | İki köprünün eşitsizliğini test eder. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet eder, hash tablo gibi veri yapılarını ve algoritmalarını kullanmak için uygundur. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Bir köprünün örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Köprü URL'si. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Belirli bir slayta işaret eden bir köprünün örneğini oluşturur. Not: oluşturulan köprü aynı sunumdaki bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

İkincil özellikleri geçersiz kılarak başka bir köprüyü kaynak olarak kullanan bir köprünün örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Kaynak köprü |
| targetFrame | java.lang.String | Hedef çerçeve |
| tooltip | java.lang.String | İpucu metni |
| history | boolean | Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. |
| stopSoundsOnClick | boolean | Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| highlightClick | boolean | Köprünün tıklamada vurgulanıp vurgulanmayacağını belirler. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okunur long.

**Döndürür:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Özel bir "hiçbir şey yapma" köprüsünü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Özel bir "ortam dosyası oynat" köprüsünü döndürür. AudioFrame ve VideoFrame içinde kullanılır. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Sonraki slayta bir köprüyü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Önceki slayta bir köprüyü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Sunumun ilk slaytına bir köprüyü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Sunumun son slaytına bir köprüyü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Son görüntülenen slayta bir köprüyü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Gösteriyi sonlandıran bir köprüyü döndürür. Yalnızca okunur [Hyperlink](../../com.aspose.slides/hyperlink).

**Döndürür:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Köprünün eylem tipini döndürür. Yalnızca okunur [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Döndürür:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Harici URL'yi belirtir. Yalnızca okunur String.

**Döndürür:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Köprü belirli bir slayta yöneliyorsa bu slaytı döndürür. Yalnızca okunur [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Parçanın gerçek içeriğine bakılmaksızın bu bölüm için ayarlanmış bir köprüyü temsil eder.

PowerPoint, bir bölümdeki bağlantılar ve bunlara karşılık gelen metinler için özel davranır. Bağlantı için gerçek adresinden farklı, geçerli bir URL biçiminde metin oluşturulmasına izin verir. Bu durumda, bağlantıyı düzenleme penceresinde görüntülediğinizde, metin kısmına uygun şekilde değişir. Bu özellik, köprünün orijinal değerini temsil eder.

**Döndürür:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Üst köprünün hedefi mevcutsa, üst HTML çerçeve setindeki hedef çerçeveyi döndürür. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Üst köprünün hedefi mevcutsa, üst HTML çerçeve setindeki hedef çerçeveyi döndürür. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Üst köprünün ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Üst köprünün ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Köprünün tıklamada vurgulanıp vurgulanmayacağını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Köprünün tıklamada vurgulanıp vurgulanmayacağını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Köprünün çalan sesini temsil eder. Okunur/yazılır [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // İlk şeklin hiperlinkini al
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Köprü sesini bayt dizisi olarak çıkar
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Köprünün çalan sesini temsil eder. Okunur/yazılır [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // İlk şeklin hiperlinkini al
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Köprü sesini bayt dizisi olarak çıkar
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. Okunur/yazılır [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Döndürür:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. Okunur/yazılır [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

İki Hyperlink örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak Hyperlink. |

**Döndürür:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

İki Hyperlink örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Karşılaştırılacak Hyperlink. |

**Döndürür:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

İki köprünün eşitliğini test eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Test edilen ilk köprü. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Test edilen ikinci köprü. |

**Döndürür:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

İki köprünün eşitsizliğini test eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Test edilen ilk köprü. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Test edilen ikinci köprü. |

**Döndürür:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için hash işlevi olarak hizmet eder, hash tablo gibi veri yapılarını ve algoritmalarını kullanmak için uygundur.

**Döndürür:**
int - URL için hash kodu.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject