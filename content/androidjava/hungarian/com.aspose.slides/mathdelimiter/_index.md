---
title: MathDelimiter
second_title: Aspose.Slides Android számára a Java API hivatkozás
description: Megadja a delimiter objektumot, amely nyitó és záró karakterekből áll, például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakterrel választanak el.
type: docs
url: /hu/com.aspose.slides/mathdelimiter/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Megadja a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakterrel választanak el. Példák: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicializálja a MathDelimiter-t a megadott elemmel, mint egyetlen alapargumentummal |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getArguments()](#getArguments--) | Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el |
| [getBeginningCharacter()](#getBeginningCharacter--) | A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. |
| [getEndingCharacter()](#getEndingCharacter--) | A Delimiter Ending Character meghatározza a záró delimiter karaktert. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | A Delimiter Ending Character meghatározza a záró delimiter karaktert. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiter függőlegesen nő, hogy megfeleljen az operandus magasságának. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiter függőlegesen nő, hogy megfeleljen az operandus magasságának. |
| [getDelimiterShape()](#getDelimiterShape--) | Meghatározza a delimiter alakját a delimiter objektumban. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Meghatározza a delimiter alakját a delimiter objektumban. |
| [delimit(char separatorCharacter)](#delimit-char-) | Argumentumokat választ el a megadott delimiter karakter segítségével |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Egy matematikai elemet zár be a megadott karakterekkel, például zárójelekkel vagy egyéb karakterekkel keretként |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Inicializálja a MathDelimiter-t a megadott elemmel, mint egyetlen alapargumentummal

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az az alap elem, amelyhez a delimiter alkalmazásra kerül. Lehet null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Visszatérési érték:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```


A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. Matematikai delimiter-ek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Visszatérési érték:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```


A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó delimiter karaktert. Matematikai delimiter-ek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('.

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
public final char getSeparatorCharacter()
```


A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Visszatérési érték:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```


A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'.

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
public final char getEndingCharacter()
```


A Delimiter Ending Character meghatározza a záró delimiter karaktert. Matematikai delimiter-ek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Visszatérési érték:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```


A Delimiter Ending Character meghatározza a záró delimiter karaktert. Matematikai delimiter-ek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```


Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiter függőlegesen nő, hogy megfeleljen az operandus magasságának. Alapértelmezett érték: true

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Visszatérési érték:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiter függőlegesen nő, hogy megfeleljen az operandus magasságának. Alapértelmezett érték: true

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
public final int getDelimiterShape()
```


Meghatározza a delimiter-ek alakját a delimiter objektumban. Ha a MathDelimiterShape.Centered, a delimiter-ek a matematikai szöveg tengelye köré középre vannak igazítva, és a tartalom teljes magasságához igazodnak. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Visszatérési érték:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```


Meghatározza a delimiter-ek alakját a delimiter objektumban. Ha a MathDelimiterShape.Centered, a delimiter-ek a matematikai szöveg tengelye köré középre vannak igazítva, és a tartalom teljes magasságához igazodnak. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik.

--------------------

> ```
> Példa:
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
public final IMathDelimiter delimit(char separatorCharacter)
```


Argumentumokat választ el a megadott delimiter karakter segítségével

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char | delimiter karakter |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ez az objektum a delimiter karakter alkalmazása után
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Egy matematikai elemet zár be a megadott karakterekkel, például zárójelekkel vagy egyéb karakterekkel keretként

--------------------

> ```
> Példa:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ha a beginningCharacter és endingCharacter null, a megfelelő tulajdonságok csak értéket kapnak, és új objektum nem jön létre (visszaadja ezt az példányt). Egyébként új Delimiter típusú matematikai elemet ad vissza, amely a megadott karaktereket keretként tartalmazza, és ez a [MathDelimiter](../../com.aspose.slides/mathdelimiter) példány keretezett állapotban.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vezérlő karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps