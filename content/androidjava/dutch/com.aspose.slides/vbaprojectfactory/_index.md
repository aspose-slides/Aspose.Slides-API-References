---
title: VbaProjectFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe om VBA project te maken via COM interface
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

Staat toe om VBA-project te maken via COM-interface
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | VBA-projectfabriek statische instantie. |
| [createVbaProject()](#createVbaProject--) | Maakt een nieuw VBA-project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Leest VBA-project vanuit OLE-container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA-projectfabriek statische instantie. Alleen-lezen [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

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


Leest VBA-project vanuit OLE-container.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] |  |

**Retour:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Gelezen VBA-project