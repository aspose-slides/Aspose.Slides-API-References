---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi VBA projekt létrehozását COM felületen keresztül
type: docs
url: /hu/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Lehetővé teszi VBA projekt létrehozását COM felületen keresztül
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Új VBA projektet hoz létre. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Olvas VBA projektet OLE tárolóból. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Új VBA projektet hoz létre.

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Új VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Olvas VBA projektet OLE tárolóból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Ole adat byte[] |

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Olvasott VBA projekt