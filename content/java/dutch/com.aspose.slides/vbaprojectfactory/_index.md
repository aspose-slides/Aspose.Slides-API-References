---
title: VbaProjectFactory
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe een VBA-project te maken via COM-interface
type: docs
url: /nl/com.aspose.slides/vbaprojectfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Staat toe een VBA-project te maken via COM-interface
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project-fabriek statisch exemplaar. |
| [createVbaProject()](#createVbaProject--) | Maakt een nieuw VBA-project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Leest VBA-project uit OLE-container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA project-fabriek statisch exemplaar. Alleen-lezen [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Retour:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Maakt een nieuw VBA-project.

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nieuw VBA-project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Leest VBA-project uit OLE-container.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] |  |

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Lees VBA-project