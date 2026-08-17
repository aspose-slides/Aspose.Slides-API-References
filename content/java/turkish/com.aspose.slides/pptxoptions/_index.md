---
title: PptxOptions
second_title: Aspose.Slides for Java API Referansı
description: OpenXml sunumlarını (PPTX, PPSX, POTX, PPTM, PPSM, POTM) kaydetmek için seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/pptxoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

OpenXml sunumlarını (PPTX, PPSX, POTX, PPTM, PPSM, POTM) kaydetmek için seçenekleri temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | PptxOptions yeni örneği oluşturur |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getConformance()](#getConformance--) | Sunum belgesinin uyduğu uyumluluk sınıfını belirtir. |
| [setConformance(int value)](#setConformance-int-) | Sunum belgesinin uyduğu uyumluluk sınıfını belirtir. |
| [getZip64Mode()](#getZip64Mode--) | Sunum belgesi için ZIP64 biçiminin kullanılıp kullanılmayacağını belirtir. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Sunum belgesi için ZIP64 biçiminin kullanılıp kullanılmayacağını belirtir. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. |
| [getCompressionLevel()](#getCompressionLevel--) | Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirtir. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirtir. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


PptxOptions yeni örneği oluşturur

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Sunum belgesinin uyduğu uyumluluk sınıfını belirtir. Varsayılan değer [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Dönüş Değeri:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Sunum belgesinin uyduğu uyumluluk sınıfını belirtir. Varsayılan değer [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Sunum belgesi için ZIP64 biçiminin kullanılıp kullanılmayacağını belirtir. Varsayılan değer [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Dönüş Değeri:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


Sunum belgesi için ZIP64 biçiminin kullanılıp kullanılmayacağını belirtir. Varsayılan değer [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. Okuma/yazma boolean. Varsayılan değer **true**.

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

Seçenek değeri **true** olduğunda yeni küçük resim oluşturulur.

Seçenek değeri **false** olduğunda mevcut küçük resim olduğu gibi kaydedilir.

**Dönüş Değeri:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. Okuma/yazma boolean. Varsayılan değer **true**.

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

Seçenek değeri **true** olduğunda yeni küçük resim oluşturulur.

Seçenek değeri **false** olduğunda mevcut küçük resim olduğu gibi kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işleme süresi gerektirir. Gerçek sıkıştırma oranı sunumun içeriğine bağlıdır.

**Dönüş Değeri:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Sunum belgesi kaydedilirken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işleme süresi gerektirir. Gerçek sıkıştırma oranı sunumun içeriğine bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |