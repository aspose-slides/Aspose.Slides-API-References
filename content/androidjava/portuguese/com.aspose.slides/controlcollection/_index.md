---
title: ControlCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Uma coleção de controles ActiveX.
type: docs
url: /pt/com.aspose.slides/controlcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Uma coleção de controles ActiveX.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna o número de objetos na coleção. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Cria e adiciona um novo controle à coleção. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Remove um controle ActiveX da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um controle ActiveX armazenado na posição especificada da coleção. |
| [clear()](#clear--) | Remove todos os controles da coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna um controle na posição especificada. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia a coleção inteira para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Retorna o número de objetos na coleção. Somente leitura int.

**Retorna:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Cria e adiciona um novo controle à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| controlType | int | Tipo de controle a ser adicionado. |
| x | float | A coordenada X para o lado esquerdo da moldura da forma. |
| y | float | A coordenada Y para o lado superior da moldura da forma. |
| width | float | A largura da moldura da forma. |
| height | float | A altura da moldura da forma. |

**Retorna:**
[IControl](../../com.aspose.slides/icontrol) - Controle criado.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Remove um controle ActiveX da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Um controle a ser removido. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove um controle ActiveX armazenado na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um controle. |

**Retorna:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Um java.util.Iterator para a coleção inteira.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia a coleção inteira para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | Índice no array de destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject