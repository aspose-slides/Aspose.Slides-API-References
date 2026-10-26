---
title: VbaReferenceFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa VBA-projektreferenser via COM-gränssnitt
type: docs
url: /sv/com.aspose.slides/vbareferencefactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Tillåter att skapa VBA-projektreferenser via COM-gränssnitt
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInstance()](#getInstance--) | VBA-projektreferenser fabrik statisk instans. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Skapar ny OLE Automation-typbibliotekreferens. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA-projektreferenser fabrik statisk instans. Skrivskyddad [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Returnerar:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Skapar ny OLE Automation-typbibliotekreferens.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Returnerar:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Ny OLE Automation-typbibliotekreferens