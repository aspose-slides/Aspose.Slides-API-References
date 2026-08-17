---
title: Compress
second_title: Referência da API Aspose.Slides para Java
description: Representa um grupo de métodos destinados a compactar .
type: docs
url: /pt/com.aspose.slides/compress/
---
**Herança:**
java.lang.Object
```
public class Compress
```

Representa um grupo de métodos destinados a compactar [Presentation](../../com.aspose.slides/presentation).

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
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Compress()](#Compress--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Faz a compactação do [Presentation](../../com.aspose.slides/presentation) removendo slides mestres não utilizados. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Faz a compactação do [Presentation](../../com.aspose.slides/presentation) removendo slides de layout não utilizados. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Faz a compactação do [Presentation](../../com.aspose.slides/presentation) removendo caracteres não utilizados de fontes incorporadas. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Faz a compactação do [Presentation](../../com.aspose.slides/presentation) removendo slides mestres não utilizados.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A instância da apresentação |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Faz a compactação do [Presentation](../../com.aspose.slides/presentation) removendo slides de layout não utilizados.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A instância da apresentação |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Faz a compactação do [Presentation](../../com.aspose.slides/presentation) removendo caracteres não utilizados de fontes incorporadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A instância da apresentação |