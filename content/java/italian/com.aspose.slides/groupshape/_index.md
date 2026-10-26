---
title: GroupShape
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un gruppo di forme su una diapositiva.
type: docs
url: /it/com.aspose.slides/groupshape/
---
**Eredità:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Tutte le interfacce implementate:**  
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)  
```
public class GroupShape extends Shape implements IGroupShape
```

Rappresenta un gruppo di forme in una diapositiva.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Restituisce i blocchi della forma. |
| [getShapes()](#getShapes--) | Restituisce la raccolta di forme all'interno del gruppo. |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: Restituisce null per gli oggetti GroupShape perché non hanno proprietà di linea. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Restituisce i blocchi della forma. Solo lettura [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Restituisce:**  
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Restituisce la raccolta di forme all'interno del gruppo. Solo lettura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Restituisce:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)