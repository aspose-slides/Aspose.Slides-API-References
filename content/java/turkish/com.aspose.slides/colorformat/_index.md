---
title: ColorFormat
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumda kullanılan bir rengi temsil eder.
type: docs
url: /tr/com.aspose.slides/colorformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Sunumda kullanılan bir rengi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorType()](#getColorType--) | Renk tanımlama yöntemini döndürür veya ayarlar. |
| [setColorType(int value)](#setColorType-int-) | Renk tanımlama yöntemini döndürür veya ayarlar. |
| [getColor()](#getColor--) | Tüm renk dönüşümleri uygulanmış sonuç rengi döndürür. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Tüm renk dönüşümleri uygulanmış sonuç rengi döndürür. |
| [getPresetColor()](#getPresetColor--) | Renk ön ayarını döndürür veya ayarlar. |
| [setPresetColor(int value)](#setPresetColor-int-) | Renk ön ayarını döndürür veya ayarlar. |
| [getSystemColor()](#getSystemColor--) | Sistem renk tablosu tarafından tanımlanan rengi döndürür veya ayarlar. |
| [setSystemColor(int value)](#setSystemColor-int-) | Sistem renk tablosu tarafından tanımlanan rengi döndürür veya ayarlar. |
| [getSchemeColor()](#getSchemeColor--) | Bir renk şeması tarafından tanımlanan rengi döndürür veya ayarlar. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Bir renk şeması tarafından tanımlanan rengi döndürür veya ayarlar. |
| [getR()](#getR--) | Bir rengin kırmızı bileşenini döndürür veya ayarlar. |
| [setR(byte value)](#setR-byte-) | Bir rengin kırmızı bileşenini döndürür veya ayarlar. |
| [getG()](#getG--) | Bir rengin yeşil bileşenini döndürür veya ayarlar. |
| [setG(byte value)](#setG-byte-) | Bir rengin yeşil bileşenini döndürür veya ayarlar. |
| [getB()](#getB--) | Bir rengin mavi bileşenini döndürür veya ayarlar. |
| [setB(byte value)](#setB-byte-) | Bir rengin mavi bileşenini döndürür veya ayarlar. |
| [getFloatR()](#getFloatR--) | Bir rengin kırmızı bileşenini döndürür veya ayarlar. |
| [setFloatR(float value)](#setFloatR-float-) | Bir rengin kırmızı bileşenini döndürür veya ayarlar. |
| [getFloatG()](#getFloatG--) | Bir rengin yeşil bileşenini döndürür veya ayarlar. |
| [setFloatG(float value)](#setFloatG-float-) | Bir rengin yeşil bileşenini döndürür veya ayarlar. |
| [getFloatB()](#getFloatB--) | Bir rengin mavi bileşenini döndürür veya ayarlar. |
| [setFloatB(float value)](#setFloatB-float-) | Bir rengin mavi bileşenini döndürür veya ayarlar. |
| [getHue()](#getHue--) | HSL gösteriminde bir rengin hue (renk tonu) bileşenini döndürür veya ayarlar. |
| [setHue(float value)](#setHue-float-) | HSL gösteriminde bir rengin hue (renk tonu) bileşenini döndürür veya ayarlar. |
| [getSaturation()](#getSaturation--) | HSL gösteriminde bir rengin doygunluk bileşenini döndürür veya ayarlar. |
| [setSaturation(float value)](#setSaturation-float-) | HSL gösteriminde bir rengin doygunluk bileşenini döndürür veya ayarlar. |
| [getLuminance()](#getLuminance--) | HSL gösteriminde bir rengin parlaklık bileşenini döndürür veya ayarlar. |
| [setLuminance(float value)](#setLuminance-float-) | HSL gösteriminde bir rengin parlaklık bileşenini döndürür veya ayarlar. |
| [getColorTransform()](#getColorTransform--) | Bir renge uygulanan renk dönüşümlerinin koleksiyonunu döndürür. |
| [toString(int format)](#toString-int-) | Mevcut renk biçimini temsil eden bir String döndürür. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Renk biçimini "color" kaynağından kopyalar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesneyle eşitliği kontrol eder. |
| [hashCode()](#hashCode--) | Karma kodunu döndürür. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

Renk tanımlama yöntemini döndürür veya ayarlar. Okunur/Yazılabilir [ColorType](../../com.aspose.slides/colortype).

**Döndürür:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Renk tanımlama yöntemini döndürür veya ayarlar. Okunur/Yazılabilir [ColorType](../../com.aspose.slides/colortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Tüm renk dönüşümleri uygulanmış sonuç rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini temizler. Okunur/Yazılabilir java.awt.Color.

**Döndürür:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Tüm renk dönüşümleri uygulanmış sonuç rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini temizler. Okunur/Yazılabilir java.awt.Color.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Renk ön ayarını döndürür veya ayarlar. Okunur/Yazılabilir [PresetColor](../../com.aspose.slides/presetcolor).

**Döndürür:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Renk ön ayarını döndürür veya ayarlar. Okunur/Yazılabilir [PresetColor](../../com.aspose.slides/presetcolor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Sistem renk tablosu tarafından tanımlanan rengi döndürür veya ayarlar. Okunur/Yazılabilir [SystemColor](../../com.aspose.slides/systemcolor).

**Döndürür:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Sistem renk tablosu tarafından tanımlanan rengi döndürür veya ayarlar. Okunur/Yazılabilir [SystemColor](../../com.aspose.slides/systemcolor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Bir renk şeması tarafından tanımlanan rengi döndürür veya ayarlar. Okunur/Yazılabilir [SchemeColor](../../com.aspose.slides/schemecolor).

**Döndürür:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Bir renk şeması tarafından tanımlanan rengi döndürür veya ayarlar. Okunur/Yazılabilir [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir byte.

**Döndürür:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır.

**Döndürür:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir byte.

**Döndürür:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Döndürür:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Döndürür:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Döndürür:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

HSL gösteriminde bir rengin hue (renk tonu) bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Döndürür:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

HSL gösteriminde bir rengin hue (renk tonu) bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

HSL gösteriminde bir rengin doygunluk bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Döndürür:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

HSL gösteriminde bir rengin doygunluk bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

HSL gösteriminde bir rengin parlaklık bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Döndürür:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

HSL gösteriminde bir rengin parlaklık bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yoksayılır. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Bir renge uygulanan renk dönüşümlerinin koleksiyonunu döndürür. Salt okunur [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Döndürür:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Mevcut renk biçimini temsil eden bir String döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | int | Renk dizesi formatı türü. |

**Döndürür:**
java.lang.String - Mevcut renk biçimini temsil eden bir dize.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Renk biçimini "color" kaynağından kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen nesneyle eşitliği kontrol eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Nesne. |

**Döndürür:**
boolean - Nesneler eşitse true, aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Karma kodunu döndürür.

**Döndürür:**
int - Karma kodu.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**Döndürür:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Üst IPresentationComponent'i döndürür. Salt okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)