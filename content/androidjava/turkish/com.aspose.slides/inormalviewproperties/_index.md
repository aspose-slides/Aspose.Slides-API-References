---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /tr/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Normal görünüm özelliklerini temsil eder. Normal görünüm üç içerik bölgesinden oluşur: slayt kendisi, bir yan içerik bölgesi ve bir alt içerik bölgesi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde anahat içeriği görüntüleniyorsa simgeleri gösterip göstermeyeceğini belirtir. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde anahat içeriği görüntüleniyorsa simgeleri gösterip göstermeyeceğini belirtir. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma tutunup tutmayacağını belirtir. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma tutunup tutmayacağını belirtir. |
| [getVerticalBarState()](#getVerticalBarState--) | Dikey bölücü çubuğunun gösterileceği durumu belirtir. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Dikey bölücü çubuğunun gösterileceği durumu belirtir. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Yatay bölücü çubuğunun gösterileceği durumu belirtir. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Yatay bölücü çubuğunun gösterileceği durumu belirtir. |
| [getPreferSingleView()](#getPreferSingleView--) | Kullanıcının üç içerik bölgesiyle standart normal görünüme göre tam pencere tek içerik bölgesi görmeyi tercih edip etmeyeceğini belirtir. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Kullanıcının üç içerik bölgesiyle standart normal görünüme göre tam pencere tek içerik bölgesi görmeyi tercih edip etmeyeceğini belirtir. |
| [getRestoredLeft()](#getRestoredLeft--) | Bu öğe, bölgenin değişken bir geri yükleme boyutunda (ne küçültülmüş ne de büyütülmüş) olduğu normal görünümün yan içerik bölgesinin boyutlandırılmasını belirtir. |
| [getRestoredTop()](#getRestoredTop--) | Bu öğe, bölgenin değişken bir geri yükleme boyutunda (ne küçültülmüş ne de büyütülmüş) olduğu normal görünümün üst slayt bölgesinin boyutlandırılmasını belirtir. |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde anahat içeriği görüntüleniyorsa simgeleri gösterip göstermeyeceğini belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde anahat içeriği görüntüleniyorsa simgeleri gösterip göstermeyeceğini belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma tutunup tutmayacağını belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma tutunup tutmayacağını belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Dikey bölücü çubuğunun gösterileceği durumu belirtir. Dikey bölücü çubuğu slaytı yan içerik bölgesinden ayırır.

**Döndürür:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Dikey bölücü çubuğunun gösterileceği durumu belirtir. Dikey bölücü çubuğu slaytı yan içerik bölgesinden ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Yatay bölücü çubuğunun gösterileceği durumu belirtir. Yatay bölücü çubuğu slaytı slaytın altındaki içerik bölgesinden ayırır.

**Döndürür:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Yatay bölücü çubuğunun gösterileceği durumu belirtir. Yatay bölücü çubuğu slaytı slaytın altındaki içerik bölgesinden ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Kullanıcının üç içerik bölgesiyle standart normal görünüme göre tam pencere tek içerik bölgesi görmeyi tercih edip etmeyeceğini belirtir. Etkinleştirildiğinde, uygulama içerik bölgelerinden birini tüm pencereye yaymayı seçebilir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Kullanıcının üç içerik bölgesiyle standart normal görünüme göre tam pencere tek içerik bölgesi görmeyi tercih edip etmeyeceğini belirtir. Etkinleştirildiğinde, uygulama içerik bölgelerinden birini tüm pencereye yaymayı seçebilir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Bu öğe, bölgenin değişken bir geri yükleme boyutunda (ne küçültülmüş ne de büyütülmüş) olduğu normal görünümün yan içerik bölgesinin boyutlandırılmasını belirtir. Yalnızca okunur [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Döndürür:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Bu öğe, bölgenin değişken bir geri yükleme boyutunda (ne küçültülmüş ne de büyütülmüş) olduğu normal görünümün üst slayt bölgesinin boyutlandırılmasını belirtir. Yalnızca okunur [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Döndürür:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)