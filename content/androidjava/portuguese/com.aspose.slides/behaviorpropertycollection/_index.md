---
title: BehaviorPropertyCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa propriedades de temporização para o comportamento do efeito.
type: docs
url: /pt/com.aspose.slides/behaviorpropertycollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Representa propriedades de tempo para o comportamento do efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna o número de propriedades armazenadas na coleção. |
| [isReadOnly()](#isReadOnly--) | Obtém um valor indicando se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Adiciona uma nova propriedade à coleção. |
| [add(String propertyValue)](#add-java.lang.String-) | Adiciona uma nova propriedade à coleção. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Determina o índice de um item específico na List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina o índice de um item específico pelo valor da propriedade na List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Insere uma nova propriedade na coleção no índice especificado. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Insere uma nova propriedade (com o valor da propriedade especificado) na coleção no índice especificado. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice específico do Array. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Remove a propriedade especificada da coleção. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Remove a propriedade especificada da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a propriedade no índice especificado. |
| [clear()](#clear--) | Remove todas as propriedades da coleção. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [get_Item(int index)](#get-Item-int-) | Retorna uma propriedade no índice especificado. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Define uma propriedade no índice especificado. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
### size() {#size--}
```
public final int size()
```


Retorna o número de propriedades armazenadas na coleção. Somente leitura int.

**Retorna:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtém um valor indicando se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. Somente leitura boolean.

**Retorna:**
boolean - true se o [IGenericCollection](../../com.aspose.slides/igenericcollection) for somente leitura; caso contrário, false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Adiciona uma nova propriedade à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propriedade a ser adicionada. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Adiciona uma nova propriedade à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor da propriedade a ser adicionada. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Determina o índice de um item específico na List.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | O objeto a localizar na List. |

**Retorna:**
int - O índice do item se encontrado na lista; caso contrário, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Determina o índice de um item específico pelo valor da propriedade na List.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | valor da propriedade |

**Retorna:**
int - O índice da propriedade com o valor especificado
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Insere uma nova propriedade na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice onde uma nova propriedade deve ser inserida. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propriedade a ser adicionada. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Insere uma nova propriedade (com o valor da propriedade especificado) na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice onde uma nova propriedade deve ser inserida. |
| propertyValue | java.lang.String | Valor da propriedade a ser adicionada. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice específico do Array.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | O Array unidimensional que é o destino dos elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). O Array deve ter indexação baseada em zero. |
| arrayIndex | int | O índice baseado em zero no array onde a cópia começa. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Remove a propriedade especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propriedade a remover. |

**Retorna:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


Remove a propriedade especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor da propriedade a remover. |

**Retorna:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove a propriedade no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da propriedade que deve ser excluída. |

### clear() {#clear--}
```
public final void clear()
```


Remove todas as propriedades da coleção.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A propriedade a localizar no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - true se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor da propriedade a localizar no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - true se propertyValue for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Retorna uma propriedade no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma propriedade a ser retornada. |

**Retorna:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Propriedade de comportamento de animação.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Define uma propriedade no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma propriedade a ser retornada. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retorna:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retorna:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retorna:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Um java.util.Iterator para a coleção inteira.