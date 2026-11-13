---
title: Compress
second_title: Referência da API Aspose.Slides para Java
description: Representa um grupo de métodos destinados a comprimir .
type: docs
url: /pt/com.aspose.slides/compress/
---
**Herança:**
java.lang.Object
```
public class Compress
```

Representa um conjunto de métodos destinados a comprimir [Presentation](../../com.aspose.slides/presentation).

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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Reduz o tamanho de uma apresentação aplicando todas as etapas de compressão disponíveis:

 *  Remove slides mestre não utilizados \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Remove slides de layout não utilizados \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Mantém apenas os glifos realmente usados em fontes incorporadas \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduz a resolução de imagens para 150 DPI e exclui áreas recortadas das imagens \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides mestre não utilizados. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides de layout não utilizados. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo caracteres não utilizados de fontes incorporadas. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Reduz a resolução das imagens na apresentação e exclui suas áreas recortadas, semelhante ao "Compress Pictures" do PowerPoint aplicado a todas as imagens. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Reduz o tamanho de uma apresentação aplicando todas as etapas de compressão disponíveis:

 *  Remove slides mestre não utilizados \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Remove slides de layout não utilizados \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Mantém apenas os glifos realmente usados em fontes incorporadas \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduz a resolução de imagens para 150 DPI e exclui áreas recortadas das imagens \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | A apresentação a ser comprimida.

--------------------

Para personalizar a compressão, por exemplo para usar uma resolução de imagem diferente ou pular uma etapa, chame os métodos listados acima individualmente em vez deste. As áreas recortadas das imagens são removidas permanentemente e não podem ser restauradas no PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides mestre não utilizados.

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


Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo slides de layout não utilizados.

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


Realiza compressão do [Presentation](../../com.aspose.slides/presentation) removendo caracteres não utilizados de fontes incorporadas.

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

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Reduz a resolução das imagens na apresentação e exclui suas áreas recortadas, semelhante ao "Compress Pictures" do PowerPoint aplicado a todas as imagens. Imagens em slides, slides de layout e slides mestre são processadas, incluindo imagens dentro de formas agrupadas e preenchimentos de imagens de formas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A apresentação a ser processada. |
| resolution | int | Resolução-alvo relativa ao tamanho em que cada imagem é exibida. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) deixa as imagens inalteradas.

Imagens já na resolução-alvo ou abaixo dela permanecem inalteradas; as imagens nunca são ampliadas.

Não processado: fundos de slide, preenchimentos de células de tabela, gráficos, SmartArt, imagens GIF (para preservar animação), imagens SVG e metafile (EMF/WMF).

Áreas recortadas são removidas permanentemente e não podem ser restauradas no PowerPoint. |