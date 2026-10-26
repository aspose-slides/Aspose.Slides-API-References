---
title: IMathBlock
second_title: Referencia de API de Aspose.Slides para Java
description: Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en una línea propia.
type: docs
url: /es/com.aspose.slides/imathblock/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en una línea propia. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits all child elements with separator character (without the brackets) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Joins another mathematical block with this one |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Saves content of this [IMathBlock](../../com.aspose.slides/imathblock) as MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimita todos los elementos hijos con el carácter separador (sin los corchetes)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char | Character used as a separator |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instancia del elemento IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros, como marco y los delimita con un carácter separador

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |
| separatorCharacter | char | Separator character |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing and delimiter
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Une otro bloque matemático con este

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | The joining block |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - este bloque matemático después de la unión
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Guarda el contenido de este [IMathBlock](../../com.aspose.slides/imathblock) como MathML

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |