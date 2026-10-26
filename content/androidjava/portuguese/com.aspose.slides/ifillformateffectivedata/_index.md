---
title: IFillFormatEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que contém propriedades efetivas de formatação de preenchimento.
type: docs
url: /pt/com.aspose.slides/ifillformateffectivedata/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Objeto imutável que contém propriedades efetivas de formatação de preenchimento.

--------------------

Esta interface é usada junto com a interface [IFillFormat](../../com.aspose.slides/ifillformat) para retornar valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillType()](#getFillType--) | Retorna o tipo de preenchimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Retorna a cor de preenchimento. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Obtém a cor de preenchimento definida por um esquema de cores. |
| [getGradientFormat()](#getGradientFormat--) | Retorna o formato de preenchimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Retorna o formato de preenchimento de padrão. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retorna o formato de preenchimento de imagem. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se o preenchimento deve ser rotacionado com a forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retorna o tipo de preenchimento. Somente leitura [FillType](../../com.aspose.slides/filltype).

**Retorna:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Retorna a cor de preenchimento. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Obtém a cor de preenchimento definida por um esquema de cores. O valor [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) indica que o SolidFillColor (\#getSolidFillColor.getSolidFillColor) não é uma cor de esquema. Somente leitura [SchemeColor](../../com.aspose.slides/schemecolor).

**Retorna:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Retorna o formato de preenchimento gradiente. Somente leitura [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Retorna:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Retorna o formato de preenchimento de padrão. Somente leitura [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Retorna:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Retorna o formato de preenchimento de imagem. Somente leitura [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Retorna:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Determina se o preenchimento deve ser rotacionado com a forma. Somente leitura boolean.

**Retorna:**
boolean