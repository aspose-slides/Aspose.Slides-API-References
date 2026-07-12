---
title: Compress
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Sıkıştırma amaçlı bir grup yöntemi temsil eder.
type: docs
url: /tr/com.aspose.slides/compress/
---
**Kalıtım:**
java.lang.Object
```
public class Compress
```

[Presentation](../../com.aspose.slides/presentation)'i sıkıştırmak amacıyla tasarlanmış bir grup yöntemi temsil eder.

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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Kullanılmayan ana slaytları kaldırarak [Presentation](../../com.aspose.slides/presentation)'in sıkıştırılmasını sağlar. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Kullanılmayan yerleşim slaytlarını kaldırarak [Presentation](../../com.aspose.slides/presentation)'in sıkıştırılmasını sağlar. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak [Presentation](../../com.aspose.slides/presentation)'in sıkıştırılmasını sağlar. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Kullanılmayan ana slaytları kaldırarak [Presentation](../../com.aspose.slides/presentation)'in sıkıştırılmasını sağlar.

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


Kullanılmayan yerleşim slaytlarını kaldırarak [Presentation](../../com.aspose.slides/presentation)'in sıkıştırılmasını sağlar.

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


Gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak [Presentation](../../com.aspose.slides/presentation)'in sıkıştırılmasını sağlar.

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