---
title: IMathDelimiter
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Określa obiekt delimitera składający się z znaków otwierających i zamykających, takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski, oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.
type: docs
url: /pl/com.aspose.slides/imathdelimiter/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Określa obiekt delimitera, składający się z znaków otwierających i zamykających (takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getArguments()](#getArguments--) | Jeden lub więcej elementów matematycznych oddzielonych znakami delimitera |
| [getBeginningCharacter()](#getBeginningCharacter--) | Znak początkowy delimitera określa początkowy, czyli otwierający, znak delimitera. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Znak początkowy delimitera określa początkowy, czyli otwierający, znak delimitera. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Znak separatora delimitera określa znak, który oddziela argumenty w obiekcie delimitera. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Znak separatora delimitera określa znak, który oddziela argumenty w obiekcie delimitera. |
| [getEndingCharacter()](#getEndingCharacter--) | Znak końcowy delimitera określa końcowy, czyli zamykający, znak delimitera. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Znak końcowy delimitera określa końcowy, czyli zamykający, znak delimitera. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Określa rozciąganie znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Określa rozciąganie znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. |
| [getDelimiterShape()](#getDelimiterShape--) | Określa kształt delimiterów w obiekcie delimitera. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Określa kształt delimiterów w obiekcie delimitera. |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddziela argumenty przy użyciu określonego znaku delimitera |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Jeden lub więcej elementów matematycznych oddzielonych znakami delimitera

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Zwraca:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Znak początkowy delimitera określa początkowy, czyli otwierający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Wartość domyślna: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Zwraca:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Znak początkowy delimitera określa początkowy, czyli otwierający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Wartość domyślna: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Znak separatora delimitera określa znak, który oddziela argumenty w obiekcie delimitera. Domyślnie: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Zwraca:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Znak separatora delimitera określa znak, który oddziela argumenty w obiekcie delimitera. Domyślnie: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Znak końcowy delimitera określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Wartość domyślna: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Zwraca:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Znak końcowy delimitera określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy, nawiasy kwadratowe i klamry. Wartość domyślna: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Określa rozciąganie znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. Wartość domyślna to true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Zwraca:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Określa rozciąganie znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. Wartość domyślna to true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Określa kształt delimiterów w obiekcie delimitera. Gdy wartość jest MathDelimiterShape.Centered, delimitery są wyśrodkowane względem osi matematycznej tekstu i nadal mogą być dopasowane do całkowitej wysokości ich zawartości. Gdy wartość jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane, aby dokładnie pasowały do zawartości.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Zwraca:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Określa kształt delimiterów w obiekcie delimitera. Gdy wartość jest MathDelimiterShape.Centered, delimitery są wyśrodkowane względem osi matematycznej tekstu i nadal mogą być dopasowane do całkowitej wysokości ich zawartości. Gdy wartość jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane, aby dokładnie pasowały do zawartości.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Oddziela argumenty przy użyciu określonego znaku delimitera

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char | znak delimitera |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ten obiekt po zastosowaniu znaku delimitera