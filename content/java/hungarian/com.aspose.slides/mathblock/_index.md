---
title: MathBlock
second_title: Aspose.Slides Java API Referencia
description: Megad egy matematikai szöveg példányt, amely egy MathParagraph-ban található és saját sorra indul.
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

Megad egy matematikai szöveg példányt, amely a MathParagraph-ban található és saját sorra indul. Az összes matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenlet- vagy kifejezés tömböket és képleteket, a math block által van reprezentálva.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inicializál egy új példányt a MathBlock osztályból. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Létrehoz egy új matematikai blokkot, és a megadott elemet elhelyezi benne |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Létrehoz egy új matematikai blokkot, és a megadott elemeket elhelyezi benne |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Lekéri a gyerek matematikai elemek tényleges számát a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Lekéri vagy beállítja az IMathElementet a megadott indexen. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Lekéri vagy beállítja az IMathElementet a megadott indexen. |
| [isReadOnly()](#isReadOnly--) | Hamis értéket ad vissza, mert a gyerek elemek gyűjteménye módosítható. |
| [getChildren()](#getChildren--) | Gyerek elemek lekérése |
| [getParent_Immediate()](#getParent-Immediate--) | Visszaadja a Parent_Immediate objektumot. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Hozzáad egy matematikai elemet a gyűjtemény végéhez. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Átmásolja a megadott tömbbe. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Meghatározza egy adott matematikai elem indexét a gyűjteményben. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Beszúr egy MathElementet a megadott indexen a gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexen a gyűjteményből. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Összekapcsol egy matematikai elemet ezzel a matematikai blokkal |
| [join(String mathText)](#join-java.lang.String-) | Összekapcsol egy matematikai szöveget ezzel a matematikai blokkal |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Összekapcsol egy másik matematikai blokkot ezzel |
| [delimit(char separatorCharacter)](#delimit-char-) | Gyerek elemeket elválasztó karakterrel határol (zárójelek nélkül) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Gyerek elemeket zárójelek vagy más karakterek közé helyez a keretezéshez |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Gyerek elemeket zárójelek vagy más karakterek közé helyez, és elválasztó karakterrel határol |
| [toMathArray()](#toMathArray--) | Gyerek elemeket függőleges tömbbe helyez |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Elmenti ennek a [MathBlock](../../com.aspose.slides/mathblock) tartalmát MathML-ként |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Inicializál egy új példányt a MathBlock osztályból.

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

Létrehoz egy új matematikai blokkot, és a megadott elemet elhelyezi benne

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

Létrehoz egy új matematikai blokkot, és a megadott elemeket elhelyezi benne

--------------------

> ```
> Példa:
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

Lekéri a gyerek matematikai elemek tényleges számát a gyűjteményben. Csak olvasható int.

--------------------

> ```
> Példa:
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

Lekéri vagy beállítja az IMathElementet a megadott indexen.

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A tétel nulláral kezdődő indexe |

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement) – A matematikai elem.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Lekéri vagy beállítja az IMathElementet a megadott indexen.

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A tétel nulláral kezdődő indexe |
| value | [IMathElement](../../com.aspose.slides/imathelement) | A matematikai elem. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hamis értéket ad vissza, mert a gyerek elemek gyűjteménye módosítható.

**Visszatér:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyerek elemek lekérése

**Visszatér:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Hozzáad egy matematikai elemet a gyűjtemény végéhez.

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A hozzáadandó IMathElement a gyűjtemény végére. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

--------------------

> ```
> Példa:
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
> Példa:
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
boolean – igaz, ha az objektum megtalálható a gyűjteményben; egyébként hamis.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Átmásolja a megadott tömbbe.

--------------------

> ```
> Példa:
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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | A másolandó tömb. |
| arrayIndex | int | Az indext, ahonnan a másolás kezdődik. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Eltávolítja egy adott objektum első előfordulását a gyűjteményből.

--------------------

> ```
> Példa:
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
boolean – igaz, ha az objektum sikeresen eltávolításra került; egyébként hamis. Ha az objektum nem található a gyűjteményben, szintén hamis a visszatérési érték.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> – IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.IEnumerator – java.util.Iterator az egész gyűjteményhez.
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
>  mathBlock.add(new MathRadial(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A keresendő elem a gyűjteményben. |

**Visszatér:**
int – Az elem indexe, ha megtalálható a gyűjteményben; egyébként -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Beszúr egy MathElementet a megadott indexen a gyűjteménybe.

--------------------

> ```
> Példa:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláral kezdődő index, ahová a MathElementet be kell szúrni. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A beszúrandó MathElement. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja az elemet a megadott indexen a gyűjteményből.

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
| index | int | A nulláral kezdődő index, amivel az elemet el kell távolítani. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Összekapcsol egy matematikai elemet ezzel a matematikai blokkal

--------------------

> ```
> Példa:
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
[IMathBlock](../../com.aspose.slides/imathblock) – Az IMathBlock aktuális példánya
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Összekapcsol egy matematikai szöveget ezzel a matematikai blokkal

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
[IMathBlock](../../com.aspose.slides/imathblock) – Új IMathBlock, amely ezt a példányt és a megadott argumentumot tartalmazza
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Összekapcsol egy másik matematikai blokkot ezzel

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
[IMathBlock](../../com.aspose.slides/imathblock) – ez a matematikai blokk a csatlakoztatás után
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Elválasztja a gyerek elemeket a separatorCharacter karakterrel (zárójelek nélkül)

--------------------

> ```
>   



```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char | Elválasztó karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Gyerek elemeket a megadott karakterek közé helyez, például zárójelek vagy más keretező karakterek

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretezőként tartalmazza
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Gyerek elemeket a megadott karakterek közé helyez, például zárójelek vagy más keretező karakterek, és elválasztja őket a separatorCharacter karakterrel

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretezőként és elválasztóként tartalmazza
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Gyerek elemeket függőleges tömbbe helyez

--------------------

> ```
> Példa:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Visszatér:**
[IMathArray](../../com.aspose.slides/imatharray) – Új példány a [IMathArray](../../com.aspose.slides/imatharray) típusból
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Elmenti ennek a [MathBlock](../../com.aspose.slides/mathblock) tartalmát MathML-ként

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |