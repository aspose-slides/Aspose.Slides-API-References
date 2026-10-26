---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Bir degrade formatını temsil eder.
type: docs
url: /tr/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Bir degrade formatını temsil eder.
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Bir degrade durak noktasının konumunu (0..1) döndürür veya ayarlar. |
| [setPosition(float value)](#setPosition-float-) | Bir degrade durak noktasının konumunu (0..1) döndürür veya ayarlar. |
| [getColor()](#getColor--) | Bir degrade durak noktasının rengini döndürür. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Bir degrade durak noktasının konumunu (0..1) döndürür veya ayarlar. Okunur/yazılabilir float.

**Döndürür:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Bir degrade durak noktasının konumunu (0..1) döndürür veya ayarlar. Okunur/yazılabilir float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Bir degrade durak noktasının rengini döndürür. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)