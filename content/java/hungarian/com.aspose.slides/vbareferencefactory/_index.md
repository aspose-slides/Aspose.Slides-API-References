---
title: VbaReferenceFactory
second_title: Aspose.Slides for Java API referencia
description: Lehetővé teszi VBA projekt hivatkozások létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/vbareferencefactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Lehetővé teszi VBA projekt hivatkozások létrehozását COM interfészen keresztül
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInstance()](#getInstance--) | VBA projekt hivatkozások gyári statikus példánya. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Új OLE Automation típusú könyvtár hivatkozást hoz létre. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA projekt hivatkozások gyári statikus példánya. Csak olvasható [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Visszatér:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Új OLE Automation típusú könyvtár hivatkozást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Visszatér:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Új OLE Automation típusú könyvtár hivatkozás