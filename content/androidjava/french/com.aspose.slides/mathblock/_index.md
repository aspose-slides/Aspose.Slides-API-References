---
title: MathBlock
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne séparée.
type: docs
url: /fr/com.aspose.slides/mathblock/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne séparée. Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d’équations ou d’expressions et les formules, sont représentées par un bloc mathématique.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initializes a new instance of the MathBlock class. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Creates a new mathematical block and puts specified element in it |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Creates a new mathematical block and puts specified elements in it |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of child math elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets or sets IMathElement at the specified index. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Gets or sets IMathElement at the specified index. |
| [isReadOnly()](#isReadOnly--) | Returns false because child elements collection can be modified. |
| [getChildren()](#getChildren--) | Get children elements |
| [getParent_Immediate()](#getParent-Immediate--) | Returns Parent\_Immediate object. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Adds a math element to the end of the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determines whether the collection contains a specific value. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Removes the first occurrence of a specific object from the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determines the index of a specific math element in collection. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Inserts a MathElement into the collection at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joins a mathematical element with this mathematical block |
| [join(String mathText)](#join-java.lang.String-) | Joins a mathematical text with this mathematical block |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Joins another mathematical block with this one |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits child elements with separator character (without the brackets) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [toMathArray()](#toMathArray--) | Puts child elements in a vertical array |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Saves content of this [MathBlock](../../com.aspose.slides/mathblock) as MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initializes a new instance of the MathBlock class.

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

Creates a new mathematical block and puts specified element in it

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | The mathematical element to put in the block |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Creates a new mathematical block and puts specified elements in it

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Mathematical elements to put in the block |

### getCount() {#getCount--}
```
public final int getCount()
```

Gets the number of child math elements actually contained in the collection. Read-only int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Gets or sets IMathElement at the specified index.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement) - The mathematical element.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Obtient ou définit IMathElement à l'index spécifié.

--------------------

> ```
> Exemple:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro de l'élément |
| value | [IMathElement](../../com.aspose.slides/imathelement) | L'élément mathématique. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Returns false because child elements collection can be modified.

**Returns:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Returns:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Adds a math element to the end of the collection.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The IMathElement to be added to the end of the collection. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.

--------------------

> ```
> Exemple:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Determines whether the collection contains a specific value.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The object to locate in the collection. |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Copy to specified array.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array to copy to. |
| arrayIndex | int | Index to begin copying. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Supprime la première occurrence d'un objet spécifique de la collection.

--------------------

> ```
> Exemple:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'objet à supprimer de la collection. |

**Valeur de retour :**
boolean - true si l'élément a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans la collection d'origine.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Renvoie un itérateur java pour l’ensemble de la collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Un java.util.Iterator pour l’ensemble de la collection.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Détermine l'indice d'un élément mathématique spécifique dans la collection.

--------------------

> ```
> Exemple:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The element to locate in the collection. |

**Returns:**
int - L'indice de l'élément s'il est trouvé dans la collection ; sinon, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Insère un MathElement dans la collection à l'index spécifié.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which MathElement should be inserted. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The MathElement to insert. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l’élément à l’index spécifié de la collection.

--------------------

> ```
> Exemple :
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro de l’élément à supprimer. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```
Joint un élément mathématique à ce bloc mathématique

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'élément à joindre |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - L'instance courante de IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```
Joint un texte mathématique à ce bloc mathématique

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Mathematical text to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Joint un autre bloc mathématique avec celui-ci

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Le bloc à joindre |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - ce bloc mathématique après la jointure
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimits child elements with separator character (without the brackets)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | Separator character |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encloses child elements of this block in specified characters such as parenthesis or another characters as framing

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d’autres, en les délimitant par un caractère séparateur

--------------------

> ```
> Exemple :
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |
| separatorCharacter | char | Separator character |

**Valeur de retour :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing and delimiter
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```
Puts child elements in a vertical array

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
Enregistre le contenu de ce [MathBlock](../../com.aspose.slides/mathblock) au format MathML

Paramètres :
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |