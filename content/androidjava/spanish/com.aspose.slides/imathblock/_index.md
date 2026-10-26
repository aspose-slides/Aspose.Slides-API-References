---
title: IMathBlock
second_title: Referencia de API Java de Aspose.Slides para Android
description: Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en una línea propia.
type: docs
url: /es/com.aspose.slides/imathblock/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en una línea propia. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, se representan mediante un bloque matemático.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita todos los elementos hijos con el carácter separador (sin los corchetes) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros, como marco y delimita con un carácter separador |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Une otro bloque matemático con este |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Guarda el contenido de este [IMathBlock](../../com.aspose.slides/imathblock) como MathML |
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
| separatorCharacter | char | Carácter usado como separador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instancia del elemento IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros, como marco y delimita con un carácter separador

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
| beginningCharacter | char | Carácter inicial (normalmente corchete izquierdo) |
| endingCharacter | char | Carácter final (normalmente corchete derecho) |
| separatorCharacter | char | Carácter separador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - El elemento math de tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que incluye los caracteres especificados como marco y delimitador
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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | El bloque que se une |

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
| stream | java.io.OutputStream | Flujo objetivo |