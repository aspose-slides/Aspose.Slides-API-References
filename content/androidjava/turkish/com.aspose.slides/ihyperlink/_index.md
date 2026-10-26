---
title: IHyperlink
second_title: Aspose.Slides for Android Java API Referansı
description: Bir hiperbağlantıyı temsil eder.
type: docs
url: /tr/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Bir hiperbağlantıyı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx'in eyleminin türünü döndürür. |
| [getExternalUrl()](#getExternalUrl--) | Harici URL'yi belirtir. Bu özellik null olmadığında TargetSlide özelliği null olur. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Bu bölümün gerçek içeriği göz önüne alınmadan bu bölüm için ayarlanan bir hiperbağlantıyı temsil eder. |
| [getTargetSlide()](#getTargetSlide--) | HyperlinkEx belirli bir slaytı hedefliyorsa bu slaytı döndürür. |
| [getTargetFrame()](#getTargetFrame--) | Varsa, ebeveyn hiperbağlantısının hedefi için ebeveyn HTML çerçeve seti içinde çerçeveyi döndürür. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Varsa, ebeveyn hiperbağlantısının hedefi için ebeveyn HTML çerçeve seti içinde çerçeveyi döndürür. |
| [getTooltip()](#getTooltip--) | Ebeveyn hiperbağlantısı ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Ebeveyn hiperbağlantısı ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. |
| [getHistory()](#getHistory--) | Ebeveyn hiperbağlantısının hedefinin, çağrıldığında görüntülenen hiperbağlantılar listesine eklenip eklenmeyeceğini belirler. |
| [setHistory(boolean value)](#setHistory-boolean-) | Ebeveyn hiperbağlantısının hedefinin, çağrıldığında görüntülenen hiperbağlantılar listesine eklenip eklenmeyeceğini belirler. |
| [getHighlightClick()](#getHighlightClick--) | Hiperbağlantının tıklandığında vurgulanıp vurgulanmayacağını belirler. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Hiperbağlantının tıklandığında vurgulanıp vurgulanmayacağını belirler. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Hiperbağlantı tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Hiperbağlantı tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| [getSound()](#getSound--) | Hiperbağlantının çalan sesini temsil eder. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Hiperbağlantının çalan sesini temsil eder. |
| [getColorSource()](#getColorSource--) | Hiperbağlantı renginin kaynağını temsil eder - stil ya da bölüm biçimi. |
| [setColorSource(int value)](#setColorSource-int-) | Hiperbağlantı renginin kaynağını temsil eder - stil ya da bölüm biçimi. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

HyperLinkEx'in eyleminin türünü döndürür. Salt okunur [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Döndürür:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Harici URL'yi belirtir. Bu özellik null olmadığında TargetSlide özelliği null olur. Salt okunur String.

**Döndürür:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Bu bölümün gerçek içeriği göz önüne alınmadan bu bölüm için ayarlanan bir hiperbağlantıyı temsil eder.

--------------------

PowerPoint, bir bölümdeki bağlantılar ve bunlara karşılık gelen metin konusunda özel davranır. Geçerli bağlantı adresinden farklı geçerli bir URL biçiminde hiperbağlantı için metin oluşturulmasına izin verir. Bu durumda, düzenleme penceresinde bağlantıyı görüntülediğinizde, metin bölümüyle eşleşecek şekilde değiştirilecektir. Bu özellik, hiperbağlantının orijinal değerini temsil eder.

**Döndürür:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

HyperlinkEx belirli bir slaytı hedefliyorsa bu slaytı döndürür. Özellik null olmaya başlarsa ExternalUrl özelliği null olur. Salt okunur [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Varsa, ebeveyn hiperbağlantısının hedefi için ebeveyn HTML çerçeve seti içinde çerçeveyi döndürür. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Varsa, ebeveyn hiperbağlantısının hedefi için ebeveyn HTML çerçeve seti içinde çerçeveyi döndürür. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Ebeveyn hiperbağlantısı ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Ebeveyn hiperbağlantısı ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Ebeveyn hiperbağlantısının hedefinin, çağrıldığında görüntülenen hiperbağlantılar listesine eklenip eklenmeyeceğini belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Ebeveyn hiperbağlantısının hedefinin, çağrıldığında görüntülenen hiperbağlantılar listesine eklenip eklenmeyeceğini belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Hiperbağlantının tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Hiperbağlantının tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Hiperbağlantı tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Hiperbağlantı tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Hiperbağlantının çalan sesini temsil eder. Okunur/yazılabilir [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // İlk şeklin hiperbağlantısını al
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Hiperbağlantı sesini bayt dizisine çıkar
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
public abstract void setSound(IAudio value)
```

Hiperbağlantının çalan sesini temsil eder. Okunur/yazılabilir [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // İlk şeklin hiperbağlantısını al
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Hiperbağlantı sesini bayt dizisine çıkar
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
public abstract int getColorSource()
```

Hiperbağlantı renginin kaynağını temsil eder - stil ya da bölüm biçimi. Okunur/yazılabilir [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Döndürür:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Hiperbağlantı renginin kaynağını temsil eder - stil ya da bölüm biçimi. Okunur/yazılabilir [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

İki Hyperlink örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Mevcut Hyperlink ile karşılaştırılacak Hyperlink. |

**Döndürür:**
boolean - belirtilen Hyperlink mevcut Hyperlink ile eşitse **true**, aksi takdirde **false**.