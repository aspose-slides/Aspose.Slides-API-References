---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi VBA projekt létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Lehetővé teszi VBA projekt létrehozását COM interfészen keresztül
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Új VBA projektet hoz létre. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Olvas egy VBA projektet OLE tárolóból. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Új VBA projektet hoz létre.

**Visszatérési érték:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Új VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Olvas egy VBA projektet OLE tárolóból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Ole adat byte[] |

**Visszatérési érték:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Olvasott VBA projekt