---
title: VbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project via COM interface
type: docs
weight: 603
url: /java/com.aspose.slides/vbaprojectfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Allows to create VBA project via COM interface
## Constructors

| Constructor | Description |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project factory static instance. |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA project factory static instance. Read-only [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Returns:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Creates new VBA project.

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - New VBA project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Reads VBA project from OLE container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Read VBA project
