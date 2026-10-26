---
title: ILineFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o formato de uma linha.
type: docs
url: /pt/com.aspose.slides/ilineformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Representa o formato de uma linha.
## Métodos

| Método | Descrição |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Retorna verdadeiro se o formato da linha não estiver definido (como recém criado, padrão). |
| [getFillFormat()](#getFillFormat--) | Retorna o formato de preenchimento de uma linha. |
| [getSketchFormat()](#getSketchFormat--) | Retorna o formato de esboço de uma linha. |
| [getWidth()](#getWidth--) | Retorna ou define a largura de uma linha. |
| [setWidth(double value)](#setWidth-double-) | Retorna ou define a largura de uma linha. |
| [getDashStyle()](#getDashStyle--) | Retorna ou define o estilo de traço da linha. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Retorna ou define o estilo de traço da linha. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Retorna ou define o padrão de traço personalizado. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Retorna ou define o padrão de traço personalizado. |
| [getCapStyle()](#getCapStyle--) | Retorna ou define o estilo de extremidade da linha. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Retorna ou define o estilo de extremidade da linha. |
| [getStyle()](#getStyle--) | Retorna ou define o estilo da linha. |
| [setStyle(byte value)](#setStyle-byte-) | Retorna ou define o estilo da linha. |
| [getAlignment()](#getAlignment--) | Retorna ou define o alinhamento da linha. |
| [setAlignment(byte value)](#setAlignment-byte-) | Retorna ou define o alinhamento da linha. |
| [getJoinStyle()](#getJoinStyle--) | Retorna ou define o estilo de junção das linhas. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Retorna ou define o estilo de junção das linhas. |
| [getMiterLimit()](#getMiterLimit--) | Retorna ou define o limite de chanfradura de uma linha. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Retorna ou define o limite de chanfradura de uma linha. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Retorna ou define o estilo da ponta da seta no início de uma linha. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Retorna ou define o estilo da ponta da seta no início de uma linha. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Retorna ou define o estilo da ponta da seta no final de uma linha. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Retorna ou define o estilo da ponta da seta no final de uma linha. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Retorna ou define a largura da ponta da seta no início de uma linha. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Retorna ou define a largura da ponta da seta no início de uma linha. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Retorna ou define a largura da ponta da seta no final de uma linha. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Retorna ou define a largura da ponta da seta no final de uma linha. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Retorna ou define o comprimento da ponta da seta no início de uma linha. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Retorna ou define o comprimento da ponta da seta no início de uma linha. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Retorna ou define o comprimento da ponta da seta no final de uma linha. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Retorna ou define o comprimento da ponta da seta no final de uma linha. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determina se duas instâncias de LineFormat são iguais. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de linha efetiva com a herança aplicada. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Retorna true se o formato da linha não estiver definido (como recém criado, padrão). Somente leitura boolean.

**Retorna:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Retorna o formato de preenchimento de uma linha. Somente leitura [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retorna:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Retorna o formato de esboço de uma linha. Somente leitura [ISketchFormat](../../com.aspose.slides/isketchformat).

**Retorna:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Retorna ou define a largura de uma linha. Leitura/Gravação double.

**Retorna:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Retorna ou define a largura de uma linha. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Retorna ou define o estilo de traço da linha. Leitura/Gravação [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retorna:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Retorna ou define o estilo de traço da linha. Leitura/Gravação [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Retorna ou define o padrão de traço personalizado. Leitura/Gravação float[].

**Retorna:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Retorna ou define o padrão de traço personalizado. Leitura/Gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Retorna ou define o estilo de extremidade da linha. Leitura/Gravação [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retorna:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Retorna ou define o estilo de extremidade da linha. Leitura/Gravação [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Retorna ou define o estilo da linha. Leitura/Gravação [LineStyle](../../com.aspose.slides/linestyle).

**Retorna:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Retorna ou define o estilo da linha. Leitura/Gravação [LineStyle](../../com.aspose.slides/linestyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Retorna ou define o alinhamento da linha. Leitura/Gravação [LineAlignment](../../com.aspose.slides/linealignment).

**Retorna:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Retorna ou define o alinhamento da linha. Leitura/Gravação [LineAlignment](../../com.aspose.slides/linealignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Retorna ou define o estilo de junção das linhas. Leitura/Gravação [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retorna:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Retorna ou define o estilo de junção das linhas. Leitura/Gravação [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Retorna ou define o limite de chanfradura de uma linha. Leitura/Gravação float.

**Retorna:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Retorna ou define o limite de chanfradura de uma linha. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Retorna ou define o estilo da ponta da seta no início de uma linha. Leitura/Gravação [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retorna:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Retorna ou define o estilo da ponta da seta no início de uma linha. Leitura/Gravação [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Retorna ou define o estilo da ponta da seta no final de uma linha. Leitura/Gravação [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retorna:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Retorna ou define o estilo da ponta da seta no final de uma linha. Leitura/Gravação [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Retorna ou define a largura da ponta da seta no início de uma linha. Leitura/Gravação [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retorna:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Retorna ou define a largura da ponta da seta no início de uma linha. Leitura/Gravação [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Retorna ou define a largura da ponta da seta no final de uma linha. Leitura/Gravação [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retorna:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Retorna ou define a largura da ponta da seta no final de uma linha. Leitura/Gravação [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Retorna ou define o comprimento da ponta da seta no início de uma linha. Leitura/Gravação [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retorna:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Retorna ou define o comprimento da ponta da seta no início de uma linha. Leitura/Gravação [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Retorna ou define o comprimento da ponta da seta no final de uma linha. Leitura/Gravação [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retorna:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Retorna ou define o comprimento da ponta da seta no final de uma linha. Leitura/Gravação [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Determina se duas instâncias de LineFormat são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | O LineFormat a ser comparado com o LineFormat atual. |

**Retorna:**
boolean - **true** se o LineFormat especificado for igual ao LineFormat atual; caso contrário, **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Obtém os dados de formatação de linha efetiva com a herança aplicada.

**Retorna:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Um [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).