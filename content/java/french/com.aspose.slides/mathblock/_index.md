---
title: MathBlock
second_title: Référence API Aspose.Slides pour Java
description: Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne distincte.
type: docs
url: /fr/com.aspose.slides/mathblock/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne séparée. Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d’équations ou d’expressions, et les formules sont représentées par un bloc mathématique.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initialise une nouvelle instance de la classe MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Crée un nouveau bloc mathématique et place l'élément spécifié dedans |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Crée un nouveau bloc mathématique et place les éléments spécifiés dedans |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'éléments mathématiques enfants réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient ou définit IMathElement à l'index spécifié. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Obtient ou définit IMathElement à l'index spécifié. |
| [isReadOnly()](#isReadOnly--) | Renvoie false car la collection d'éléments enfants peut être modifiée. |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getParent_Immediate()](#getParent-Immediate--) | Renvoie l'objet Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Ajoute un élément mathématique à la fin de la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Détermine si la collection contient une valeur spécifique. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copie dans le tableau spécifié. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Détermine l'index d'un élément mathématique spécifique dans la collection. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Insère un MathElement dans la collection à l'index spécifié. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joint un élément mathématique à ce bloc mathématique |
| [join(String mathText)](#join-java.lang.String-) | Joint un texte mathématique à ce bloc mathématique |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Joint un autre bloc mathématique à celui-ci |
| [delimit(char separatorCharacter)](#delimit-char-) | Délimite les éléments enfants avec le caractère séparateur (sans les crochets) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme cadre |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres comme cadre et les délimite avec un caractère séparateur |
| [toMathArray()](#toMathArray--) | Place les éléments enfants dans un tableau vertical |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Enregistre le contenu de ce [MathBlock](../../com.aspose.slides/mathblock) au format MathML |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initialise une nouvelle instance de la classe MathBlock.

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

Crée un nouveau bloc mathématique et place l'élément spécifié dedans

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'élément mathématique à placer dans le bloc |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Crée un nouveau bloc mathématique et place les éléments spécifiés dedans

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Éléments mathématiques à placer dans le bloc |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtient le nombre d'éléments mathématiques enfants réellement contenus dans la collection. Lecture seule int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Renvoie:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Obtient ou définit IMathElement à l'index spécifié.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément |

**Renvoie:**
[IMathElement](../../com.aspose.slides/imathelement) - L'élément mathématique.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Obtient ou définit IMathElement à l'index spécifié.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément |
| value | [IMathElement](../../com.aspose.slides/imathelement) | L'élément mathématique. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Renvoie false car la collection d'éléments enfants peut être modifiée.

**Renvoie:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Renvoie:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Ajoute un élément mathématique à la fin de la collection.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'IMathElement à ajouter à la fin de la collection. |

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

Détermine si la collection contient une valeur spécifique.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'objet à localiser dans la collection. |

**Renvoie:**
boolean - true si l'élément est trouvé dans la collection ; sinon false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Copie dans le tableau spécifié.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Tableau dans lequel copier. |
| arrayIndex | int | Index à partir duquel commencer la copie. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Supprime la première occurrence d'un objet spécifique de la collection.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'objet à supprimer de la collection. |

**Renvoie:**
boolean - true si l'élément a été supprimé avec succès de la collection ; sinon false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans la collection originale.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie:**
com.aspose.ms.System.Collections.IEnumerator - Un java.util.Iterator pour l'ensemble de la collection.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Détermine l'index d'un élément mathématique spécifique dans la collection.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'élément à localiser dans la collection. |

**Renvoie:**
int - L'index de l'élément s'il est trouvé dans la collection ; sinon -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Insère un MathElement dans la collection à l'index spécifié.

--------------------

> ```
> Exemple:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel le MathElement doit être inséré. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Le MathElement à insérer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Joint un élément mathématique à ce bloc mathématique

--------------------

> ```
> Exemple:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'élément à joindre |

**Renvoie:**
[IMathBlock](../../com.aspose.slides/imathblock) - L'instance actuelle de IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Joint un texte mathématique à ce bloc mathématique

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Texte mathématique à joindre |

**Renvoie:**
[IMathBlock](../../com.aspose.slides/imathblock) - Une nouvelle IMathBlock contenant cette instance et l'argument spécifié
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Joint un autre bloc mathématique à celui-ci

--------------------

> ```
> Exemple:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Le bloc de jointure |

**Renvoie:**
[IMathBlock](../../com.aspose.slides/imathblock) - ce bloc mathématique après la jointure
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Délimite les éléments enfants avec le caractère séparateur (sans les crochets)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | Caractère séparateur |

**Renvoie:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme cadre

--------------------

> ```
> Exemple:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (habituellement le crochet gauche) |
| endingCharacter | char | Caractère de fin (habituellement le crochet droit) |

**Renvoie:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) incluant les caractères spécifiés comme encadrement
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres comme cadre et les délimite avec un caractère séparateur

--------------------

> ```
> Exemple:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (habituellement le crochet gauche) |
| endingCharacter | char | Caractère de fin (habituellement le crochet droit) |
| separatorCharacter | char | Caractère séparateur |

**Renvoie:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) incluant les caractères spécifiés comme encadrement et délimiteur
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Place les éléments enfants dans un tableau vertical

--------------------

> ```
> Exemple:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Renvoie:**
[IMathArray](../../com.aspose.slides/imatharray) - Nouvelle instance du type [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Enregistre le contenu de ce [MathBlock](../../com.aspose.slides/mathblock) au format MathML

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |