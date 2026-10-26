---
title: GroupShape
second_title: Referência da API Aspose.Slides para Java
description: Representa um grupo de formas em um slide.
type: docs
url: /pt/com.aspose.slides/groupshape/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Todas as interfaces implementadas:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Representa um grupo de formas em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retorna o objeto LineFormat que contém as propriedades de formatação de linha para uma forma. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Retorna os bloqueios da forma. |
| [getShapes()](#getShapes--) | Retorna a coleção de formas dentro do grupo. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Retorna o objeto LineFormat que contém as propriedades de formatação de linha para uma forma. Nota: Retorna null para objetos GroupShape porque eles não possuem propriedades de linha. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Retorna os bloqueios da forma. Somente leitura [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Retorna:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Retorna a coleção de formas dentro do grupo. Somente leitura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retorna:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)