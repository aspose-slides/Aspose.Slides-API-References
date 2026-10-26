---
title: MathBlock
second_title: Aspose.Slides voor Android via Java API Referentie
description: Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint.
type: docs
url: /nl/com.aspose.slides/mathblock/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, expressies, arrays van vergelijkingen of expressies, en formules worden weergegeven door een math block.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initialiseert een nieuwe instantie van de MathBlock-klasse. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Maakt een nieuw MathBlock aan en plaatst het opgegeven element erin |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Maakt een nieuw MathBlock aan en plaatst de opgegeven elementen erin |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Haalt het aantal child math elements op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt een IMathElement op of stelt deze in op de opgegeven index. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Haalt een IMathElement op of stelt deze in op de opgegeven index. |
| [isReadOnly()](#isReadOnly--) | Retourneert false omdat de collectie van kind-elementen kan worden gewijzigd. |
| [getChildren()](#getChildren--) | Haalt kind-elementen op |
| [getParent_Immediate()](#getParent-Immediate--) | Retourneert Parent_Immediate-object. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Voegt een math-element toe aan het einde van de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Bepaalt of de collectie een specifieke waarde bevat. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopieert naar opgegeven array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Bepaalt de index van een specifiek math-element in de collectie. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Voegt een MathElement in de collectie in op de opgegeven index. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Voegt een mathematisch element samen met dit MathBlock |
| [join(String mathText)](#join-java.lang.String-) | Voegt een mathematische tekst samen met dit MathBlock |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Voegt een ander mathematisch blok samen met dit blok |
| [delimit(char separatorCharacter)](#delimit-char-) | Scheidt kind-elementen met een scheidingsteken (zonder de haakjes) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omhult kind-elementen van dit blok met gespecificeerde tekens, zoals haakjes of andere tekens als omlijsting |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Omhult kind-elementen van dit blok met gespecificeerde tekens, zoals haakjes of andere, en scheidt met een scheidingsteken |
| [toMathArray()](#toMathArray--) | Plaatst kind-elementen in een verticale array |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Slaat de inhoud van deze [MathBlock](../../com.aspose.slides/mathblock) op als MathML |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initialiseert een nieuwe instantie van de MathBlock-klasse.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Maakt een nieuw MathBlock aan en plaatst het opgegeven element erin

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Het wiskundige element om in het blok te plaatsen |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Maakt een nieuw MathBlock aan en plaatst de opgegeven elementen erin

--------------------

> ```
> Voorbeeld:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Wiskundige elementen om in het blok te plaatsen |

### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het aantal child math elements op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Retourneert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Haalt een IMathElement op of stelt deze in op de opgegeven index.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het item |

**Retourneert:**
[IMathElement](../../com.aspose.slides/imathelement) - Het wiskundige element.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Haalt een IMathElement op of stelt deze in op de opgegeven index.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het item |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Het wiskundige element. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Retourneert false omdat de collectie van kind-elementen kan worden gewijzigd.

**Retourneert:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haalt kind-elementen op

**Retourneert:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Voegt een math-element toe aan het einde van de collectie.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het IMathElement dat aan het einde van de collectie moet worden toegevoegd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Bepaalt of de collectie een specifieke waarde bevat.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het object om in de collectie te zoeken. |

**Retourneert:**
boolean - true als het item in de collectie wordt gevonden; anders false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Kopieert naar opgegeven array.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array om naar te kopiëren. |
| arrayIndex | int | Index om te beginnen met kopiëren. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Verwijdert het eerste voorkomen van een specifiek object uit de collectie.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het object om uit de collectie te verwijderen. |

**Retourneert:**
boolean - true als het item succesvol is verwijderd uit de collectie; anders false. Deze methode retourneert ook false als het item niet in de oorspronkelijke collectie wordt gevonden.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.IEnumerator - Een java.util.Iterator voor de volledige collectie.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Bepaalt de index van een specifiek math-element in de collectie.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het element om in de collectie te zoeken. |

**Retourneert:**
int - De index van het item als het wordt gevonden in de collectie; anders -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Voegt een MathElement in de collectie in op de opgegeven index.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop MathElement moet worden ingevoegd. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Het MathElement om in te voegen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element dat moet worden verwijderd. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Voegt een mathematisch element samen met dit MathBlock

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Het element dat moet worden samengevoegd |

**Retourneert:**
[IMathBlock](../../com.aspose.slides/imathblock) - De huidige instantie van IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Voegt een mathematische tekst samen met dit MathBlock

--------------------

> ```
> Voorbeeld:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | java.lang.String | Wiskundige tekst die moet worden samengevoegd |

**Retourneert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Een nieuw IMathBlock dat deze instantie en het opgegeven argument bevat
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Voegt een ander mathematisch blok samen met dit blok

--------------------

> ```
> Voorbeeld:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Het samenvoegende blok |

**Retourneert:**
[IMathBlock](../../com.aspose.slides/imathblock) - dit wiskundige blok na het samenvoegen
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Scheidt kind-elementen met een scheidingsteken (zonder de haakjes)

--------------------

> ```
> Voorbeeld:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char | Scheidingsteken |

**Retourneert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het math-element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omhult kind-elementen van dit blok met gespecificeerde tekens, zoals haakjes of andere tekens als omlijsting

--------------------

> ```
> Voorbeeld:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char | Beginteken (meestal linker haakje) |
| endingCharacter | char | Eindteken (meestal rechter haakje) |

**Retourneert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het math-element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat de opgegeven tekens als omlijsting bevat
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Omhult kind-elementen van dit blok met gespecificeerde tekens, zoals haakjes of andere, als omlijsting en scheidt met een scheidingsteken

--------------------

> ```
> Voorbeeld:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char | Beginteken (meestal linker haakje) |
| endingCharacter | char | Eindteken (meestal rechter haakje) |
| separatorCharacter | char | Scheidingsteken |

**Retourneert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het math-element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat de opgegeven tekens als omlijsting en scheidingsteken bevat
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Plaatst kind-elementen in een verticale array

--------------------

> ```
> Voorbeeld:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Retourneert:**
[IMathArray](../../com.aspose.slides/imatharray) - Nieuwe instantie van type [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Slaat de inhoud van deze [MathBlock](../../com.aspose.slides/mathblock) op als MathML

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |