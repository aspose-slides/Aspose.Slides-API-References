---
title: MathBlock
second_title: Aspose.Slides für Java API Referenz
description: Gibt eine Instanz von mathematischem Text an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt.
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

Gibt eine Instanz von mathematischem Text an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücken, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen Math-Block dargestellt.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initialisiert eine neue Instanz der MathBlock-Klasse. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Erstellt einen neuen mathematischen Block und fügt das angegebene Element ein |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente ein |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen Kind-Math-Elemente zurück. |
| [get_Item(int index)](#get-Item-int-) | Ruft ein IMathElement am angegebenen Index ab oder setzt es. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Ruft ein IMathElement am angegebenen Index ab oder setzt es. |
| [isReadOnly()](#isReadOnly--) | Gibt false zurück, weil die Sammlung der Kind-Elemente modifiziert werden kann. |
| [getChildren()](#getChildren--) | Gibt die Kind-Elemente zurück |
| [getParent_Immediate()](#getParent-Immediate--) | Gibt das Parent_Immediate-Objekt zurück. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Fügt der Sammlung ein Math-Element am Ende hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Kopiert in das angegebene Array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Bestimmt den Index eines bestimmten Math-Elements in der Sammlung. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Fügt ein MathElement an der angegebenen Position in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index aus der Sammlung. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Verbindet ein mathematisches Element mit diesem mathematischen Block |
| [join(String mathText)](#join-java.lang.String-) | Verbindet einen mathematischen Text mit diesem mathematischen Block |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Verbindet einen anderen mathematischen Block mit diesem |
| [delimit(char separatorCharacter)](#delimit-char-) | Begrenz t Kind-Elemente mit einem Trennzeichen (ohne Klammern) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Schließt die Kind-Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Schließt die Kind-Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen als Rahmen ein und begrenzt sie mit einem Trennzeichen |
| [toMathArray()](#toMathArray--) | Ordnet die Kind-Elemente in einem vertikalen Array an |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Speichert den Inhalt dieses [MathBlock](../../com.aspose.slides/mathblock) als MathML |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initialisiert eine neue Instanz der MathBlock-Klasse.

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

Erstellt einen neuen mathematischen Block und fügt das angegebene Element ein

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Das mathematische Element, das in den Block eingefügt werden soll |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente ein

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Mathematische Elemente, die in den Block eingefügt werden sollen |

### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen Kind-Math-Elemente zurück. Nur-Lese-int.

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

Ruft ein IMathElement am angegebenen Index ab oder setzt es.

--------------------

> ```
> Beispiel:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des Elements |

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement) – Das mathematische Element.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Ruft ein IMathElement am angegebenen Index ab oder setzt es.

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
| index | int | Der nullbasierte Index des Elements |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Das mathematische Element. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gibt false zurück, weil die Sammlung der Kind-Elemente modifiziert werden kann.

**Rückgabe:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gibt die Kind-Elemente zurück

**Rückgabe:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lese-IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Fügt der Sammlung ein Math-Element am Ende hinzu.

--------------------

> ```
> Example:
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
> Example:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das Objekt, das in der Sammlung gesucht werden soll. |

**Rückgabe:**
boolean – true, wenn das Element gefunden wurde; andernfalls false.
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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array, in das kopiert werden soll. |
| arrayIndex | int | Index, an dem das Kopieren beginnen soll. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

--------------------

> ```
> Beispiel:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das Objekt, das aus der Sammlung entfernt werden soll. |

**Rückgabe:**
boolean – true, wenn das Element erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Element nicht in der ursprünglichen Sammlung gefunden wird.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> – ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.IEnumerator – ein java.util.Iterator für die gesamte Sammlung.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Bestimmt den Index eines bestimmten Math-Elements in der Sammlung.

--------------------

> ```
> Beispiel:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das Element, das in der Sammlung gesucht werden soll. |

**Rückgabe:**
int – Der Index des Elements, falls gefunden; andernfalls -1.
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das MathElement, das eingefügt werden soll. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index aus der Sammlung.

--------------------

> ```
> Beispiel:
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

Verbindet ein mathematisches Element mit diesem mathematischen Block

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Das zu verbindende Element |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Die aktuelle Instanz von IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Verbindet einen mathematischen Text mit diesem mathematischen Block

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
| mathText | java.lang.String | Zu verbindender mathematischer Text |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Ein neuer IMathBlock, der diese Instanz und das angegebene Argument enthält
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Verbindet einen anderen mathematischen Block mit diesem

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Der zu verbindende Block |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) – Dieser mathematische Block nach dem Verbinden
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Begrenzt Kind-Elemente mit einem Trennzeichen (ohne Klammern)

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
| separatorCharacter | char | Trennzeichen |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das Math-Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Schließt die Kind-Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein

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
| beginningCharacter | char | Anfangszeichen (in der Regel linke Klammer) |
| endingCharacter | char | Endzeichen (in der Regel rechte Klammer) |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das Math-Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) mit den angegebenen Zeichen als Rahmen
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Schließt die Kind-Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen als Rahmen ein und begrenzt sie mit einem Trennzeichen

--------------------

> ```
> Beispiel:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char | Anfangszeichen (in der Regel linke Klammer) |
| endingCharacter | char | Endzeichen (in der Regel rechte Klammer) |
| separatorCharacter | char | Trennzeichen |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) – Das Math-Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) mit den angegebenen Zeichen als Rahmen und Trennzeichen
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Ordnet die Kind-Elemente in einem vertikalen Array an

--------------------

> ```
> Beispiel:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Rückgabe:**
[IMathArray](../../com.aspose.slides/imatharray) – Neue Instanz vom Typ [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Speichert den Inhalt dieses [MathBlock](../../com.aspose.slides/mathblock) als MathML

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |