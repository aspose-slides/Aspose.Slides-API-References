---
title: PptxOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções para salvar apresentações OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /pt/com.aspose.slides/pptxoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Representa opções para salvar apresentações OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Construtores

| Construtor | Descrição |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Cria nova instância de PptxOptions |
## Métodos

| Método | Descrição |
| --- | --- |
| [getConformance()](#getConformance--) | Especifica a classe de conformidade à qual o documento Presentation está em conformidade. |
| [setConformance(int value)](#setConformance-int-) | Especifica a classe de conformidade à qual o documento Presentation está em conformidade. |
| [getZip64Mode()](#getZip64Mode--) | Especifica se o formato ZIP64 é usado para o documento Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Especifica se o formato ZIP64 é usado para o documento Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Especifica se a miniatura da apresentação será atualizada. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Especifica se a miniatura da apresentação será atualizada. |
| [getCompressionLevel()](#getCompressionLevel--) | Especifica o nível de compressão usado ao salvar o documento Presentation. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Especifica o nível de compressão usado ao salvar o documento Presentation. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


Cria nova instância de PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Especifica a classe de conformidade à qual o documento Presentation está em conformidade. Valor padrão é [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retorna:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Especifica a classe de conformidade à qual o documento Presentation está em conformidade. Valor padrão é [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Especifica se o formato ZIP64 é usado para o documento Presentation. O valor padrão é [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Retorna:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


Especifica se o formato ZIP64 é usado para o documento Presentation. O valor padrão é [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


Especifica se a miniatura da apresentação será atualizada. Leitura/gravação boolean. Valor padrão é **true**.

--------------------

> ```
> Exemplo:
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

Quando o valor da opção é **true**, a nova miniatura será gerada.

Quando o valor da opção é **false**, a miniatura atual será salva como está.

**Retorna:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Especifica se a miniatura da apresentação será atualizada. Leitura/gravação boolean. Valor padrão é **true**.

--------------------

> ```
> Exemplo:
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

Quando o valor da opção é **true**, a nova miniatura será gerada.

Quando o valor da opção é **false**, a miniatura atual será salva como está.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Especifica o nível de compressão usado ao salvar o documento Presentation. O valor padrão é [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Exemplo:
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

Níveis de compressão mais altos produzem arquivos menores, mas exigem mais tempo de processamento. A taxa de compressão real depende do conteúdo da apresentação.

**Retorna:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Especifica o nível de compressão usado ao salvar o documento Presentation. O valor padrão é [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Exemplo:
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

Níveis de compressão mais altos produzem arquivos menores, mas exigem mais tempo de processamento. A taxa de compressão real depende do conteúdo da apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |