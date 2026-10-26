---
title: MathBlock
second_title: Aspose.Slides for Android Java API hivatkozás
description: Megad egy matematikai szövegrészt, amely egy MathParagraph-ben található és saját sorban kezdődik.
type: docs
url: /hu/com.aspose.slides/mathblock/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Megad egy matematikai szövegrészt, amely egy MathParagraph-en belül található és saját sorban kezdődik. Minden matematikai zóna, beleértve egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit és képleteket, egy math block által van reprezentálva.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBlock()](#MathBlock--) | Új példányt hoz létre a MathBlock osztályból. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Új matematikai blokkot hoz létre, és a megadott elemet elhelyezi benne. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Új matematikai blokkot hoz létre, és a megadott elemeket elhelyezi benne. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen lévő gyermek matematikai elemek számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | Lekérdezi vagy beállítja az IMathElement-et a megadott indexnél. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Lekérdezi vagy beállítja az IMathElement-et a megadott indexnél. |
| [isReadOnly()](#isReadOnly--) | False értéket ad vissza, mert a gyermek elemek gyűjteménye módosítható. |
| [getChildren()](#getChildren--) | Gyermek elemek lekérdezése |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate objektumot ad vissza. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Matematikai elemet ad a gyűjtemény végéhez. |
| [clear()](#clear--) | Az összes elemet eltávolítja a gyűjteményből. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Másolás a megadott tömbbe. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Az adott objektum első előfordulását eltávolítja a gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterator-t a teljes gyűjteményhez. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Meghatározza egy adott matematikai elem indexét a gyűjteményben. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Beszúr egy MathElement-et a gyűjteménybe a megadott indexnél. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexnél a gyűjteményből. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Egy matematikai elemet összekapcsol ezzel a matematikai blokkal |
| [join(String mathText)](#join-java.lang.String-) | Egy matematikai szöveget összekapcsol ezzel a matematikai blokkal |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Egy másik matematikai blokkot összekapcsol ezzel |
| [delimit(char separatorCharacter)](#delimit-char-) | A gyermek elemeket elválasztó karakterrel (zárójelek nélkül) választja el |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | A gyermek elemeket megadott karakterekkel (pl. zárójelek) keretezi |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | A gyermek elemeket megadott karakterekkel keretezi és elválasztó karakterrel elválasztja |
| [toMathArray()](#toMathArray--) | Gyermek elemeket függőleges tömbbe helyez |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | A [MathBlock](../../com.aspose.slides/mathblock) tartalmát MathML formátumban menti |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Új példányt hoz létre a MathBlock osztályból.

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

Új matematikai blokkot hoz létre, és a megadott elemet elhelyezi benne

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | A blokkba helyezendő matematikai elem |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Új matematikai blokkot hoz létre, és a megadott elemeket elhelyezi benne

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | A blokkba helyezendő matematikai elemek |

### getCount() {#getCount--}
```
public final int getCount()
```

A gyűjteményben ténylegesen lévő gyermek matematikai elemek számát adja vissza. Csak olvasható int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Lekérdezi vagy beállítja az IMathElement-et a megadott indexnél.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A tétel nullához képest indexe |

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement) - A matematikai elem.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Lekérdezi vagy beállítja az IMathElement-et a megadott indexnél.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A tétel nullához képest indexe |
| value | [IMathElement](../../com.aspose.slides/imathelement) | A matematikai elem. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

False értéket ad vissza, mert a gyermek elemek gyűjteménye módosítható.

**Visszatér:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermek elemek lekérdezése

**Visszatér:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate objektumot ad vissza. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Matematikai elemet ad a gyűjtemény végéhez.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A hozzáadandó IMathElement a gyűjtemény végéhez. |

### clear() {#clear--}
```
public final void clear()
```

Az összes elemet eltávolítja a gyűjteményből.

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

Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott értéket.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A keresendő objektum a gyűjteményben. |

**Visszatér:**
boolean - true, ha az elem megtalálható a gyűjteményben; egyébként false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Másolás a megadott tömbbe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | A másolás célja. |
| arrayIndex | int | Az indítási index. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Az adott objektum első előfordulását eltávolítja a gyűjteményből.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A gyűjteményből eltávolítandó objektum. |

**Visszatér:**
boolean - true, ha az elem sikeresen eltávolításra került; egyébként false. Ez a metódus false értéket ad vissza, ha az elem nem található a kiinduló gyűjmentényben.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Egy IGenericEnumerator, amely a gyűjtemény iterálására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Visszaad egy java iterator-t a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.IEnumerator - Egy java.util.Iterator a teljes gyűjteményhez.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Meghatározza egy adott matematikai elem indexét a gyűjteményben.

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A keresendő elem a gyűjteményben. |

**Visszatér:**
int - Az elem indexe, ha megtalálható; egyébként -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Beszúr egy MathElement-et a megadott indexnél a gyűjteménybe.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullához képest index, ahol a MathElement-et be kell illeszteni. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A beszúrandó MathElement. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja az elemet a megadott indexnél a gyűjteményből.

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullához képest eltávolítandó elem indexe. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Egy matematikai elemet összekapcsol ezzel a matematikai blokkal

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | A csatlakoztatandó elem |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - Az IMathBlock aktuális példánya
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Matematikai szöveget csatlakoztat ezzel a matematikai blokkal

--------------------

> ```
> Példa:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | A csatlakoztatandó matematikai szöveg |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - Egy új IMathBlock, amely ezt a példányt és a megadott argumentumot tartalmazza
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Egy másik matematikai blokkot összekapcsol ezzel

--------------------

> ```
> Példa:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | A csatlakoztatandó blokk |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - ez a matematikai blokk a csatlakoztatás után
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

A gyermek elemeket elválasztó karakterrel (zárójelek nélkül) választja el

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char | Elválasztó karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

A gyermek elemeket megadott karakterekkel (pl. zárójelek) keretezi

--------------------

> ```
> Példa:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretezi
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

A gyermek elemeket megadott karakterekkel keretezi és elválasztó karakterrel elválasztja

--------------------

> ```
> Példa:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |
| separatorCharacter | char | Elválasztó karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretezi és elválasztja
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Gyermek elemeket függőleges tömbbe helyez

--------------------

> ```
> Példa:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Visszatér:**
[IMathArray](../../com.aspose.slides/imatharray) - Új példány a [IMathArray](../../com.aspose.slides/imatharray) típusból
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

A [MathBlock](../../com.aspose.slides/mathblock) tartalmát MathML formátumban menti

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |