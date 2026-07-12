---
title: XpsOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato XPS.
type: docs
url: /pt/com.aspose.slides/xpsoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Fornece opções que controlam como uma apresentação é salva no formato XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Salvando a apresentação em documento XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instanciar a classe TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Salvar MetaFiles como PNG
>      options.setSaveMetafilesAsPng(true);
>      // Salvar a apresentação em documento XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Construtor padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Verdadeiro para converter todos os metafiles usados em uma apresentação em imagens PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Verdadeiro para converter todos os metafiles usados em uma apresentação em imagens PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Verdadeiro para desenhar uma borda preta ao redor de cada slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Verdadeiro para desenhar uma borda preta ao redor de cada slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Construtor padrão.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Retorna:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


Verdadeiro para converter todos os metafiles usados em uma apresentação em imagens PNG. Leitura/escrita boolean.

--------------------

O padrão é **true**.

**Retorna:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Verdadeiro para converter todos os metafiles usados em uma apresentação em imagens PNG. Leitura/escrita boolean.

--------------------

O padrão é **true**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Verdadeiro para desenhar uma borda preta ao redor de cada slide. Leitura/escrita boolean.

--------------------

O padrão é **false**.

**Retorna:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Verdadeiro para desenhar uma borda preta ao redor de cada slide. Leitura/escrita boolean.

--------------------

O padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |