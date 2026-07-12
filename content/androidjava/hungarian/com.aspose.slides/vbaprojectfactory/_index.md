---
title: VbaProjectFactory
second_title: Aspose.Slides for Android a Java API referencia szerint
description: Lehetővé teszi VBA projekt létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/vbaprojectfactory/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
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
| [getInstance()](#getInstance--) | VBA projektgyári statikus példány. |
| [createVbaProject()](#createVbaProject--) | Új VBA projektet hoz létre. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | VBA projektet olvas az OLE tárolóból. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA projektgyári statikus példány. Csak olvasható [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

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


VBA projektet olvas az OLE tárolóból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] |  |

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - VBA projekt olvasása