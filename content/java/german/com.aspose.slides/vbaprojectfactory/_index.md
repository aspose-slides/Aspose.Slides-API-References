---
title: VbaProjectFactory
second_title: Aspose.Slides für Java API-Referenz
description: Ermöglicht das Erstellen eines VBA-Projekts über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/vbaprojectfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Ermöglicht das Erstellen eines VBA-Projekts über die COM-Schnittstelle
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInstance()](#getInstance--) | Statische Instanz der VBA-Projekt-Factory. |
| [createVbaProject()](#createVbaProject--) | Erstellt ein neues VBA-Projekt. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Liest das VBA-Projekt aus einem OLE-Container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Statische Instanz der VBA-Projekt-Factory. Nur lesbar [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Rückgabe:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Erstellt ein neues VBA-Projekt.

**Rückgabe:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Neues VBA-Projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Liest das VBA-Projekt aus einem OLE-Container.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] |  |

**Rückgabe:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Gelesenes VBA-Projekt