---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe om een VBA-project te maken via COM-interface
type: docs
url: /nl/com.aspose.slides/ivbaprojectfactory/
---
```
public interface IVbaProjectFactory
```


Staat toe om een VBA-project te maken via COM-interface
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Maakt een nieuw VBA-project aan. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Leest VBA-project uit OLE-container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Maakt een nieuw VBA-project aan.

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nieuw VBA-project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Leest VBA-project uit OLE-container.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Ole-gegevens byte[] |

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Gelezen VBA-project