---
title: IMathBlock
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha.
type: docs
url: /pt/com.aspose.slides/imathblock/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha. Todas as zonas matemáticas, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas são representadas por um bloco matemático.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita todos os elementos filhos com o caractere separador (sem os colchetes) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros, como moldura e delimita com um caractere separador |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Une outro bloco matemático a este |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva o conteúdo deste [IMathBlock](../../com.aspose.slides/imathblock) como MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimita todos os elementos filhos com o caractere separador (sem os colchetes)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char | Caractere usado como separador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instância do elemento IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros, como moldura e delimita com um caractere separador

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char | Caractere final (geralmente colchete direito) |
| separatorCharacter | char | Caractere separador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - O elemento matemático do tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que inclui os caracteres especificados como moldura e delimitador
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Une outro bloco matemático a este

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | O bloco de junção |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - este bloco matemático após a união
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Salva o conteúdo deste [IMathBlock](../../com.aspose.slides/imathblock) como MathML

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |