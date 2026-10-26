---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /tr/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Grafik metin öğeleri için biçimlendirme özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Returns or sets vertical anchor text in a TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returns or sets vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Determines text orientation. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determines text orientation. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin (points) in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin (points) in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin (points) in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin (points) in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAutofitType()](#getAutofitType--) | Returns or sets text's autofit mode. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returns or sets text's autofit mode. |
| [getRotationAngle()](#getRotationAngle--) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifies the custom rotation that is being applied to the text within the bounding box. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Bir TextFrame içinde dikey tutturma metnini alır veya ayarlar. Okuma/yazma [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Bir TextFrame içinde dikey tutturma metnini alır veya ayarlar. Okuma/yazma [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True ise metin kutu içinde yatay olarak ortalanmalıdır. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True ise metin kutu içinde yatay olarak ortalanmalıdır. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Metin yönelimini belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının birleştirilmesiyle elde edilen görsel metin dönüş değeri. Okuma/yazma [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Metin yönelimini belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının birleştirilmesiyle elde edilen görsel metin dönüş değeri. Okuma/yazma [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Bir TextFrame içinde sol kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Bir TextFrame içinde sol kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Bir TextFrame içinde sağ kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Bir TextFrame içinde sağ kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Bir TextFrame içinde üst kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Bir TextFrame içinde üst kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Bir TextFrame içinde alt kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Bir TextFrame içinde alt kenar boşluğunu (nokta) alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Metin TextFrame kenar boşluklarında kaydırılıyorsa doğru. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2007/2013'te tam destek). Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Metin TextFrame kenar boşluklarında kaydırılıyorsa doğru. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2007/2013'te tam destek). Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Metnin otomatik sığdırma modunu alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma [TextAutofitType](../../com.aspose.slides/textautofittype).

**Döndürür:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Metnin otomatik sığdırma modunu alır veya ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümleri için belirli bir etki oluşturabilir: DataLabel ve DataLabelFormat (PowerPoint 2013'te tam destek; PowerPoint 2007'de görüntüleme için etkisi yok). Okuma/yazma [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Sınırlayıcı kutu içinde metne uygulanan özel dönüşü belirtir. Belirtilmezse, ekli şeklin dönüşü kullanılır. Belirtilirse, bu şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisine ayrıca bir dönüş uygulanırken aynı anda bir dönüş de alabilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin birleştirilmesiyle elde edilen görsel metin dönüş değeri. Okuma/yazma float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Döndürür:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Sınırlayıcı kutu içinde metne uygulanan özel dönüşü belirtir. Belirtilmezse, ekli şeklin dönüşü kullanılır. Belirtilirse, bu şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisine ayrıca bir dönüş uygulanırken aynı anda bir dönüş de alabilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin birleştirilmesiyle elde edilen görsel metin dönüş değeri. Okuma/yazma float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |