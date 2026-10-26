---
title: MathBlock
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en una línea propia.
type: docs
url: /es/com.aspose.slides/mathblock/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en una línea propia. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inicializa una nueva instancia de la clase MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Crea un nuevo bloque matemático y coloca el elemento especificado en él. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Crea un nuevo bloque matemático y coloca los elementos especificados en él. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene o establece IMathElement en el índice especificado. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Obtiene o establece IMathElement en el índice especificado. |
| [isReadOnly()](#isReadOnly--) | Devuelve false porque la colección de elementos secundarios puede ser modificada. |
| [getChildren()](#getChildren--) | Obtiene los elementos hijos. |
| [getParent_Immediate()](#getParent-Immediate--) | Devuelve el objeto Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Agrega un elemento matemático al final de la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determina si la colección contiene un valor específico. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copia a la matriz especificada. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Elimina la primera ocurrencia de un objeto específico de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determina el índice de un elemento matemático específico en la colección. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Inserta un MathElement en la colección en el índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Une un elemento matemático con este bloque matemático. |
| [join(String mathText)](#join-java.lang.String-) | Une un texto matemático con este bloque matemático. |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Une otro bloque matemático con este. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita los elementos hijos con un carácter separador (sin los corchetes). |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros caracteres como marco. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros como marco y delimita con un carácter separador. |
| [toMathArray()](#toMathArray--) | Coloca los elementos hijos en una matriz vertical. |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Guarda el contenido de este [MathBlock](../../com.aspose.slides/mathblock) como MathML. |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Inicializa una nueva instancia de la clase MathBlock.

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

Crea un nuevo bloque matemático y coloca el elemento especificado en él.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | El elemento matemático para colocar en el bloque. |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Crea un nuevo bloque matemático y coloca los elementos especificados en él.

--------------------

> ```
> Ejemplo:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementos matemáticos para colocar en el bloque. |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección. int de solo lectura.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Obtiene o establece IMathElement en el índice especificado.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento. |

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement) - El elemento matemático.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Obtiene o establece IMathElement en el índice especificado.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento. |
| value | [IMathElement](../../com.aspose.slides/imathelement) | El elemento matemático. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Devuelve false porque la colección de elementos secundarios puede ser modificada.

**Devuelve:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtiene los elementos hijos.

**Devuelve:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. IDOMObject de solo lectura.

**Devuelve:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Agrega un elemento matemático al final de la colección.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | El IMathElement que se agregará al final de la colección. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los elementos de la colección.

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Determina si la colección contiene un valor específico.

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | El objeto a localizar en la colección. |

**Devuelve:**
boolean - true si el elemento se encuentra en la colección; de lo contrario, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Copia a la matriz especificada.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Matriz a la que copiar. |
| arrayIndex | int | Índice para comenzar a copiar. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Elimina la primera ocurrencia de un objeto específico de la colección.

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | El objeto a eliminar de la colección. |

**Devuelve:**
boolean - true si el elemento se eliminó correctamente de la colección; de lo contrario, false. Este método también devuelve false si el elemento no se encuentra en la colección original.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Un IGenericEnumerator que puede usarse para iterar la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.IEnumerator - Un java.util.Iterator para toda la colección.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Determina el índice de un elemento matemático específico en la colección.

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | El elemento a localizar en la colección. |

**Devuelve:**
int - El índice del elemento si se encuentra en la colección; de lo contrario, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Inserta un MathElement en la colección en el índice especificado.

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se debe insertar el MathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | El MathElement a insertar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Une un elemento matemático con este bloque matemático.

--------------------

> ```
> Ejemplo:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | El elemento a unir. |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - La instancia actual de IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Une un texto matemático con este bloque matemático.

--------------------

> ```
> Ejemplo:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | Texto matemático a unir. |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nuevo IMathBlock que contiene esta instancia y el argumento especificado.
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Une otro bloque matemático con este.

--------------------

> ```
> Ejemplo:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | El bloque que se une. |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - este bloque matemático después de la unión.
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimita los elementos hijos con un carácter separador (sin los corchetes).

--------------------

> ```
> Ejemplo:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char | Carácter separador. |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - El elemento matemático de tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter).
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros caracteres como marco.

--------------------

> ```
> Ejemplo:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char | Carácter inicial (generalmente corchete izquierdo). |
| endingCharacter | char | Carácter final (generalmente corchete derecho). |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - El elemento matemático de tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que incluye los caracteres especificados como marco.
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Encierra los elementos hijos de este bloque en caracteres especificados, como paréntesis u otros como marco y delimita con un carácter separador.

--------------------

> ```
> Ejemplo:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char | Carácter inicial (generalmente corchete izquierdo). |
| endingCharacter | char | Carácter final (generalmente corchete derecho). |
| separatorCharacter | char | Carácter separador. |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - El elemento matemático de tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que incluye los caracteres especificados como marco y delimitador.
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Coloca los elementos hijos en una matriz vertical.

--------------------

> ```
> Ejemplo:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Devuelve:**
[IMathArray](../../com.aspose.slides/imatharray) - Nueva instancia de tipo [IMathArray](../../com.aspose.slides/imatharray).
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Guarda el contenido de este [MathBlock](../../com.aspose.slides/mathblock) como MathML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino. |