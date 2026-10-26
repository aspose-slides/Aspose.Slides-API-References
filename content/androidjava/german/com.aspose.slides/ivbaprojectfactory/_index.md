---
title: IVbaProjectFactory
second_title: Aspose.Slides für Android über Java API Referenz
description: Ermöglicht das Erstellen eines VBA-Projekts über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Ermöglicht das Erstellen eines VBA-Projekts über die COM-Schnittstelle
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Erstellt ein neues VBA-Projekt. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Liest ein VBA-Projekt aus einem OLE-Container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Erstellt ein neues VBA-Projekt.

**Rückgabewert:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Neues VBA-Projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Liest ein VBA-Projekt aus einem OLE-Container.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Ole-Daten byte[] |

**Rückgabewert:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Gelesenes VBA-Projekt