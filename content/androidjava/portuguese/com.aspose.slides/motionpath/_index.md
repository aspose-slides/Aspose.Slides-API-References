---
title: MotionPath
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um caminho de movimento.
type: docs
url: /pt/com.aspose.slides/motionpath/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Representa caminho de movimento.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Add new command to path |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Insert new command to path |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Adiciona um novo comando ao caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Matriz de pontos |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booleano de coordenadas relativas |

**Retorna:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

Retorna o número de caminhos na coleção. Somente leitura int.

**Retorna:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Insere um novo comando ao caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o item deve ser inserido. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Matriz de pontos |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booleano de coordenadas relativas |

### clear() {#clear--}
```
public final void clear()
```

Remove todos os comandos da coleção.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

Remove comandos especificados da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Caminho de movimento a remover. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove um comando no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um comando que deve ser excluído. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Retorna um comando no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - O objeto [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Um java.util.Iterator para a coleção inteira.