---
title: ILineFormatEffectiveData
second_title: Aspose.Slides para Android via Referência de API Java
description: Objeto imutável que contém propriedades efetivas de formatação de linha.
type: docs
url: /pt/com.aspose.slides/ilineformateffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Objeto imutável que contém propriedades efetivas de formatação de linha.

--------------------

Esta interface é usada juntamente com a interface [ILineFormat](../../com.aspose.slides/ilineformat) para retornar valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retorna o formato de preenchimento de uma linha. |
| [getSketchFormat()](#getSketchFormat--) | Retorna o formato de esboço de uma linha. |
| [getWidth()](#getWidth--) | Retorna a largura de uma linha. |
| [getDashStyle()](#getDashStyle--) | Retorna o estilo de traço da linha. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Retorna o padrão de traço personalizado. |
| [getCapStyle()](#getCapStyle--) | Retorna o estilo de extremidade da linha. |
| [getStyle()](#getStyle--) | Retorna o estilo da linha. |
| [getAlignment()](#getAlignment--) | Retorna o alinhamento da linha. |
| [getJoinStyle()](#getJoinStyle--) | Retorna o estilo de junção das linhas. |
| [getMiterLimit()](#getMiterLimit--) | Retorna o limite de mitra de uma linha. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Retorna o estilo da ponta de seta no início de uma linha. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Retorna o estilo da ponta de seta no final de uma linha. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Retorna a largura da ponta de seta no início de uma linha. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Retorna a largura da ponta de seta no final de uma linha. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Retorna o comprimento da ponta de seta no início de uma linha. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Retorna o comprimento da ponta de seta no final de uma linha. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determina se as duas instâncias ILineFormatEffectiveData são iguais. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Retorna o formato de preenchimento de uma linha. Somente leitura [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Retorna:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Retorna o formato de esboço de uma linha. Somente leitura [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Retorna:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Retorna a largura de uma linha. Somente leitura double.

**Retorna:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Retorna o estilo de traço da linha. Somente leitura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retorna:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Retorna o padrão de traço personalizado. Somente leitura float[].

**Retorna:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Retorna o estilo de extremidade da linha. Somente leitura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retorna:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Retorna o estilo da linha. Somente leitura [LineStyle](../../com.aspose.slides/linestyle).

**Retorna:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Retorna o alinhamento da linha. Somente leitura [LineAlignment](../../com.aspose.slides/linealignment).

**Retorna:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Retorna o estilo de junção das linhas. Somente leitura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retorna:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Retorna o limite de mitra de uma linha. Somente leitura float.

**Retorna:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Retorna o estilo da ponta de seta no início de uma linha. Somente leitura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retorna:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Retorna o estilo da ponta de seta no final de uma linha. Somente leitura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retorna:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Retorna a largura da ponta de seta no início de uma linha. Somente leitura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retorna:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Retorna a largura da ponta de seta no final de uma linha. Somente leitura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retorna:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Retorna o comprimento da ponta de seta no início de uma linha. Somente leitura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retorna:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Retorna o comprimento da ponta de seta no final de uma linha. Somente leitura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retorna:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Determina se as duas instâncias ILineFormatEffectiveData são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | O ILineFormatEffectiveData a ser comparado com o ILineFormatEffectiveData atual. |

**Retorna:**
boolean - **true** se o ILineFormatEffectiveData especificado for igual ao ILineFormatEffectiveData atual; caso contrário, **false**.