---
title: IMathDelimiter
second_title: Aspose.Slides Java API referencia
description: Meghatározza a határoló objektumot, amely nyitó és záró karakterekből áll, például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak, és egy vagy több matematikai elemet tartalmaz, amelyeket egy meghatározott karakter választ el.
type: docs
url: /hu/com.aspose.slides/imathdelimiter/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Meghatározza a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy meghatározott karakter választ el. Példák: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getArguments()](#getArguments--) | Egy vagy több matematikai elem, amelyet határoló karakterek választanak el |
| [getBeginningCharacter()](#getBeginningCharacter--) | A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó, határoló karaktert. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó, határoló karaktert. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a határoló objektumban. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a határoló objektumban. |
| [getEndingCharacter()](#getEndingCharacter--) | A Delimiter Ending Character meghatározza a záró, vagy végző, határoló karaktert. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | A Delimiter Ending Character meghatározza a záró, vagy végző, határoló karaktert. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. |
| [getDelimiterShape()](#getDelimiterShape--) | Meghatározza a határolók alakját a határoló objektumban. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Meghatározza a határolók alakját a határoló objektumban. |
| [delimit(char separatorCharacter)](#delimit-char-) | Határolja az argumentumokat a megadott határoló karakter segítségével |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Egy vagy több matematikai elem, amelyet határoló karakterek választanak el

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Visszatér:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó, határoló karaktert. Matematikai határolók olyan záró karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Visszatér:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó, határoló karaktert. Matematikai határolók olyan záró karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a határoló objektumban. Alapértelmezett: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Visszatér:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a határoló objektumban. Alapértelmezett: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

A Delimiter Ending Character meghatározza a záró, vagy végző, határoló karaktert. Matematikai határolók olyan záró karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Visszatér:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

A Delimiter Ending Character meghatározza a záró, vagy végző, határoló karaktert. Matematikai határolók olyan záró karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Alapértelmezett érték: true

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
```

**Visszatér:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Alapértelmezett érték: true

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Meghatározza a határolók alakját a határoló objektumban. Ha a MathDelimiterShape.Centered érték, a határolók középre vannak igazítva a matematikai szöveg tengelye körül, és a tartalom teljes magasságához igazíthatók. Ha a MathDelimiterShape.Match érték, magasságuk és alakjuk pontosan a tartalomhoz igazodik.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Visszatér:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Meghatározza a határolók alakját a határoló objektumban. Ha a MathDelimiterShape.Centered érték, a határolók középre vannak igazítva a matematikai szöveg tengelye körül, és a tartalom teljes magasságához igazíthatók. Ha a MathDelimiterShape.Match érték, magasságuk és alakjuk pontosan a tartalomhoz igazodik.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Határolja az argumentumokat a megadott határoló karakter segítségével

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char | határoló karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ez az objektum a határoló karakter alkalmazása után

