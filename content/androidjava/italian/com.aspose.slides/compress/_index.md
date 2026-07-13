---
title: Compress
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un gruppo di metodi destinati a comprimere.
type: docs
url: /it/com.aspose.slides/compress/
---
**Eredità:**
java.lang.Object
```
public class Compress
```

Rappresenta un gruppo di metodi destinati a comprimere [Presentation](../../com.aspose.slides/presentation).

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Effettua la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le diapositive master inutilizzate. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Effettua la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le diapositive layout inutilizzate. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Effettua la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo i caratteri inutilizzati dai font incorporati. |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Effettua la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le diapositive master inutilizzate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'istanza della presentazione |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

Effettua la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le diapositive layout inutilizzate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'istanza della presentazione |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

Effettua la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo i caratteri inutilizzati dai font incorporati.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'istanza della presentazione |