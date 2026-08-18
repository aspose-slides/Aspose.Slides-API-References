---
title: VbaProjectFactory
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi VBA projekt létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/vbaprojectfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Lehetővé teszi VBA projekt létrehozását COM interfészen keresztül
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInstance()](#getInstance--) | VBA projekt gyár statikus példánya. |
| [createVbaProject()](#createVbaProject--) | Új VBA projektet hoz létre. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | VBA projektet olvas be egy OLE konténerből. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA projekt gyár statikus példánya. Csak olvasható [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Visszatér:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Új VBA projektet hoz létre.

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Új VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


VBA projektet olvas be egy OLE konténerből.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Beolvasott VBA projekt