---
title: IPptxOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: OpenXml sunumlarını (PPTX, PPSX, POTX, PPTM, PPSM, POTM) kaydetmek için seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/ipptxoptions/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

OpenXml sunumlarını (PPTX, PPSX, POTX, PPTM, PPSM, POTM) kaydetmek için seçenekleri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getConformance()](#getConformance--) | Sunum belgesinin uyması gereken uyumluluk sınıfını belirtir. |
| [setConformance(int value)](#setConformance-int-) | Sunum belgesinin uyması gereken uyumluluk sınıfını belirtir. |
| [getZip64Mode()](#getZip64Mode--) | Sunum belgesinde ZIP64 biçiminin kullanılıp kullanılmadığını belirtir. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Sunum belgesinde ZIP64 biçiminin kullanılıp kullanılmadığını belirtir. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. |
| [getCompressionLevel()](#getCompressionLevel--) | Sunum belgesini kaydederken kullanılan sıkıştırma seviyesini belirtir. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Sunum belgesini kaydederken kullanılan sıkıştırma seviyesini belirtir. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


Sunum belgesinin uyması gereken uyumluluk sınıfını belirtir. Varsayılan değer [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Döndürür:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


Sunum belgesinin uyması gereken uyumluluk sınıfını belirtir. Varsayılan değer [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```


Sunum belgesinde ZIP64 biçiminin kullanılıp kullanılmadığını belirtir. Varsayılan değer [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```


Sunum belgesinde ZIP64 biçiminin kullanılıp kullanılmadığını belirtir. Varsayılan değer [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract boolean getRefreshThumbnail()
```


Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. Okuma/Yazma boolean. Varsayılan değer **true**.

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

Seçenek değeri **true** olduğunda, yeni küçük resim oluşturulur.

Seçenek değeri **false** olduğunda, mevcut küçük resim olduğu gibi kaydedilir.

**Döndürür:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```


Sunum küçük resminin yenilenip yenilenmeyeceğini belirtir. Okuma/Yazma boolean. Varsayılan değer **true**.

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

Seçenek değeri **true** olduğunda, yeni küçük resim oluşturulur.

Seçenek değeri **false** olduğunda, mevcut küçük resim olduğu gibi kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```


Sunum belgesini kaydederken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işlem süresi gerektirir. Gerçek sıkıştırma oranı, sunumun içeriğine bağlıdır.

**Döndürür:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```


Sunum belgesini kaydederken kullanılan sıkıştırma seviyesini belirtir. Varsayılan değer [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Daha yüksek sıkıştırma seviyeleri daha küçük dosyalar üretir ancak daha fazla işlem süresi gerektirir. Gerçek sıkıştırma oranı, sunumun içeriğine bağlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |