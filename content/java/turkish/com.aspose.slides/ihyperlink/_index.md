---
title: IHyperlink
second_title: Aspose.Slides for Java API Referansı
description: Bir köprüyü temsil eder.
type: docs
url: /tr/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Bir köprüyü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx'in eyleminin türünü döndürür. |
| [getExternalUrl()](#getExternalUrl--) | Harici URL'yi belirtir. Bu özellik null olmayan bir değere dönüştüğünde TargetSlide özelliği null olur. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Bu bölümün gerçek içeriğine bakılmaksızın bu bölüm için ayarlanmış bir köprüyü temsil eder. |
| [getTargetSlide()](#getTargetSlide--) | HyperlinkEx belirli bir slaytı hedefliyorsa bu slaytı döndürür. |
| [getTargetFrame()](#getTargetFrame--) | Varsa, üst köprünün hedefi için üst HTML çerçeve setindeki çerçeveyi döndürür. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Varsa, üst köprünün hedefi için üst HTML çerçeve setindeki çerçeveyi döndürür. |
| [getTooltip()](#getTooltip--) | Üst köprüyle ilişkili olarak kullanıcı arayüzünde görüntülenebilecek dizeyi döndürür. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Üst köprüyle ilişkili olarak kullanıcı arayüzünde görüntülenebilecek dizeyi döndürür. |
| [getHistory()](#getHistory--) | Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. |
| [setHistory(boolean value)](#setHistory-boolean-) | Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. |
| [getHighlightClick()](#getHighlightClick--) | Köprünün tıklandığında vurgulanıp vurgulanmayacağını belirler. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Köprünün tıklandığında vurgulanıp vurgulanmayacağını belirler. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. |
| [getSound()](#getSound--) | Köprünün çalan sesini temsil eder. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Köprünün çalan sesini temsil eder. |
| [getColorSource()](#getColorSource--) | Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. |
| [setColorSource(int value)](#setColorSource-int-) | Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | İki Hyperlink örneğinin eşit olup olmadığını belirler. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Yalnızca okunabilir [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Döndürür:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Harici URL'yi belirtir. Bu özellik null olmayan bir değere dönüştüğünde TargetSlide özelliği null olur. Yalnızca okunabilir String.

**Döndürür:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Bu bölümün gerçek içeriğine bakılmaksızın bu bölüm için ayarlanmış bir köprüyü temsil eder.

---

PowerPoint davranışı, bir bölümdeki bağlantılar ve bunlara karşılık gelen metin için özeldir. Bağlantı için geçerli bir URL biçiminde metin oluşturulmasına izin verir; bu, bağlantının gerçek adresinden farklıdır. Bu durumda, bağlantıyı düzenleme penceresinde görüntülediğinizde, metin bölümüne uyması için değiştirilecektir. Bu özellik, köprünün orijinal değerini temsil eder.

**Döndürür:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

HyperlinkEx belirli bir slaytı hedefliyorsa bu slaytı döndürür. Bu özellik null olmayan bir değere dönüştüğünde ExternalUrl özelliği null olur. Yalnızca okunabilir [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Varsa, üst köprünün hedefi için üst HTML çerçeve setindeki çerçeveyi döndürür. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Varsa, üst köprünün hedefi için üst HTML çerçeve setindeki çerçeveyi döndürür. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Üst köprüyle ilişkili olarak kullanıcı arayüzünde görüntülenebilecek dizeyi döndürür. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Üst köprüyle ilişkili olarak kullanıcı arayüzünde görüntülenebilecek dizeyi döndürür. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Üst köprünün hedefinin, tetiklendiğinde görüntülenen köprüler listesine eklenip eklenmeyeceğini belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Köprünün tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Köprünün tıklandığında vurgulanıp vurgulanmayacağını belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Köprü tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Köprünün çalan sesini temsil eder. Okunabilir/Yazılabilir [IAudio](../../com.aspose.slides/iaudio).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // İlk şekil köprüsünü al
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Köprü sesini bayt dizisine çıkar
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

Köprünün çalan sesini temsil eder. Okunabilir/Yazılabilir [IAudio](../../com.aspose.slides/iaudio).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // İlk şekil köprüsünü al
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Köprü sesini bayt dizisine çıkar
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. Okunabilir/Yazılabilir [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Döndürür:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Köprü renginin kaynağını temsil eder - stil ya da bölüm biçimi. Okunabilir/Yazılabilir [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

İki Hyperlink örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Karşılaştırılacak Hyperlink. |

**Döndürür:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.