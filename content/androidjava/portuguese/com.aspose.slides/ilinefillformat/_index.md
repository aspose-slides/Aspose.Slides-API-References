---
title: ILineFillFormat
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa propriedades para preenchimento de linhas.
type: docs
url: /pt/com.aspose.slides/ilinefillformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Representa propriedades para preenchimento de linhas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillType()](#getFillType--) | Retorna ou define o tipo de preenchimento. |
| [setFillType(byte value)](#setFillType-byte-) | Retorna ou define o tipo de preenchimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Retorna a cor de um preenchimento sólido. |
| [getGradientFormat()](#getGradientFormat--) | Retorna o formato de preenchimento de gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Retorna o formato de preenchimento de padrão. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se o preenchimento deve ser girado com uma forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se o preenchimento deve ser girado com uma forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Retorna ou define o tipo de preenchimento. Leitura/gravação [FillType](../../com.aspose.slides/filltype).

**Retorna:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Retorna ou define o tipo de preenchimento. Leitura/gravação [FillType](../../com.aspose.slides/filltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Retorna a cor de um preenchimento sólido. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Retorna o formato de preenchimento de gradiente. Somente leitura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retorna:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Retorna o formato de preenchimento de padrão. Somente leitura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retorna:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Determina se o preenchimento deve ser girado com uma forma. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Determina se o preenchimento deve ser girado com uma forma. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |