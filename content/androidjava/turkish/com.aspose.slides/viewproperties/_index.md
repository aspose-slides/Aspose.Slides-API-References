---
title: ViewProperties
second_title: Aspose.Slides for Android via Java API Referansı
description: Sunum genelindeki görünüm özellikleri.
type: docs
url: /tr/com.aspose.slides/viewproperties/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Sunum genelindeki görünüm özellikleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLastView()](#getLastView--) | Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. |
| [setLastView(int value)](#setLastView-int-) | Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. |
| [getShowComments()](#getShowComments--) | Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. |
| [setShowComments(byte value)](#setShowComments-byte-) | Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Normal görünüm özelliklerini temsil eder. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Slayt görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Not görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. |
| [getGridSpacing()](#getGridSpacing--) | Sunum belgesinin altında bulunan ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür veya ayarlar. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Sunum belgesinin altında bulunan ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür veya ayarlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. Okunur/Yazılabilir [ViewType](../../com.aspose.slides/viewtype).

**Döndürür:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. Okunur/Yazılabilir [ViewType](../../com.aspose.slides/viewtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Normal görünüm özelliklerini temsil eder. Normal görünüm üç içerik bölgesinden oluşur: slayt kendisi, bir yan içerik bölgesi ve bir alt içerik bölgesi. Salt Okunur [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Döndürür:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Slayt görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. Salt Okunur [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Döndürür:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Not görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. Salt Okunur [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Döndürür:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Sunum belgesinin altında bulunan ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür veya ayarlar. Okunur/Yazılabilir float.

--------------------

> ```
> Aşağıdaki örnek kod, PowerPoint sunumunda ızgara aralığını nasıl değiştireceğinizi gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 nokta) ile 2 inç (144 nokta) arasındadır.

**Döndürür:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Sunum belgesinin altında bulunan ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür veya ayarlar. Okunur/Yazılabilir float.

--------------------

> ```
> Aşağıdaki örnek kod, PowerPoint sunumunda ızgara aralığını nasıl değiştireceğinizi gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 nokta) ile 2 inç (144 nokta) arasındadır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt Okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject