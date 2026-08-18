---
title: IFillFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa opções de formatação de preenchimento.
type: docs
url: /pt/com.aspose.slides/ifillformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Representa opções de formatação de preenchimento.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillType()](#getFillType--) | Retorna ou define o tipo de preenchimento. |
| [setFillType(byte value)](#setFillType-byte-) | Retorna ou define o tipo de preenchimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Retorna a cor de preenchimento. |
| [getGradientFormat()](#getGradientFormat--) | Retorna o formato de preenchimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Retorna o formato de preenchimento com padrão. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retorna o formato de preenchimento de imagem. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se o preenchimento deve ser rotacionado com a forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se o preenchimento deve ser rotacionado com a forma. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de preenchimento efetivos com a herança aplicada. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Retorna ou define o tipo de preenchimento. Leitura/Gravação [FillType](../../com.aspose.slides/filltype).

**Retorna:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Retorna ou define o tipo de preenchimento. Leitura/Gravação [FillType](../../com.aspose.slides/filltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Retorna a cor de preenchimento. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Retorna o formato de preenchimento gradiente. Somente leitura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retorna:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Retorna o formato de preenchimento com padrão. Somente leitura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retorna:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Retorna o formato de preenchimento de imagem. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Determina se o preenchimento deve ser rotacionado com a forma. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Determina se o preenchimento deve ser rotacionado com a forma. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Obtém os dados de formatação de preenchimento efetivos com a herança aplicada.

**Retorna:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).