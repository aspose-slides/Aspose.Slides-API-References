---
title: IMathDelimiter
second_title: Aspose.Slides for Android Java API-referencia
description: Megadja a delimiter objektumot, amely nyitó és záró karakterekből áll, például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak, valamint egy vagy több matematikai elemet tartalmaz belül, amelyeket egy megadott karakterrel választanak el.
type: docs
url: /hu/com.aspose.slides/imathdelimiter/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Megadja a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, amelyeket egy meghatározott karakterrel választanak el. Példák: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character meghatározza a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character meghatározza a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character meghatározza a befejező, vagy záró delimiter karaktert. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character meghatározza a befejező, vagy záró delimiter karaktert. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Amikor true, a delimiter függőlegesen nő, hogy illeszkedjen az operandus magasságához. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Amikor true, a delimiter függőlegesen nő, hogy illeszkedjen az operandus magasságához. |
| [getDelimiterShape()](#getDelimiterShape--) | Meghatározza a delimiter objektumban lévő delimiter alakját. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Meghatározza a delimiter objektumban lévő delimiter alakját. |
| [delimit(char separatorCharacter)](#delimit-char-) | Argumentumokat a megadott delimiter karakterrel választ el |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el

--------------------

> ```
> Példa:
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

Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. A matematikai delimiterek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett érték: '('.

--------------------

> ```
> Példa:
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

Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. A matematikai delimiterek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett érték: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character meghatározza a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Az alapértelmezett: '|'.

--------------------

> ```
> Példa:
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

Delimiter Separator Character meghatározza a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Az alapértelmezett: '|'.

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Delimiter Ending Character meghatározza a befejező, vagy záró delimiter karaktert. A matematikai delimiterek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett érték: ')'.

--------------------

> ```
> Példa:
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

Delimiter Ending Character meghatározza a befejező, vagy záró delimiter karaktert. A matematikai delimiterek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett érték: ')'.

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Amikor true, a delimiter függőlegesen nő, hogy illeszkedjen az operandus magasságához. Az alapértelmezett érték true

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Visszatér:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter Amikor true, a delimiter függőlegesen nő, hogy illeszkedjen az operandus magasságához. Az alapértelmezett érték true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Meghatározza a delimiter objektumban lévő delimiter alakját. Amikor MathDelimiterShape.Centered, a delimiterok a matematikai szöveg tengelye körül középre helyeződnek, és még mindig úgy illeszkednek, hogy lefedjék a tartalom teljes magasságát. Amikor MathDelimiterShape.Match, a magasságuk és alakjuk pontosan a tartalomnak megfelelően módosul.

--------------------

> ```
> Példa:
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

Meghatározza a delimiter objektumban lévő delimiter alakját. Amikor MathDelimiterShape.Centered, a delimiterok a matematikai szöveg tengelye körül középre helyeződnek, és még mindig úgy illeszkednek, hogy lefedjék a tartalom teljes magasságát. Amikor MathDelimiterShape.Match, a magasságuk és alakjuk pontosan a tartalomnak megfelelően módosul.

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Argumentumokat a megadott delimiter karakterrel választ el

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | delimiter karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ez az objektum a delimiter karakter alkalmazása után