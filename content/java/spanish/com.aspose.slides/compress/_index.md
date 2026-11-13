---
title: Compress
second_title: Aspose.Slides para la referencia de API de Java
description: Representa un grupo de métodos destinados a comprimir.
type: docs
url: /es/com.aspose.slides/compress/
---
**Herencia:**
java.lang.Object
```
public class Compress
```

Representa un grupo de métodos destinados a comprimir [Presentation](../../com.aspose.slides/presentation).

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Compress()](#Compress--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Reduce el tamaño de una presentación aplicando todos los pasos de compresión disponibles:

 *  Elimina diapositivas maestras no utilizadas \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Elimina diapositivas de diseño no utilizadas \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Conserva solo los glifos realmente utilizados en fuentes incrustadas \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduce la resolución de las imágenes a 150 DPI y elimina las áreas recortadas de las imágenes \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Realiza la compresión del [Presentation](../../com.aspose.slides/presentation) mediante la eliminación de diapositivas maestras no utilizadas. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Realiza la compresión del [Presentation](../../com.aspose.slides/presentation) mediante la eliminación de diapositivas de diseño no utilizadas. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Realiza la compresión del [Presentation](../../com.aspose.slides/presentation) mediante la eliminación de caracteres no utilizados de las fuentes incrustadas. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Reduce la resolución de las imágenes en la presentación y elimina sus áreas recortadas, similar a la función "Compress Pictures" de PowerPoint aplicada a todas las imágenes. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Reduce el tamaño de una presentación aplicando todos los pasos de compresión disponibles:

 *  Elimina diapositivas maestras no utilizadas \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Elimina diapositivas de diseño no utilizadas \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Conserva solo los glifos realmente utilizados en fuentes incrustadas \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduce la resolución de las imágenes a 150 DPI y elimina las áreas recortadas de las imágenes \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | La presentación a comprimir.

--------------------

Para personalizar la compresión, por ejemplo para usar una resolución de imagen diferente o para omitir un paso, llame a los métodos enumerados arriba individualmente en lugar de este. Las áreas recortadas de las imágenes se eliminan de forma permanente y no pueden restaurarse en PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Realiza la compresión del [Presentation](../../com.aspose.slides/presentation) mediante la eliminación de diapositivas maestras no utilizadas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La instancia de la presentación |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Realiza la compresión del [Presentation](../../com.aspose.slides/presentation) mediante la eliminación de diapositivas de diseño no utilizadas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La instancia de la presentación |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Realiza la compresión del [Presentation](../../com.aspose.slides/presentation) mediante la eliminación de caracteres no utilizados de las fuentes incrustadas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La instancia de la presentación |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Reduce la resolución de las imágenes en la presentación y elimina sus áreas recortadas, similar a la función "Compress Pictures" de PowerPoint aplicada a todas las imágenes. Las imágenes en diapositivas, diapositivas de diseño y diapositivas maestras son procesadas, incluidas las imágenes dentro de formas grupales y los rellenos de imágenes de las formas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | La presentación a procesar. |
| resolution | int | Resolución objetivo relativa al tamaño al que se muestra cada imagen. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) deja las imágenes sin cambios.

--------------------

Las imágenes que ya están en o por debajo de la resolución objetivo se dejan sin cambios; las imágenes nunca se aumentan.

Sin procesar: fondos de diapositiva, rellenos de celdas de tabla, gráficos, SmartArt, imágenes GIF (para preservar la animación), imágenes SVG y metafiles (EMF/WMF).

Las áreas recortadas se eliminan de forma permanente y no pueden restaurarse en PowerPoint. |