---
title: Compress
second_title: Aspose.Slides for Java API Referansı
description: Sıkıştırmak için tasarlanmış bir grup yöntemi temsil eder.
type: docs
url: /tr/com.aspose.slides/compress/
---
**Kalıtım:**
java.lang.Object
```
public class Compress
```

[Presentation](../../com.aspose.slides/presentation)'ı sıkıştırmak için tasarlanmış bir grup yöntemi temsil eder.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Compress()](#Compress--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Kullanılmayan ana slaytları kaldırarak [Presentation](../../com.aspose.slides/presentation) sıkıştırmasını yapar. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Kullanılmayan düzen slaytlarını kaldırarak [Presentation](../../com.aspose.slides/presentation) sıkıştırmasını yapar. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak [Presentation](../../com.aspose.slides/presentation) sıkıştırmasını yapar. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Kullanılmayan ana slaytları kaldırarak [Presentation](../../com.aspose.slides/presentation) sıkıştırmasını yapar.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Sunum örneği |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Kullanılmayan düzen slaytlarını kaldırarak [Presentation](../../com.aspose.slides/presentation) sıkıştırmasını yapar.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Sunum örneği |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak [Presentation](../../com.aspose.slides/presentation) sıkıştırmasını yapar.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Sunum örneği |