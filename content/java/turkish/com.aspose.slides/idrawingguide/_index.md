---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Ayarlanabilir bir çizim kılavuzu temsil eder.
type: docs
url: /tr/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Ayarlanabilir bir çizim kılavuzu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOrientation()](#getOrientation--) | Çizim kılavuzunun yönünü döndürür veya ayarlar. |
| [setOrientation(byte value)](#setOrientation-byte-) | Çizim kılavuzunun yönünü döndürür veya ayarlar. |
| [getPosition()](#getPosition--) | Çizim kılavuzunun konumunu slaytın sol üst köşesinden nokta cinsinden döndürür veya ayarlar. |
| [setPosition(float value)](#setPosition-float-) | Çizim kılavuzunun konumunu slaytın sol üst köşesinden nokta cinsinden döndürür veya ayarlar. |
| [getColor()](#getColor--) | Çizim kılavuzunun rengini döndürür veya ayarlar. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Çizim kılavuzunun rengini döndürür veya ayarlar. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Çizim kılavuzunun yönünü döndürür veya ayarlar. Okunur/Yazılabilir [Orientation](../../com.aspose.slides/orientation).

**Döndürür:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Çizim kılavuzunun yönünü döndürür veya ayarlar. Okunur/Yazılabilir [Orientation](../../com.aspose.slides/orientation).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Çizim kılavuzunun konumunu slaytın sol üst köşesinden nokta cinsinden döndürür veya ayarlar. Okunur/Yazılabilir float.

--------------------

Tipik değer aralığı, yatay bir kılavuz için sıfırdan slayt yüksekliğine ve dikey bir kılavuz için sıfırdan slayt genişliğine kadardır.

**Döndürür:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Çizim kılavuzunun konumunu slaytın sol üst köşesinden nokta cinsinden döndürür veya ayarlar. Okunur/Yazılabilir float.

--------------------

Tipik değer aralığı, yatay bir kılavuz için sıfırdan slayt yüksekliğine ve dikey bir kılavuz için sıfırdan slayt genişliğine kadardır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Çizim kılavuzunun rengini döndürür veya ayarlar. Okunur/Yazılabilir java.awt.Color.

**Döndürür:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Çizim kılavuzunun rengini döndürür veya ayarlar. Okunur/Yazılabilir java.awt.Color.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |