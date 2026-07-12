---
title: AdjustValueCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de ajustes de formas.
type: docs
url: /pt/com.aspose.slides/adjustvaluecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as interfaces implementadas:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Representa uma coleção de ajustes de shape.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna um número de ajustes. |
| [get_Item(int index)](#get-Item-int-) | Retorna o ajuste por índice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador para toda a coleção. |
### size() {#size--}
```
public final int size()
```

Retorna um número de ajustes. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Retorna o ajuste por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | índice do ajuste. |

**Retorna:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Retorna um enumerador para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.IEnumerator