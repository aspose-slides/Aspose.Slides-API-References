---
title: NormalViewProperties
second_title: Aspose.Slides for Android için Java API Referansı
description: Normal görünüm özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/normalviewproperties/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Normal görünüm özelliklerini temsil eder. Normal görünüm, slayt kendisi, bir yan içerik bölgesi ve bir alt içerik bölgesi olmak üzere üç içerik bölgesinden oluşur.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Bir sunum dosyasını temsil eden bir sunum nesnesi oluşturun
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde taslak içeriği görüntülerken simgeleri gösterip göstermeyeceğini belirtir. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde taslak içeriği görüntülerken simgeleri gösterip göstermeyeceğini belirtir. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Yan bölge yeterince küçük olduğunda dikey ayırıcının küçültülmüş bir duruma çekilip çekilmeyeceğini belirtir. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Yan bölge yeterince küçük olduğunda dikey ayırıcının küçültülmüş bir duruma çekilip çekilmeyeceğini belirtir. |
| [getVerticalBarState()](#getVerticalBarState--) | Dikey ayırıcı çubuğunun gösterileceği durumu belirtir. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Dikey ayırıcı çubuğunun gösterileceği durumu belirtir. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Yatay ayırıcı çubuğunun gösterileceği durumu belirtir. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Yatay ayırıcı çubuğunun gösterileceği durumu belirtir. |
| [getPreferSingleView()](#getPreferSingleView--) | Kullanıcının üç içerik bölgesi içeren standart normal görünüm yerine tam pencere tek içerik bölgesi görmeyi tercih edip etmediğini belirtir. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Kullanıcının üç içerik bölgesi içeren standart normal görünüm yerine tam pencere tek içerik bölgesi görmeyi tercih edip etmediğini belirtir. |
| [getRestoredLeft()](#getRestoredLeft--) | Bu öğe, bölgenin değişken bir geri yüklenmiş boyutta (ne küçültülmüş ne de büyütülmüş) olduğu durumda normal görünümdeki yan içerik bölgesinin boyutlandırılmasını belirtir. |
| [getRestoredTop()](#getRestoredTop--) | Bu öğe, bölgenin değişken bir geri yüklenmiş boyutta (ne küçültülmüş ne de büyütülmüş) olduğu durumda normal görünümdeki üst slayt bölgesinin boyutlandırılmasını belirtir. |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde taslak içeriği görüntülerken simgeleri gösterip göstermeyeceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Uygulamanın normal görünüm modunda içerik bölgelerinden herhangi birinde taslak içeriği görüntülerken simgeleri gösterip göstermeyeceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Yan bölge yeterince küçük olduğunda dikey ayırıcının küçültülmüş bir duruma çekilip çekilmeyeceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Yan bölge yeterince küçük olduğunda dikey ayırıcının küçültülmüş bir duruma çekilip çekilmeyeceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Dikey ayırıcı çubuğunun gösterileceği durumu belirtir. Dikey ayırıcı çubuğu, slaytı yan içerik bölgesinden ayırır.

**Döndürür:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Dikey ayırıcı çubuğunun gösterileceği durumu belirtir. Dikey ayırıcı çubuğu, slaytı yan içerik bölgesinden ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Yatay ayırıcı çubuğunun gösterileceği durumu belirtir. Yatay ayırıcı çubuğu, slaytı slaytın altındaki içerik bölgesinden ayırır.

**Döndürür:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Yatay ayırıcı çubuğunun gösterileceği durumu belirtir. Yatay ayırıcı çubuğu, slaytı slaytın altındaki içerik bölgesinden ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Kullanıcının üç içerik bölgesi içeren standart normal görünüm yerine tam pencere tek içerik bölgesi görmeyi tercih edip etmediğini belirtir. Etkinleştirildiğinde, uygulama içerik bölgelerinden birini tüm pencere içinde görüntülemeyi seçebilir. Okuma/Yazma boolean.

**Döndürür:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Kullanıcının üç içerik bölgesi içeren standart normal görünüm yerine tam pencere tek içerik bölgesi görmeyi tercih edip etmediğini belirtir. Etkinleştirildiğinde, uygulama içerik bölgelerinden birini tüm pencere içinde görüntülemeyi seçebilir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Bu öğe, bölgenin değişken bir geri yüklenmiş boyutta (ne küçültülmüş ne de büyütülmüş) olduğu durumda normal görünümdeki yan içerik bölgesinin boyutlandırılmasını belirtir. Sadece Okunur [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Döndürür:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Bu öğe, bölgenin değişken bir geri yüklenmiş boyutta (ne küçültülmüş ne de büyütülmüş) olduğu durumda normal görünümdeki üst slayt bölgesinin boyutlandırılmasını belirtir. Sadece Okunur [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Döndürür:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)