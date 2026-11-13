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

[Presentation](../../com.aspose.slides/presentation) sıkıştırmak için tasarlanmış bir grup yöntemi temsil eder.

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
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Bir sunumun boyutunu mevcut tüm sıkıştırma adımlarını uygulayarak azaltır:

 *  Kullanılmayan ana slaytları kaldırır \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Kullanılmayan yerleşim slaytlarını kaldırır \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Gömülü yazı tiplerinde gerçekten kullanılan glifleri yalnızca tutar \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Resim çözünürlüğünü 150 DPI'ye düşürür ve resimlerin kırpılmış alanlarını siler \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) sıkıştırması, kullanılmayan ana slaytlar kaldırılarak yapılır. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) sıkıştırması, kullanılmayan yerleşim slaytları kaldırılarak yapılır. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) sıkıştırması, gömülü yazı tiplerinden kullanılmayan karakterler kaldırılarak yapılır. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Sunumdaki resimlerin çözünürlüğünü düşürür ve kırpılmış alanlarını siler; bu, PowerPoint'in tüm resimlere uyguladığı "Resimleri Sıkıştır" özelliğine benzer. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Bir sunumun boyutunu mevcut tüm sıkıştırma adımlarını uygulayarak azaltır:

 *  Kullanılmayan ana slaytları kaldırır \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Kullanılmayan yerleşim slaytlarını kaldırır \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Gömülü yazı tiplerinde gerçekten kullanılan glifleri yalnızca tutar \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Resim çözünürlüğünü 150 DPI'ye düşürür ve resimlerin kırpılmış alanlarını siler \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Sıkıştırılacak sunum. |

Sıkıştırmayı özelleştirmek için, örneğin farklı bir resim çözünürlüğü kullanmak veya bir adımı atlamak amacıyla, bu yöntemi yerine yukarıda listelenen yöntemleri tek tek çağırın. Resimlerin kırpılmış alanları kalıcı olarak kaldırılır ve PowerPoint'te geri getirilemez.

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) sıkıştırması, kullanılmayan ana slaytlar kaldırılarak yapılır.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Sunum örneği. |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) sıkıştırması, kullanılmayan yerleşim slaytları kaldırılarak yapılır.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Sunum örneği. |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) sıkıştırması, gömülü yazı tiplerinden kullanılmayan karakterler kaldırılarak yapılır.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Sunum örneği. |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

Sunumdaki resimlerin çözünürlüğünü düşürür ve kırpılmış alanlarını siler; bu, PowerPoint'in tüm resimlere uyguladığı "Resimleri Sıkıştır" özelliğine benzer. Slaytlardaki, yerleşim slaytlarındaki ve ana slaytlardaki resimler işlenir; grup şekilleri içindeki resimler ve şekillerin resim dolguları da dahil.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | İşlenecek sunum. |
| resolution | int | Her resmin gösterildiği boyuta göre hedef çözünürlük. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) resimleri değiştirmeden bırakır.

Hedef çözünürlüğe eşit veya daha düşük çözünürlükte olan resimler değişmeden kalır; resimler asla yükseltilmez.

İşlem görmeyenler: slayt arka planları, tablo hücresi doldurmaları, grafikler, SmartArt, GIF görüntüler (animasyonu korumak için), SVG ve metafile (EMF/WMF) görüntüler.

Kırpılmış alanlar kalıcı olarak kaldırılır ve PowerPoint'te geri getirilemez. |