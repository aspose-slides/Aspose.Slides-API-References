---
title: GroupShape
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Representa un grupo de formas en una diapositiva.
type: docs
url: /es/com.aspose.slides/groupshape/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Todas las interfaces implementadas:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Representa un grupo de formas en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Devuelve los bloqueos de la forma. |
| [getShapes()](#getShapes--) | Devuelve la colección de formas dentro del grupo. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. Nota: Devuelve null para objetos GroupShape porque no tienen propiedades de línea. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Devuelve los bloqueos de la forma. Solo lectura [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Devuelve:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Devuelve la colección de formas dentro del grupo. Solo lectura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Devuelve:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)