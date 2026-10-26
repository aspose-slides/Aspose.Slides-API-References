---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Esta classe contém as propriedades de formatação de parágrafo.
type: docs
url: /pt/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), todas as propriedades desta classe são graváveis.

--------------------

Esta classe é usada para retornar e manipular as propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "indefinido".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) que retorna uma instância [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Métodos

| Método | Descrição |
| --- | --- |
| [getBullet()](#getBullet--) | Retorna o formato de marcador do parágrafo. |
| [getDepth()](#getDepth--) | Retorna ou define a profundidade do parágrafo. |
| [setDepth(short value)](#setDepth-short-) | Retorna ou define a profundidade do parágrafo. |
| [getAlignment()](#getAlignment--) | Retorna ou define o alinhamento de texto em um parágrafo sem herança. |
| [setAlignment(int value)](#setAlignment-int-) | Retorna ou define o alinhamento de texto em um parágrafo sem herança. |
| [getSpaceWithin()](#getSpaceWithin--) | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. |
| [getSpaceAfter()](#getSpaceAfter--) | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se a quebra de linha Leste-asiática é usada em um parágrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina se a quebra de linha Leste-asiática é usada em um parágrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se a quebra de linha latina é usada em um parágrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina se a quebra de linha latina é usada em um parágrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se a pontuação suspensa é usada em um parágrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina se a pontuação suspensa é usada em um parágrafo. |
| [getMarginLeft()](#getMarginLeft--) | Retorna ou define a margem esquerda em um parágrafo sem herança. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Retorna ou define a margem esquerda em um parágrafo sem herança. |
| [getMarginRight()](#getMarginRight--) | Retorna ou define a margem direita em um parágrafo sem herança. |
| [setMarginRight(float value)](#setMarginRight-float-) | Retorna ou define a margem direita em um parágrafo sem herança. |
| [getIndent()](#getIndent--) | Retorna ou define a indentação da primeira linha/indentação suspensa do parágrafo sem herança. |
| [setIndent(float value)](#setIndent-float-) | Retorna ou define a indentação da primeira linha/indentação suspensa do parágrafo sem herança. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retorna ou define o tamanho de tabulação padrão sem herança. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Retorna ou define o tamanho de tabulação padrão sem herança. |
| [getTabs()](#getTabs--) | Retorna as tabulações de um parágrafo. |
| [getFontAlignment()](#getFontAlignment--) | Retorna ou define um alinhamento de fonte em um parágrafo sem herança. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Retorna ou define um alinhamento de fonte em um parágrafo sem herança. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retorna o formato de porção padrão de um parágrafo. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de parágrafo efetivos com a herança aplicada. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Retorna o formato de marcador do parágrafo. Somente leitura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retorna:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Retorna ou define a profundidade do parágrafo. Valor 0 significa valor indefinido. Leitura/gravação short.

**Retorna:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Retorna ou define a profundidade do parágrafo. Valor 0 significa valor indefinido. Leitura/gravação short.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Retorna ou define o alinhamento de texto em um parágrafo sem herança. Leitura/gravação [TextAlignment](../../com.aspose.slides/textalignment).

**Retorna:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Retorna ou define o alinhamento de texto em um parágrafo sem herança. Leitura/gravação [TextAlignment](../../com.aspose.slides/textalignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa percentual, negativo - tamanho em pontos. Nenhuma herança aplicada. Leitura/gravação float.

**Retorna:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa percentual, negativo - tamanho em pontos. Nenhuma herança aplicada. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float.

**Retorna:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float.

**Retorna:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Determina se a quebra de linha Leste-asiática é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Determina se a quebra de linha Leste-asiática é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Retorna ou define a margem esquerda em um parágrafo sem herança. Leitura/gravação float.

**Retorna:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Retorna ou define a margem esquerda em um parágrafo sem herança. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Retorna ou define a margem direita em um parágrafo sem herança. Leitura/gravação float.

**Retorna:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Retorna ou define a margem direita em um parágrafo sem herança. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Retorna ou define a indentação da primeira linha/indentação suspensa do parágrafo sem herança. Indentação suspensa pode ser definida com valores negativos. Leitura/gravação float.

**Retorna:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Retorna ou define a indentação da primeira linha/indentação suspensa do parágrafo sem herança. Indentação suspensa pode ser definida com valores negativos. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Retorna ou define o tamanho de tabulação padrão sem herança. Leitura/gravação float.

**Retorna:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Retorna ou define o tamanho de tabulação padrão sem herança. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Retorna as tabulações de um parágrafo. Nenhuma herança aplicada. Somente leitura [ITabCollection](../../com.aspose.slides/itabcollection).

**Retorna:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Retorna ou define um alinhamento de fonte em um parágrafo sem herança. Leitura/gravação [FontAlignment](../../com.aspose.slides/fontalignment).

**Retorna:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Retorna ou define um alinhamento de fonte em um parágrafo sem herança. Leitura/gravação [FontAlignment](../../com.aspose.slides/fontalignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Retorna o formato de porção padrão de um parágrafo. Nenhuma herança aplicada. Somente leitura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Obtém os dados de formatação de parágrafo efetivos com a herança aplicada.

**Retorna:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).