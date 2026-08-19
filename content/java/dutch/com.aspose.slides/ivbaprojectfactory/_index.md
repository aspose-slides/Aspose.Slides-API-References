---
title: IVbaProjectFactory
second_title: Aspose.Slides voor Java API-referentie
description: Maakt het mogelijk een VBA-project te maken via COM-interface
type: docs
url: /nl/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Maakt het mogelijk een VBA-project te maken via COM-interface
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Maakt een nieuw VBA-project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Leest VBA-project vanuit OLE-container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Maakt een nieuw VBA-project.

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nieuw VBA-project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Leest VBA-project vanuit OLE-container.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Gelezen VBA-project