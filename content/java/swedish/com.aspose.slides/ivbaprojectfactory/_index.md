---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Tillåter att skapa VBA-projekt via COM-gränssnitt
type: docs
url: /sv/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Tillåter att skapa VBA-projekt via COM-gränssnitt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Skapar ett nytt VBA-projekt. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Läser VBA-projekt från OLE-behållare. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Skapar ett nytt VBA-projekt.

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nytt VBA-projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Läser VBA-projekt från OLE-behållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Ole-data byte[] |

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Läs VBA-projekt