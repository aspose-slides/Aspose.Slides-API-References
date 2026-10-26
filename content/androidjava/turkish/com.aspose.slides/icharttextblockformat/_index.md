---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Grafik metin öğeleri için biçimlendirme özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Grafik metin öğeleri için biçimlendirme özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. |
| [getCenterText()](#getCenterText--) | NullableBool.True ise metin kutunun içinde yatay olarak ortalanmalıdır. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True ise metin kutunun içinde yatay olarak ortalanmalıdır. |
| [getTextVerticalType()](#getTextVerticalType--) | Metin yönlendirmesini belirler. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Metin yönlendirmesini belirler. |
| [getMarginLeft()](#getMarginLeft--) | Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getWrapText()](#getWrapText--) | Metin, TextFrame kenar boşluklarında kaydırılmışsa True döner. |
| [setWrapText(byte value)](#setWrapText-byte-) | Metin, TextFrame kenar boşluklarında kaydırılmışsa True döner. |
| [getAutofitType()](#getAutofitType--) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [getRotationAngle()](#getRotationAngle--) | Sınırlayıcı kutu içinde metne uygulanan özel rotasyonu belirtir. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Sınırlayıcı kutu içinde metne uygulanan özel rotasyonu belirtir. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. Okunur/Yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. Okunur/Yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True ise metin kutunun içinde yatay olarak ortalanmalıdır. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True ise metin kutunun içinde yatay olarak ortalanmalıdır. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Metin yönlendirmesini belirler. Görsel metin dönüşünün elde edilen değeri, bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenir. Okunur/Yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Metin yönlendirmesini belirler. Görsel metin dönüşünün elde edilen değeri, bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenir. Okunur/Yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Metin, TextFrame kenar boşluklarında kaydırılmışsa True döner. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2007/2013'te tam destek). Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Metin, TextFrame kenar boşluklarında kaydırılmışsa True döner. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2007/2013'te tam destek). Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Döndürür:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Bu özelliğin değiştirilmesi sadece şu grafik bölümleri için belirli bir etki yaratabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de render etkisi yoktur). Okunur/Yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Metnin sınırlayıcı kutu içinde uygulanacak özel dönüşünü belirtir. Belirtilmemişse, birlikte gelen şeklin dönüşü kullanılır. Belirtilmişse, bu dönüş şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendi dönüşüne ek olarak bir dönüş alabilir. Görsel metin dönüşünün elde edilen değeri, bu özellik ve TextVerticalType özelliğindeki önceden tanımlı dikey türden özetlenir. Okunur/Yazılabilir float.

--------------------

> ```
> Durumu düşünün: bir şekle 90 derece saat yönünde bir dönüş uygulanmış. 
>  Buna ek olarak, metin gövdesi kendisi -90 derece saat yönünün tersine bir dönüşe sahip. 
>  Böylece ortaya çıkan şekil döndürülmüş gibi görünecek ancak içindeki metin hiç döndürülmemiş gibi görünecek.
> ```


**Döndürür:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Metnin sınırlayıcı kutu içinde uygulanacak özel dönüşünü belirtir. Belirtilmemişse, birlikte gelen şeklin dönüşü kullanılır. Belirtilmişse, bu dönüş şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendi dönüşüne ek olarak bir dönüş alabilir. Görsel metin dönüşünün elde edilen değeri, bu özellik ve TextVerticalType özelliğindeki önceden tanımlı dikey türden özetlenir. Okunur/Yazılabilir float.

--------------------

> ```
> Durumu düşünün: bir şekle 90 derece saat yönünde bir dönüş uygulanmış. 
>  Buna ek olarak, metin gövdesi kendisi -90 derece saat yönünün tersine bir dönüşe sahip 
>  saat yönünün tersine uygulanmış. Ardından elde edilen şekil şu şekilde görünecek
>  döndürülmüş gibi görünür ancak içindeki metin hiç döndürülmemiş gibi görünecektir.
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |