---
title: Compress
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um grupo de métodos destinados a comprimir.
type: docs
url: /pt/com.aspose.slides/compress/
---
**Herança:**
java.lang.Object
```
public class Compress
```

Representa um grupo de métodos destinados a comprimir [Presentation](../../com.aspose.slides/presentation).

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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides mestre não usados. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides de layout não usados. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo caracteres não usados de fontes incorporadas. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides mestre não usados.

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


Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides de layout não usados.

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


Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo caracteres não usados de fontes incorporadas.

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