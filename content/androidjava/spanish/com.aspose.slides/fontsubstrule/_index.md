---
title: FontSubstRule
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa información de sustitución de fuentes
type: docs
url: /es/com.aspose.slides/fontsubstrule/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Representa información de sustitución de fuentes
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Crea una nueva instancia. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Crea una nueva instancia. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Fuente a sustituir. |
| [getDestFont()](#getDestFont--) | Fuente a usar para la sustitución. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regla a aplicar para la sustitución. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Crea una nueva instancia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente de origen. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente de destino. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Crea una nueva instancia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente de origen. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente de destino. |
| fontSubstRule | int | Regla de sustitución de fuentes. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Fuente a sustituir. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Fuente a usar para la sustitución. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Regla a aplicar para la sustitución. Solo lectura [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Devuelve:**
int