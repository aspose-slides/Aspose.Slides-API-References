---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que contém propriedades de formatação de parágrafo efetivas.
type: docs
url: /pt/com.aspose.slides/iparagraphformateffectivedata/
---```

```

Objeto imutável que contém propriedades de formatação de parágrafo efetivas.

--------------------

Esta interface é usada juntamente com a interface [IParagraphFormat](../../com.aspose.slides/iparagraphformat) para retornar valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBullet()](#getBullet--) | Retorna um formato de marcador de um parágrafo. |
| [getDepth()](#getDepth--) | Retorna a profundidade de um parágrafo. |
| [getAlignment()](#getAlignment--) | Retorna o alinhamento de texto em um parágrafo. |
| [getSpaceWithin()](#getSpaceWithin--) | Retorna a quantidade de espaço entre linhas base em um parágrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Retorna a quantidade de espaço antes da primeira linha em um parágrafo. |
| [getSpaceAfter()](#getSpaceAfter--) | Retorna a quantidade de espaço após a última linha em um parágrafo. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se a quebra de linha East Asian é usada em um parágrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se a escrita Right to Left é usada em um parágrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se a quebra de linha Latin é usada em um parágrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se a pontuação suspensa é usada em um parágrafo. |
| [getMarginLeft()](#getMarginLeft--) | Retorna a margem esquerda em um parágrafo. |
| [getMarginRight()](#getMarginRight--) | Retorna a margem direita em um parágrafo. |
| [getIndent()](#getIndent--) | Retorna o recuo da primeira linha/recuso suspenso do parágrafo. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retorna o tamanho padrão de tabulação. |
| [getTabs()](#getTabs--) | Retorna as tabulações de um parágrafo. |
| [getFontAlignment()](#getFontAlignment--) | Retorna um alinhamento de fonte em um parágrafo. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retorna o formato padrão de porção de um parágrafo. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Retorna um formato de marcador de um parágrafo. Somente leitura [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Retorna:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Retorna a profundidade de um parágrafo. Somente leitura short.

**Retorna:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Retorna o alinhamento de texto em um parágrafo. Somente leitura [TextAlignment](../../com.aspose.slides/textalignment).

**Retorna:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Retorna a quantidade de espaço entre linhas base em um parágrafo. Somente leitura float.

**Retorna:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Retorna a quantidade de espaço antes da primeira linha em um parágrafo. Somente leitura float.

**Retorna:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Retorna a quantidade de espaço após a última linha em um parágrafo. Somente leitura float.

**Retorna:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Determina se a quebra de linha East Asian é usada em um parágrafo. Somente leitura boolean.

**Retorna:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Determina se a escrita Right to Left é usada em um parágrafo. Somente leitura boolean.

**Retorna:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Determina se a quebra de linha Latin é usada em um parágrafo. Somente leitura boolean.

**Retorna:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Determina se a pontuação suspensa é usada em um parágrafo. Somente leitura boolean.

**Retorna:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Retorna a margem esquerda em um parágrafo. Somente leitura float.

**Retorna:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Retorna a margem direita em um parágrafo. Somente leitura float.

**Retorna:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Retorna o recuo da primeira linha/recuso suspenso do parágrafo. O recuo suspenso pode ser definido com valores negativos. Somente leitura float.

**Retorna:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Retorna o tamanho padrão de tabulação. Somente leitura float.

**Retorna:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Retorna as tabulações de um parágrafo. Somente leitura ITabEffectiveData[].

**Retorna:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Retorna um alinhamento de fonte em um parágrafo. Somente leitura [FontAlignment](../../com.aspose.slides/fontalignment).

**Retorna:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Retorna o formato padrão de porção de um parágrafo. Somente leitura [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Retorna:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)