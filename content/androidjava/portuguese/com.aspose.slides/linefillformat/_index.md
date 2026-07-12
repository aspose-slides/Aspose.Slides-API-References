---
title: LineFillFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa propriedades para preenchimento de linhas.
type: docs
url: /pt/com.aspose.slides/linefillformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as interfaces implementadas:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Representa propriedades para preenchimento de linhas.

## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Retorna ou define o tipo de preenchimento. |
| [setFillType(byte value)](#setFillType-byte-) | Retorna ou define o tipo de preenchimento. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se o preenchimento deve ser girado com uma forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se o preenchimento deve ser girado com uma forma. |
| [getSolidFillColor()](#getSolidFillColor--) | Retorna a cor de um preenchimento sólido. |
| [getGradientFormat()](#getGradientFormat--) | Retorna o formato de preenchimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Retorna o formato de preenchimento de padrão. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Retorna ou define o tipo de preenchimento. Leitura/gravação [FillType](../../com.aspose.slides/filltype).

**Retorna:**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Retorna ou define o tipo de preenchimento. Leitura/gravação [FillType](../../com.aspose.slides/filltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Determina se o preenchimento deve ser girado com uma forma. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Determina se o preenchimento deve ser girado com uma forma. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Retorna a cor de um preenchimento sólido. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Retorna o formato de preenchimento gradiente. Somente leitura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retorna:**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Retorna o formato de preenchimento de padrão. Somente leitura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retorna:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)