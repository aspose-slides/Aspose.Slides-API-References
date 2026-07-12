---
title: MathBlock
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica uma instância de texto matemático contida em um MathParagraph e que começa em sua própria linha.
type: docs
url: /pt/com.aspose.slides/mathblock/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Especifica uma instância de texto matemático que está contido em um MathParagraph e começa em sua própria linha. Todas as zonas matemáticas, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas são representadas por bloco matemático.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inicializa uma nova instância da classe MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Cria um novo bloco matemático e coloca o elemento especificado nele |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Cria um novo bloco matemático e coloca os elementos especificados nele |
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Obtém o número de elementos matemáticos filhos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém ou define IMathElement no índice especificado. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Obtém ou define IMathElement no índice especificado. |
| [isReadOnly()](#isReadOnly--) | Retorna false porque a coleção de elementos filhos pode ser modificada. |
| [getChildren()](#getChildren--) | Obtém elementos filhos |
| [getParent_Immediate()](#getParent-Immediate--) | Retorna o objeto Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Adiciona um elemento matemático ao final da coleção. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determina se a coleção contém um valor específico. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copia para a matriz especificada. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determina o índice de um elemento matemático específico na coleção. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Insere um MathElement na coleção no índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Une um elemento matemático a este bloco matemático |
| [join(String mathText)](#join-java.lang.String-) | Une um texto matemático a este bloco matemático |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Une outro bloco matemático a este |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita elementos filhos com caractere separador (sem os colchetes) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros como moldura e delimita com um caractere separador |
| [toMathArray()](#toMathArray--) | Coloca os elementos filhos em uma matriz vertical |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva o conteúdo deste [MathBlock](../../com.aspose.slides/mathblock) como MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```


Inicializa uma nova instância da classe MathBlock.

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


Cria um novo bloco matemático e coloca o elemento especificado nele

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | O elemento matemático a ser colocado no bloco |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```


Cria um novo bloco matemático e coloca os elementos especificados nele

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementos matemáticos a serem colocados no bloco |

### getCount() {#getCount--}
```
public final int getCount()
```


Obtém o número de elementos matemáticos filhos realmente contidos na coleção. int somente leitura.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```


Obtém ou define IMathElement no índice especificado.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do item |

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement) - O elemento matemático.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```


Obtém ou define IMathElement no índice especificado.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do item |
| value | [IMathElement](../../com.aspose.slides/imathelement) | O elemento matemático. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Retorna false porque a coleção de elementos filhos pode ser modificada.

**Retorna:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtém elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. IDOMObject somente leitura.

**Retorna:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```


Adiciona um elemento matemático ao final da coleção.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O IMathElement a ser adicionado ao final da coleção. |

### clear() {#clear--}
```
public final void clear()
```


Remove todos os elementos da coleção.

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


Determina se a coleção contém um valor específico.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O objeto a ser localizado na coleção. |

**Retorna:**
boolean - true se o item for encontrado na coleção; caso contrário, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```


Copia para a matriz especificada.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Matriz para onde copiar. |
| arrayIndex | int | Índice para começar a copiar. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```


Remove a primeira ocorrência de um objeto específico da coleção.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O objeto a ser removido da coleção. |

**Retorna:**
boolean - true se o item for removido com sucesso da coleção; caso contrário, false. Este método também retorna false se o item não for encontrado na coleção original.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```


Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.IEnumerator - Um java.util.Iterator para toda a coleção.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```


Determina o índice de um elemento matemático específico na coleção.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O elemento a ser localizado na coleção. |

**Retorna:**
int - O índice do item se encontrado na coleção; caso contrário, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```


Insere um MathElement na coleção no índice especificado.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o MathElement deve ser inserido. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | O MathElement a ser inserido. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove o elemento no índice especificado da coleção.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


Une um elemento matemático a este bloco matemático

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | O elemento a ser unido |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - A instância atual de IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```


Une um texto matemático a este bloco matemático

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | Texto matemático a ser unido |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - Um novo IMathBlock contendo esta instância e o argumento especificado
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```


Une outro bloco matemático a este

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | O bloco que será unido |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - este bloco matemático após a união
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```


Delimita elementos filhos com caractere separador (sem os colchetes)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char | Caractere separador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - O elemento matemático do tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros caracteres como moldura

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char | Caractere final (geralmente colchete direito) |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - O elemento matemático do tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que inclui os caracteres especificados como moldura
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outro como moldura e delimita com um caractere separador

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char | Caractere final (geralmente colchete direito) |
| separatorCharacter | char | Caractere separador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - O elemento matemático do tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que inclui os caracteres especificados como moldura e delimitador
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```


Coloca os elementos filhos em uma matriz vertical

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Retorna:**
[IMathArray](../../com.aspose.slides/imatharray) - Nova instância do tipo [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


Salva o conteúdo deste [MathBlock](../../com.aspose.slides/mathblock) como MathML

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |