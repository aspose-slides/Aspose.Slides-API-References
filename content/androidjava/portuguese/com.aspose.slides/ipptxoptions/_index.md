---
title: IPptxOptions
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa opções para salvar apresentações OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /pt/com.aspose.slides/ipptxoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Representa opções para salvar apresentações OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
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
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Especifica a classe de conformidade à qual o documento Presentation está em conformidade. O valor padrão é [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retorna:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Especifica a classe de conformidade à qual o documento Presentation está em conformidade. O valor padrão é [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
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
public abstract void setZip64Mode(int value)
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
public abstract boolean getRefreshThumbnail()
```

Especifica se a miniatura da apresentação será atualizada. Leitura/gravação boolean. Valor padrão é **true**.

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

Quando o valor da opção é **true**, a nova miniatura será gerada.

Quando o valor da opção é **false**, a miniatura atual será salva como está.

**Retorna:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Especifica se a miniatura da apresentação será atualizada. Leitura/gravação boolean. Valor padrão é **true**.

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

Quando o valor da opção é **true**, a nova miniatura será gerada.

Quando o valor da opção é **false**, a miniatura atual será salva como está.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Especifica o nível de compressão usado ao salvar o documento Presentation. O valor padrão é [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Níveis de compressão mais altos produzem arquivos menores, mas exigem mais tempo de processamento. A taxa de compressão real depende do conteúdo da apresentação.

**Retorna:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Especifica o nível de compressão usado ao salvar o documento Presentation. O valor padrão é [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Níveis de compressão mais altos produzem arquivos menores, mas exigem mais tempo de processamento. A taxa de compressão real depende do conteúdo da apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |