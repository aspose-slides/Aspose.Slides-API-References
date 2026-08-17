---
title: NormalViewProperties
second_title: Aspose.Slides için Java API Referansı
description: Normal görünüm özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/normalviewproperties/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Normal görünüm özelliklerini temsil eder. Normal görünüm üç içerik bölgesinden oluşur: slayt kendisi, bir yan içerik bölgesi ve bir alt içerik bölgesi.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Sunum dosyasını temsil eden bir sunum nesnesi oluşturun
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
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Normal görünüm modunda herhangi bir içerik bölgesinde anahat içeriği görüntülenirken uygulamanın simgeleri gösterip göstermeyeceğini belirtir. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Normal görünüm modunda herhangi bir içerik bölgesinde anahat içeriği görüntülenirken uygulamanın simgeleri gösterip göstermeyeceğini belirtir. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma yapışıp yapmayacağını belirtir. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma yapışıp yapmayacağını belirtir. |
| [getVerticalBarState()](#getVerticalBarState--) | Dikey bölücü çubuğunun gösterilmesi gereken durumu belirtir. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Dikey bölücü çubuğunun gösterilmesi gereken durumu belirtir. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Yatay bölücü çubuğunun gösterilmesi gereken durumu belirtir. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Yatay bölücü çubuğunun gösterilmesi gereken durumu belirtir. |
| [getPreferSingleView()](#getPreferSingleView--) | Kullanıcının standart üç içerik bölgesine sahip normal görünüm yerine tam pencere tek-içerik bölgesi tercih edip etmediğini belirtir. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Kullanıcının standart üç içerik bölgesine sahip normal görünüm yerine tam pencere tek-içerik bölgesi tercih edip etmediğini belirtir. |
| [getRestoredLeft()](#getRestoredLeft--) | Bu öğe, bölge değişken bir geri yüklenmiş boyutta (ne küçültülmüş ne de büyütülmüş) olduğunda normal görünümün yan içerik bölgesinin boyutlandırılmasını belirtir. |
| [getRestoredTop()](#getRestoredTop--) | Bu öğe, bölge değişken bir geri yüklenmiş boyutta (ne küçültülmüş ne de büyütülmüş) olduğunda normal görünümün üst slayt bölgesinin boyutlandırılmasını belirtir. |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Uygulamanın normal görünüm modunda herhangi bir içerik bölgesinde anahat içeriği görüntülenirken simgeleri gösterip göstermeyeceğini belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Uygulamanın normal görünüm modunda herhangi bir içerik bölgesinde anahat içeriği görüntülenirken simgeleri gösterip göstermeyeceğini belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma yapışıp yapmayacağını belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Yan bölge yeterince küçük olduğunda dikey bölücünün küçültülmüş bir duruma yapışıp yapmayacağını belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Dikey bölücü çubuğunun gösterilmesi gereken durumu belirtir. Dikey bölücü çubuğu slaytı yan içerik bölgesinden ayırır.

**Döndürür:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Dikey bölücü çubuğunun gösterilmesi gereken durumu belirtir. Dikey bölücü çubuğu slaytı yan içerik bölgesinden ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Yatay bölücü çubuğunun gösterilmesi gereken durumu belirtir. Yatay bölücü çubuğu slaytı slaytın altındaki içerik bölgesinden ayırır.

**Döndürür:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Yatay bölücü çubuğunun gösterilmesi gereken durumu belirtir. Yatay bölücü çubuğu slaytı slaytın altındaki içerik bölgesinden ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Kullanıcının standart üç içerik bölgesine sahip normal görünüm yerine tam pencere tek-içerik bölgesi tercih edip etmediğini belirtir. Etkinleştirildiğinde uygulama, içerik bölgelerinden birini tüm pencere içinde gösterebilir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Kullanıcının standart üç içerik bölgesine sahip normal görünüm yerine tam pencere tek-içerik bölgesi tercih edip etmediğini belirtir. Etkinleştirildiğinde uygulama, içerik bölgelerinden birini tüm pencere içinde gösterebilir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Bu öğe, normal görünümde yan içerik bölgesinin boyutlandırılmasını belirtir; bölge değişken bir geri yüklenmiş boyutta (küçültülmemiş ya da büyütülmemiş) olduğunda. Yalnızca okuma [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Döndürür:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Bu öğe, normal görünümde üst slayt bölgesinin boyutlandırılmasını belirtir; bölge değişken bir geri yüklenmiş boyutta (küçültülmemiş ya da büyütülmemiş) olduğunda. Yalnızca okuma [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Döndürür:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)