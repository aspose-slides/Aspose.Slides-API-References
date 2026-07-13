---
title: MathBlock
second_title: Aspose.Slides pro Android prostřednictvím Java API referenčního materiálu
description: Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku.
type: docs
url: /cs/com.aspose.slides/mathblock/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a formulí, jsou reprezentovány matematickým blokem.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inicializuje novou instanci třídy MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Vytvoří nový matematický blok a vloží do něj zadaný prvek |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Vytvoří nový matematický blok a vloží do něj zadané prvky |
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Získá počet podřízených matematických prvků, které jsou ve skutečnosti obsaženy v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá nebo nastaví IMathElement na zadaném indexu. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Získá nebo nastaví IMathElement na zadaném indexu. |
| [isReadOnly()](#isReadOnly--) | Vrací false, protože kolekci podřízených prvků lze upravovat. |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
| [getParent_Immediate()](#getParent-Immediate--) | Vrací objekt Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Přidá matematický prvek na konec kolekce. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Určuje, zda kolekce obsahuje konkrétní hodnotu. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopíruje do zadaného pole. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Určuje index konkrétního matematického prvku v kolekci. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Vloží MathElement do kolekce na zadaném indexu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Spojí matematický prvek s tímto matematickým blokem |
| [join(String mathText)](#join-java.lang.String-) | Spojí matematický text s tímto matematickým blokem |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Spojí další matematický blok s tímto |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddělí podřízené prvky pomocí oddělovače (bez závorek) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Obalí podřízené prvky tohoto bloku ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámování |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Obalí podřízené prvky tohoto bloku ve specifikovaných znacích (např. závorky) a oddělí je pomocí oddělovače |
| [toMathArray()](#toMathArray--) | Umístí podřízené prvky do svislého pole |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Uloží obsah tohoto [MathBlock](../../com.aspose.slides/mathblock) jako MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```


Inicializuje novou instanci třídy MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```


Vytvoří nový matematický blok a vloží do něj zadaný prvek

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Matematický prvek, který se má vložit do bloku |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```


Vytvoří nový matematický blok a vloží do něj zadané prvky

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Matematické prvky, které se mají vložit do bloku |

### getCount() {#getCount--}
```
public final int getCount()
```


Získá počet podřízených matematických prvků, které jsou ve skutečnosti obsaženy v kolekci. Read-only int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```


Získá nebo nastaví IMathElement na zadaném indexu.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index položky |

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement) - Matematický prvek.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```


Získá nebo nastaví IMathElement na zadaném indexu.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index položky |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Matematický prvek. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Vrací false, protože kolekci podřízených prvků lze upravovat.

**Vrací:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Read-only IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```


Přidá matematický prvek na konec kolekce.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement, který se má přidat na konec kolekce. |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny prvky z kolekce.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```


Určuje, zda kolekce obsahuje konkrétní hodnotu.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objekt, který se má v kolekci vyhledat. |

**Vrací:**
boolean - true, pokud je položka v kolekci nalezena; jinak false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```


Kopíruje do zadaného pole.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IMathElement[]](../../com.aspose.slides/imathelement) | Pole, do kterého se má kopírovat. |
| arrayIndex | int | Index, od kterého se začne kopírovat. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```


Odstraní první výskyt konkrétního objektu z kolekce.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objekt, který se má z kolekce odstranit. |

**Vrací:**
boolean - true, pokud byla položka úspěšně odstraněna z kolekce; jinak false. Tato metoda také vrací false, pokud položka v původní kolekci není nalezena.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.IEnumerator - An java.util.Iterator for the entire collection.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```


Určuje index konkrétního matematického prvku v kolekci.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Prvek, který se má v kolekci vyhledat. |

**Vrací:**
int - Index položky, pokud je v kolekci nalezena; jinak -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```


Vloží MathElement do kolekce na zadaném indexu.

--------------------

> ```
> Příklad:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který má být MathElement vložen. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement, který má být vložen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní prvek na zadaném indexu kolekce.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index položky, která se má odstranit. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


Spojí matematický prvek s tímto matematickým blokem

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Prvek, který má být spojen |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - Aktuální instance IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```


Spojí matematický text s tímto matematickým blokem

--------------------

> ```
> Příklad:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | java.lang.String | Matematický text, který má být spojen |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - Nový IMathBlock obsahující tuto instanci a zadaný argument
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```


Spojí další matematický blok s tímto

--------------------

> ```
> Příklad:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Spojovací blok |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - tento matematický blok po spojení
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```


Oddělí podřízené prvky pomocí oddělovače (bez závorek)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char | Oddělovač |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Math element typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Obalí podřízené prvky tohoto bloku ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámování

--------------------

> ```
> Příklad:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char | Ukončovací znak (obvykle pravá závorka) |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Math element typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) který zahrnuje specifikované znaky jako rámování
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Obalí podřízené prvky tohoto bloku ve specifikovaných znacích, jako jsou závorky nebo jiné jako rámování a oddělí je pomocí oddělovače

--------------------

> ```
> Příklad:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char | Ukončovací znak (obvykle pravá závorka) |
| separatorCharacter | char | Oddělovač |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Math element typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) který zahrnuje specifikované znaky jako rámování a oddělovač
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```


Umístí podřízené prvky do svislého pole

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Vrací:**
[IMathArray](../../com.aspose.slides/imatharray) - Nová instance typu [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


Uloží obsah tohoto [MathBlock](../../com.aspose.slides/mathblock) jako MathML

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový stream |