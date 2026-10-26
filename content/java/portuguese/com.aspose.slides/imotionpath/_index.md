---
title: IMotionPath
second_title: Referência da API Aspose.Slides para Java
description: Representa caminho de movimento.
type: docs
url: /pt/com.aspose.slides/imotionpath/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Representa caminho de movimento.
## Métodos

| Method | Description |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Adiciona um novo comando ao caminho |
| [getCount()](#getCount--) | Retorna o número de caminhos na coleção. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Insere um novo comando ao caminho |
| [clear()](#clear--) | Remove todos os comandos da coleção. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Remove os comandos especificados da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um comando no índice especificado. |
| [get_Item(int index)](#get-Item-int-) | Retorna um comando no índice especificado. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Adiciona um novo comando ao caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | Tipo de comando para comportamento do efeito de movimento de animação [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Matriz de pontos java.awt.geom.Point2D.Float[] |
| ptsType | int | Tipo de pontos no caminho de movimento da animação [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica se deve usar coordenadas relativas ou não boolean |

**Retorna:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando de um caminho [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retorna o número de caminhos na coleção. Somente leitura int.

**Retorna:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Insere um novo comando ao caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice para inserção do comando int |
| type | int | Tipo de comando para comportamento do efeito de movimento de animação [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Matriz de pontos java.awt.geom.Point2D.Float[] |
| ptsType | int | Tipo de pontos no caminho de movimento da animação [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica se deve usar coordenadas relativas ou não boolean |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todos os comandos da coleção.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Remove os comandos especificados da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Caminho de movimento a remover [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove um comando no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice para remover o comando int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Retorna um comando no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando no índice especificado [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)