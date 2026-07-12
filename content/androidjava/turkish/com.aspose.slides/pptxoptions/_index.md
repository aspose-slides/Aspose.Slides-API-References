---
title: PptxOptions
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: OpenXml sunumlarını (PPTX, PPSX, POTX, PPTM, PPSM, POTM) kaydetmek için seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/pptxoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

OpenXml sunumlarını (PPTX, PPSX, POTX, PPTM, PPSM, POTM) kaydetmek için seçenekleri temsil eder.
## Yapıcılar

| Constructor | Description |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | PptxOptions sınıfının yeni bir örneğini oluşturur |
## Metodlar

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Presentation belgesinin uyduğu uygunluk sınıfını belirler. |
| [setConformance(int value)](#setConformance-int-) | Presentation belgesinin uyduğu uygunluk sınıfını belirler. |
| [getZip64Mode()](#getZip64Mode--) | Presentation belgesi için ZIP64 biçiminin kullanılıp kullanılmadığını belirler. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Presentation belgesi için ZIP64 biçiminin kullanılıp kullanılmadığını belirler. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Sunum küçük resminin yenilenip yenilenmeyeceğini belirler. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Sunum küçük resminin yenilenip yenilenmeyeceğini belirler. |
| [getCompressionLevel()](#getCompressionLevel--) | Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirler. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirler. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


PptxOptions sınıfının yeni bir örneğini oluşturur

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Presentation belgesinin uyduğu uygunluk sınıfını belirler. Varsayılan değer [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Döndürür:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Presentation belgesinin uyduğu uygunluk sınıfını belirler. Varsayılan değer [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Presentation belgesi için ZIP64 biçiminin kullanılıp kullanılmadığını belirler. Varsayılan değer [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


Presentation belgesi için ZIP64 biçiminin kullanılıp kullanılmadığını belirler. Varsayılan değer [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


Sunum küçük resminin yenilenip yenilenmeyeceğini belirler. Okuma/yazma boolean. Varsayılan değer **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

**true** olduğunda, yeni küçük resim oluşturulacak.

**false** olduğunda, mevcut küçük resim olduğu gibi kaydedilecek.

**Döndürür:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Sunum küçük resminin yenilenip yenilenmeyeceğini belirler. Okuma/yazma boolean. Varsayılan değer **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

**true** olduğunda, yeni küçük resim oluşturulacak.

**false** olduğunda, mevcut küçük resim olduğu gibi kaydedilecek.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirler. Varsayılan değer [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işleme süresi gerekir. Gerçek sıkıştırma oranı sunumun içeriğine bağlıdır.

**Döndürür:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirler. Varsayılan değer [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işleme süresi gerekir. Gerçek sıkıştırma oranı sunumun içeriğine bağlıdır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |