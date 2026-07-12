---
title: FontSubstRule
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa informações de substituição de fonte
type: docs
url: /pt/com.aspose.slides/fontsubstrule/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Representa informações de substituição de fonte
## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Cria nova instância. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Cria nova instância. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Fonte a substituir. |
| [getDestFont()](#getDestFont--) | Fonte a usar para substituição. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regra a aplicar para substituição. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Cria nova instância.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de origem. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de destino. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Cria nova instância.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de origem. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de destino. |
| fontSubstRule | int | Regra de substituição de fonte. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Fonte a substituir. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Fonte a usar para substituição. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Regra a aplicar para substituição. Somente leitura [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Retorna:**
int