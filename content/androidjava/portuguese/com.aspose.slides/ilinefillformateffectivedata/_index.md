---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides para Android via Referência de API Java
description: Objeto imutável que contém propriedades efetivas de preenchimento de linha.
type: docs
url: /pt/com.aspose.slides/ilinefillformateffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Objeto imutável que contém propriedades efetivas de preenchimento de linha.

--------------------

Esta interface é usada como parte de [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillType()](#getFillType--) | Retorna o tipo de preenchimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Retorna a cor de um preenchimento sólido. |
| [getGradientFormat()](#getGradientFormat--) | Retorna o formato de preenchimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Retorna o formato de preenchimento de padrão. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se o preenchimento deve ser rotacionado com uma forma. |
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

Retorna a cor de um preenchimento sólido. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
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
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Determina se o preenchimento deve ser rotacionado com uma forma. Somente leitura boolean.

**Retorna:**
boolean