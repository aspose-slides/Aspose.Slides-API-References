---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the sizing of the slide region width when a child of restoredTop height when a child of restoredLeft of the normal view when the region is of a variable restored sizeneither minimized nor maximized.
type: docs
url: /tr/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

Kaydırıma ilişkin bölgenin boyutlandırmasını belirtir ((restoredTop'un bir çocuğu olduğunda genişlik, restoredLeft'in bir çocuğu olduğunda yükseklik) normal görünümde, bölge değişken bir restored boyutunda (ne küçültülmüş ne de büyütülmüş) olduğunda).

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | Kaydırıma ilişkin bölgenin boyutunu belirler (RestoredTop'un bir çocuğu olduğunda genişlik, RestoredLeft'in bir çocuğu olduğunda yükseklik). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | Kaydırıma ilişkin bölgenin boyutunu belirler (RestoredTop'un bir çocuğu olduğunda genişlik, RestoredLeft'in bir çocuğu olduğunda yükseklik). |
| [getAutoAdjust()](#getAutoAdjust--) | Kaydırıma ilişkin kenar içerik bölgesinin boyutunun, uygulamadaki görünümü içeren pencere yeniden boyutlandığında yeni boyuta göre telafi edilip edilmediğini belirler. Okunur/Yazılabilir boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | Kaydırıma ilişkin kenar içerik bölgesinin boyutunun, uygulamadaki görünümü içeren pencere yeniden boyutlandığında yeni boyuta göre telafi edilip edilmediğini belirler. Okunur/Yazılabilir boolean. |

### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

Kaydırıma ilişkin bölgenin boyutunu belirler (RestoredTop'un bir çocuğu olduğunda genişlik, RestoredLeft'in bir çocuğu olduğunda yükseklik). Okunur/Yazılabilir float.

**Dönüş Değeri:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

Kaydırıma ilişkin bölgenin boyutunu belirler (RestoredTop'un bir çocuğu olduğunda genişlik, RestoredLeft'in bir çocuğu olduğunda yükseklik). Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

Kaydırıma ilişkin kenar içerik bölgesinin boyutunun, uygulamadaki görünümü içeren pencere yeniden boyutlandığında yeni boyuta göre telafi edilip edilmediğini belirler. Okunur/Yazılabilir boolean.

**Dönüş Değeri:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

Kaydırıma ilişkin kenar içerik bölgesinin boyutunun, uygulamadaki görünümü içeren pencere yeniden boyutlandığında yeni boyuta göre telafi edilip edilmediğini belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |