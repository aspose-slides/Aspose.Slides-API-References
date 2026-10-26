---
title: MathBlock
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar en instans av matematisk text som finns i ett MathParagraph och startar på en egen rad.
type: docs
url: /sv/com.aspose.slides/mathblock/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Specificerar en instans av matematisk text som finns i ett MathParagraph och startar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, arrayer av ekvationer eller uttryck och formler representeras av math block.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initierar en ny instans av MathBlock-klassen. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Skapar ett nytt matematiskt block och placerar det angivna elementet i det. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Skapar ett nytt matematiskt block och placerar de angivna elementen i det. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet underordnade matematiska element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar eller sätter IMathElement på det angivna indexet. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Hämtar eller sätter IMathElement på det angivna indexet. |
| [isReadOnly()](#isReadOnly--) | Returnerar false eftersom samlingen av underordnade element kan modifieras. |
| [getChildren()](#getChildren--) | Hämta underordnade element |
| [getParent_Immediate()](#getParent-Immediate--) | Returnerar Parent_Immediate-objektet. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Lägger till ett matematiskt element i slutet av samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Avgör om samlingen innehåller ett specifikt värde. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopiera till angiven array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar igenom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Avgör index för ett specifikt matematiskt element i samlingen. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Infogar ett MathElement i samlingen på det angivna indexet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Förenar ett matematiskt element med detta matematiska block |
| [join(String mathText)](#join-java.lang.String-) | Förenar en matematisk text med detta matematiska block |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Förenar ett annat matematiskt block med detta |
| [delimit(char separatorCharacter)](#delimit-char-) | Avgränsar underordnade element med separator-tecken (utan hakparenteserna). |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Innesluter underordnade element i detta block med angivna tecken, såsom parenteser eller andra tecken, som ram. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Innesluter underordnade element i detta block med angivna tecken, såsom parenteser eller andra, som ram och avgränsar med ett separator-tecken. |
| [toMathArray()](#toMathArray--) | Placera underordnade element i en vertikal matris |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Sparar innehållet av denna [MathBlock](../../com.aspose.slides/mathblock) som MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initierar en ny instans av MathBlock-klassen.

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

Skapar ett nytt matematiskt block och placerar det angivna elementet i det.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Det matematiska elementet som ska placeras i blocket. |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Skapar ett nytt matematiskt block och placerar de angivna elementen i det.

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Matematiska element som ska placeras i blocket. |

### getCount() {#getCount--}
```
public final int getCount()
```

Hämtar antalet underordnade matematiska element som faktiskt finns i samlingen. Skrivskyddad int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Hämtar eller sätter IMathElement på det angivna indexet.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet. |

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement) - Det matematiska elementet.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Hämtar eller sätter IMathElement på det angivna indexet.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet. |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Det matematiska elementet. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Returnerar false eftersom samlingen av underordnade element kan modifieras.

**Returnerar:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Lägger till ett matematiskt element i slutet av samlingen.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement som ska läggas till i slutet av samlingen. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla element från samlingen.

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

Avgör om samlingen innehåller ett specifikt värde.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objektet som ska hittas i samlingen. |

**Returnerar:**
boolean - true om elementet finns i samlingen; annars false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Kopiera till angiven array.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array att kopiera till. |
| arrayIndex | int | Index att börja kopiera från. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadial(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Objektet som ska tas bort från samlingen. |

**Returnerar:**
boolean - true om elementet avlägsnades framgångsrikt från samlingen; annars false. Denna metod returnerar också false om elementet inte finns i den ursprungliga samlingen.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Returnerar en enumerator som itererar igenom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - En IGenericEnumerator som kan användas för att iterera igenom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.IEnumerator - En java.util.Iterator för hela samlingen.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Avgör index för ett specifikt matematiskt element i samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Elementet som ska hittas i samlingen. |

**Returnerar:**
int - Index för elementet om det hittas i samlingen; annars -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Infogar ett MathElement i samlingen på det angivna indexet.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där MathElement ska infogas. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement att infoga. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Förenar ett matematiskt element med detta matematiska block

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elementet som ska förenas. |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Den nuvarande instansen av IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Förenar en matematisk text med detta matematiska block

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | Matematisk text som ska förenas. |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ett nytt IMathBlock som innehåller denna instans och angivet argument
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Förenar ett annat matematiskt block med detta

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Det förenande blocket |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - detta matematiska block efter föreningen
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Avgränsar underordnade element med separator-tecken (utan hakparenteserna)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char | Separator-tecken |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Det matematiska elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Innesluter underordnade element i detta block med angivna tecken, såsom parenteser eller andra tecken som ram

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char | Avslutande tecken (vanligtvis höger hakparentes) |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Det matematiska elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som inkluderar angivna tecken som ram
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Innesluter underordnade element i detta block med angivna tecken, såsom parenteser eller andra som ram och avgränsar med ett separator-tecken

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char | Avslutande tecken (vanligtvis höger hakparentes) |
| separatorCharacter | char | Separator-tecken |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Det matematiska elementet av typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som innehåller angivna tecken som ram och avgränsare
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Placera underordnade element i en vertikal matris

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returnerar:**
[IMathArray](../../com.aspose.slides/imatharray) - Ny instans av typ [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Sparar innehållet av denna [MathBlock](../../com.aspose.slides/mathblock) som MathML

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |