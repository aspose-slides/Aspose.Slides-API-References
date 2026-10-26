---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Sunum genelindeki görünüm özellikleri.
type: docs
url: /tr/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Sunum genelindeki görünüm özellikleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLastView()](#getLastView--) | Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. |
| [setLastView(int value)](#setLastView-int-) | Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. |
| [getShowComments()](#getShowComments--) | Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. |
| [setShowComments(byte value)](#setShowComments-byte-) | Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Slayt görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Notlar görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Normal görünüm özelliklerini temsil eder. |
| [getGridSpacing()](#getGridSpacing--) | Sunum belgesi altındaki ızgara için kullanılacak ızgara aralığını döndürür veya ayarlar, birim puan. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Sunum belgesi altındaki ızgara için kullanılacak ızgara aralığını döndürür veya ayarlar, birim puan. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. Okunur/Yazılabilir [ViewType](../../com.aspose.slides/viewtype).

**Döndürür:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Sunum belgesi en son kaydedildiğinde kullanılan görünüm modunu belirtir. Okunur/Yazılabilir [ViewType](../../com.aspose.slides/viewtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Slayt yorumlarının gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Slayt görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. Salt okunur [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Döndürür:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Notlar görünüm moduyla ilişkili ortak görünüm özelliklerini belirtir. Salt okunur [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Döndürür:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Normal görünüm özelliklerini temsil eder. Normal görünüm üç içerik bölgesinden oluşur: slayt kendisi, yan içerik bölgesi ve alt içerik bölgesi. Salt okunur [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Döndürür:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Sunum belgesi altındaki ızgara için kullanılacak ızgara aralığını döndürür veya ayarlar, birim puan. Okunur/Yazılabilir float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 puan) ile 2 inç (144 puan) arasındadır.

**Döndürür:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Sunum belgesi altındaki ızgara için kullanılacak ızgara aralığını döndürür veya ayarlar, birim puan. Okunur/Yazılabilir float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 puan) ile 2 inç (144 puan) arasındadır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |