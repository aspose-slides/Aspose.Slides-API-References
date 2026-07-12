---
title: IXpsOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato XPS.
type: docs
url: /pt/com.aspose.slides/ixpsoptions/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Fornece opções que controlam como uma apresentação é salva no formato XPS.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True para converter todos os metafiles usados em uma apresentação para imagens PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True para converter todos os metafiles usados em uma apresentação para imagens PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True para desenhar uma moldura preta ao redor de cada slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True para desenhar uma moldura preta ao redor de cada slide. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True para converter todos os metafiles usados em uma apresentação para imagens PNG. Booleano de leitura/gravação.

--------------------

O padrão é **true**.

**Retorna:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True para converter todos os metafiles usados em uma apresentação para imagens PNG. Booleano de leitura/gravação.

--------------------

O padrão é **true**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True para desenhar uma moldura preta ao redor de cada slide. Booleano de leitura/gravação.

--------------------

O padrão é **false**.

**Retorna:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True para desenhar uma moldura preta ao redor de cada slide. Booleano de leitura/gravação.

--------------------

O padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Retorna:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |