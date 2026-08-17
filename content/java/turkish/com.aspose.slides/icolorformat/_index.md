---
title: IColorFormat
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumda kullanılan bir rengi temsil eder.
type: docs
url: /tr/com.aspose.slides/icolorformat/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Bir sunumda kullanılan bir rengi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorType()](#getColorType--) | Renk tanımlama metodunu döndürür veya ayarlar. |
| [setColorType(int value)](#setColorType-int-) | Renk tanımlama metodunu döndürür veya ayarlar. |
| [getColor()](#getColor--) | Tüm renk dönüşümleri uygulanmış sonucu rengi döndürür. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Tüm renk dönüşümleri uygulanmış sonucu rengi döndürür. |
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
| [getHue()](#getHue--) | HSL gösteriminde rengin ton bileşenini döndürür veya ayarlar. |
| [setHue(float value)](#setHue-float-) | HSL gösteriminde rengin ton bileşenini döndürür veya ayarlar. |
| [getSaturation()](#getSaturation--) | HSL gösteriminde rengin doygunluk bileşenini döndürür veya ayarlar. |
| [setSaturation(float value)](#setSaturation-float-) | HSL gösteriminde rengin doygunluk bileşenini döndürür veya ayarlar. |
| [getLuminance()](#getLuminance--) | HSL gösteriminde rengin parlaklık bileşenini döndürür veya ayarlar. |
| [setLuminance(float value)](#setLuminance-float-) | HSL gösteriminde rengin parlaklık bileşenini döndürür veya ayarlar. |
| [getColorTransform()](#getColorTransform--) | Bir renge uygulanan renk dönüşümlerinin koleksiyonunu döndürür. |
| [toString(int format)](#toString-int-) | Geçerli renk formatını temsil eden bir String döndürür. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Renk formatını “color”dan kopyalar. |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Renk tanımlama metodunu döndürür veya ayarlar. Okuma/yazma [ColorType](../../com.aspose.slides/colortype).

**Döndürür:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Renk tanımlama metodunu döndürür veya ayarlar. Okuma/yazma [ColorType](../../com.aspose.slides/colortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Tüm renk dönüşümleri uygulanmış sonucu rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini temizler. Okuma/yazma java.awt.Color.

**Döndürür:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Tüm renk dönüşümleri uygulanmış sonucu rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini temizler. Okuma/yazma java.awt.Color.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Renk ön ayarını döndürür veya ayarlar. Okuma/yazma [PresetColor](../../com.aspose.slides/presetcolor).

**Döndürür:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Renk ön ayarını döndürür veya ayarlar. Okuma/yazma [PresetColor](../../com.aspose.slides/presetcolor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Sistem renk tablosu tarafından tanımlanan rengi döndürür veya ayarlar. Okuma/yazma [SystemColor](../../com.aspose.slides/systemcolor).

**Döndürür:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Sistem renk tablosu tarafından tanımlanan rengi döndürür veya ayarlar. Okuma/yazma [SystemColor](../../com.aspose.slides/systemcolor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Bir renk şeması tarafından tanımlanan rengi döndürür veya ayarlar. Okuma/yazma [SchemeColor](../../com.aspose.slides/schemecolor).

**Döndürür:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Bir renk şeması tarafından tanımlanan rengi döndürür veya ayarlar. Okuma/yazma [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma byte.

**Döndürür:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma byte.

**Döndürür:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma byte.

**Döndürür:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Döndürür:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Bir rengin kırmızı bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Döndürür:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Bir rengin yeşil bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Döndürür:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Bir rengin mavi bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL gösteriminde rengin ton bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Döndürür:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL gösteriminde rengin ton bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL gösteriminde rengin doygunluk bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Döndürür:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL gösteriminde rengin doygunluk bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL gösteriminde rengin parlaklık bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Döndürür:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL gösteriminde rengin parlaklık bileşenini döndürür veya ayarlar. Tüm renk dönüşümleri yok sayılır. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Bir renge uygulanan renk dönüşümlerinin koleksiyonunu döndürür. Salt-okunur [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Döndürür:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Geçerli renk formatını temsil eden bir String döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | int | Renk dizesi biçimi türü. |

**Döndürür:**
java.lang.String - Geçerli renk formatını temsil eden bir dize.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Renk formatını “color”dan kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Renk [IColorFormat](../../com.aspose.slides/icolorformat) |