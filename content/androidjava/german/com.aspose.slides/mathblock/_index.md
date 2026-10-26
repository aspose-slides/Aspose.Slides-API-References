---
title: MathBlock
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt eine Instanz von mathematischem Text an, die in einem MathParagraph enthalten ist und in einer eigenen Zeile beginnt.
type: docs
url: /de/com.aspose.slides/mathblock/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Gibt eine Instanz von mathematischem Text an, die in einem MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücken, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen MathBlock dargestellt.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initialisiert eine neue Instanz der Klasse MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Erstellt einen neuen mathematischen Block und fügt das angegebene Element ein. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente ein. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Ermittelt die Anzahl der tatsächlich in der Sammlung enthaltenen untergeordneten mathematischen Elemente. |
| [get_Item(int index)](#get-Item-int-) | Ruft das IMathElement am angegebenen Index ab oder legt es fest. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Ruft das IMathElement am angegebenen Index ab oder legt es fest. |
| [isReadOnly()](#isReadOnly--) | Gibt false zurück, weil die Sammlung der Kind-Elemente verändert werden kann. |
| [getChildren()](#getChildren--) | Gibt die Kind-Elemente zurück. |
| [getParent_Immediate()](#getParent-Immediate--) | Gibt das Objekt Parent_Immediate zurück. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Fügt ein mathematisches Element am Ende der Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopiert in das angegebene Array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Fügt ein MathElement an der angegebenen Position in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element an der angegebenen Position aus der Sammlung. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Verknüpft ein mathematisches Element mit diesem mathematischen Block. |
| [join(String mathText)](#join-java.lang.String-) | Verknüpft einen mathematischen Text mit diesem mathematischen Block. |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Verknüpft einen anderen mathematischen Block mit diesem. |
| [delimit(char separatorCharacter)](#delimit-char-) | Begrenzt Kind-Elemente mit einem Trennzeichen (ohne die Klammern). |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Umschließt die Kind-Elemente dieses Blocks mit angegebenen Zeichen, z. B. Klammern oder anderen Zeichen als Rahmen. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Umschließt die Kind-Elemente dieses Blocks mit angegebenen Zeichen, z. B. Klammern oder anderen als Rahmen, und trennt sie mit einem Trennzeichen. |
| [toMathArray()](#toMathArray--) | Ordnet die Kind-Elemente in einer vertikalen Anordnung an. |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Speichert den Inhalt dieses [MathBlock](../../com.aspose.slides/mathblock) als MathML. |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initialisiert eine neue Instanz der Klasse MathBlock.

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

Erstellt einen neuen mathematischen Block und fügt das angegebene Element ein.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Das mathematische Element, das in den Block eingefügt wird. |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente ein.

--------------------

> ```
> Beispiel:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Mathematische Elemente, die in den Block eingefügt werden. |

### getCount() {#getCount--}
```
public final int getCount()
```

Ermittelt die Anzahl der tatsächlich in der Sammlung enthaltenen untergeordneten mathematischen Elemente. Nur lesbarer int.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Ruft das IMathElement am angegebenen Index ab oder legt es fest.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des Elements. |

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement) – Das mathematische Element.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Ruft das IMathElement am angegebenen Index ab oder legt es fest.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des Elements. |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Das mathematische Element. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gibt false zurück, weil die Sammlung der Kind-Elemente verändert werden kann.

**Rückgabe:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gibt die Kind-Elemente zurück.

**Rückgabe:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Objekt Parent_Immediate zurück. Nur lesbares IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Fügt ein mathematisches Element am Ende der Sammlung hinzu.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das IMathElement, das am Ende der Sammlung hinzugefügt werden soll. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das zu suchende Objekt in der Sammlung. |

**Rückgabe:**
boolean – true, wenn das Element in der Sammlung gefunden wurde; andernfalls false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Kopiert in das angegebene Array.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IMathElement[]](../../com.aspose.slides/imathelement) | Array, in das kopiert wird. |
| arrayIndex | int | Index, ab dem das Kopieren beginnt. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das zu entfernende Objekt aus der Sammlung. |

**Rückgabe:**
boolean – true, wenn das Element erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Element in der Originalsammlung nicht gefunden wird.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> – Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.IEnumerator – Ein java.util.Iterator für die gesamte Sammlung.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das zu findende Element in der Sammlung. |

**Rückgabe:**
int – Der Index des Elements, falls gefunden; sonst -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Fügt ein MathElement an der angegebenen Position in die Sammlung ein.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das MathElement eingefügt werden soll. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das einzufügende MathElement. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element an der angegebenen Position aus der Sammlung.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Verknüpft ein mathematisches Element mit diesem mathematischen Block.

--------------------

> ```
> Beispiel:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Das zu verknüpfende Element. |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Die aktuelle Instanz von IMathBlock.
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Verknüpft einen mathematischen Text mit diesem mathematischen Block.

--------------------

> ```
> Beispiel:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Der zu verknüpfende mathematische Text. |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Ein neuer IMathBlock, der diese Instanz und das angegebene Argument enthält.
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Verknüpft einen anderen mathematischen Block mit diesem.

--------------------

> ```
> Beispiel:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Der zu verknüpfende Block. |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Dieser mathematische Block nach dem Verknüpfen.
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Begrenzt Kind-Elemente mit einem Trennzeichen (ohne die Klammern).

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char | Das Trennzeichen. |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das MathElement vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter).
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Umschließt die Kind-Elemente dieses Blocks mit angegebenen Zeichen, z. B. Klammern oder anderen Zeichen als Rahmen.

--------------------

> ```
> Beispiel:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char | Beginnzeichen (meist linke Klammer). |
| endingCharacter | char | Endzeichen (meist rechte Klammer). |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das MathElement vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter), das die angegebenen Zeichen als Rahmen enthält.
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Umschließt die Kind-Elemente dieses Blocks mit angegebenen Zeichen, z. B. Klammern oder anderen als Rahmen, und trennt sie mit einem Trennzeichen.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char | Beginnzeichen (meist linke Klammer). |
| endingCharacter | char | Endzeichen (meist rechte Klammer). |
| separatorCharacter | char | Trennzeichen. |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das MathElement vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter), das die angegebenen Zeichen als Rahmen und Trennzeichen enthält.
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Ordnet die Kind-Elemente in einer vertikalen Anordnung an.

--------------------

> ```
> Beispiel:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Rückgabe:**
[IMathArray](../../com.aspose.slides/imatharray) – Neue Instanz vom Typ [IMathArray](../../com.aspose.slides/imatharray).
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Speichert den Inhalt dieses [MathBlock](../../com.aspose.slides/mathblock) als MathML.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |