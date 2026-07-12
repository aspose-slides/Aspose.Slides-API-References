---
title: LineFormat
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa o formato de uma linha.
type: docs
url: /pt/com.aspose.slides/lineformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Representa o formato de uma linha.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Retorna true se o formato da linha não estiver definido (como recém criado, padrão). |
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
| [getMiterLimit()](#getMiterLimit--) | Retorna ou define o limite de mitra de uma linha. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Retorna ou define o limite de mitra de uma linha. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Retorna ou define o estilo da ponta da seta no início de uma linha. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Retorna ou define o estilo da ponta da seta no início de uma linha. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Retorna e define o estilo da ponta da seta no final de uma linha. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Retorna e define o estilo da ponta da seta no final de uma linha. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Retorna ou define a largura da ponta da seta no início de uma linha. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Retorna ou define a largura da ponta da seta no início de uma linha. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Retorna ou define a largura da ponta da seta no final de uma linha. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Retorna ou define a largura da ponta da seta no final de uma linha. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Retorna ou define o comprimento da ponta da seta no início de uma linha. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Retorna ou define o comprimento da ponta da seta no início de uma linha. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Retorna ou define o comprimento da ponta da seta no final de uma linha. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Retorna ou define o comprimento da ponta da seta no final de uma linha. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determina se duas instâncias de LineFormat são iguais. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de linha efetivos com a herança aplicada. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Read-only long.

**Retorna:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compara com o objeto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retorna:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Retorna true se o formato da linha não estiver definido (como recém criado, padrão). Read-only boolean.

**Retorna:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Retorna o formato de preenchimento de uma linha. Read-only [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retorna:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Retorna o formato de esboço de uma linha. Read-only [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retorna:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Retorna ou define a largura de uma linha. Read/write double.

**Retorna:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Retorna ou define a largura de uma linha. Read/write double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Retorna ou define o estilo de traço da linha. Read/write [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retorna:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Retorna ou define o estilo de traço da linha. Read/write [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Retorna ou define o padrão de traço personalizado. Read/write float[].

**Retorna:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Retorna ou define o padrão de traço personalizado. Read/write float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Retorna ou define o estilo de extremidade da linha. Read/write [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retorna:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Retorna ou define o estilo de extremidade da linha. Read/write [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Retorna ou define o estilo da linha. Read/write [LineStyle](../../com.aspose.slides/linestyle).

**Retorna:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Retorna ou define o estilo da linha. Read/write [LineStyle](../../com.aspose.slides/linestyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Retorna ou define o alinhamento da linha. Read/write [LineAlignment](../../com.aspose.slides/linealignment).

**Retorna:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Retorna ou define o alinhamento da linha. Read/write [LineAlignment](../../com.aspose.slides/linealignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Retorna ou define o estilo de junção das linhas. Read/write [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retorna:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Retorna ou define o estilo de junção das linhas. Read/write [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Retorna ou define o limite de mitra de uma linha. Read/write float.

**Retorna:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Retorna ou define o limite de mitra de uma linha. Read/write float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Retorna ou define o estilo da ponta da seta no início de uma linha. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retorna:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Retorna ou define o estilo da ponta da seta no início de uma linha. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Retorna ou define o estilo da ponta da seta no final de uma linha. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retorna:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Retorna ou define o estilo da ponta da seta no final de uma linha. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Retorna ou define a largura da ponta da seta no início de uma linha. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retorna:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Retorna ou define a largura da ponta da seta no início de uma linha. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Retorna ou define a largura da ponta da seta no final de uma linha. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retorna:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Retorna ou define a largura da ponta da seta no final de uma linha. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Retorna ou define o comprimento da ponta da seta no início de uma linha. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retorna:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Retorna ou define o comprimento da ponta da seta no início de uma linha. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Retorna ou define o comprimento da ponta da seta no final de uma linha. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retorna:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Retorna ou define o comprimento da ponta da seta no final de uma linha. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
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
public final ILineFormatEffectiveData getEffective()
```

Obtém os dados de formatação de linha efetivos com a herança aplicada.

--------------------

> ```
> Este exemplo demonstra como obter as propriedades de formato de linha efetivo da forma.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).