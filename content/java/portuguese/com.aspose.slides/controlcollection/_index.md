---
title: ControlCollection
second_title: Referência da API Aspose.Slides para Java
description: Uma coleção de controles ActiveX.
type: docs
url: /pt/com.aspose.slides/controlcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Uma coleção de controles ActiveX.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Retorna um número de objetos na coleção. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Cria e adiciona um novo controle à coleção. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Remove um controle ActiveX da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um controle ActiveX armazenado na posição especificada da coleção. |
| [clear()](#clear--) | Remove todos os controles da coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna um controle na posição especificada. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia toda a coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna um objeto raiz de sincronização. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Retorna um número de objetos na coleção. Somente leitura int.

**Returns:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


Cria e adiciona um novo controle à coleção.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| controlType | int | Tipo do controle a ser adicionado. |
| x | float | A coordenada X do lado esquerdo da moldura da forma. |
| y | float | A coordenada Y do lado superior da moldura da forma. |
| width | float | A largura da moldura da forma. |
| height | float | A altura da moldura da forma. |

**Returns:**
[IControl](../../com.aspose.slides/icontrol) - Controle criado.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


Remove um controle ActiveX da coleção.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Um controle a ser removido. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove um controle ActiveX armazenado na posição especificada da coleção.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice do controle a ser removido. |

### clear() {#clear--}
```
public final void clear()
```


Remove todos os controles da coleção.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


Retorna um controle na posição especificada.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice do controle. |

**Returns:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


Retorna um enumerador que itera através da coleção.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


Retorna um iterator java para toda a coleção.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Um java.util.Iterator para toda a coleção.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia toda a coleção para o array especificado.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | Índice no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna um objeto raiz de sincronização. Somente leitura Object.

**Returns:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject