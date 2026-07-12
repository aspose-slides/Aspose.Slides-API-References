---
title: VbaReferenceFactory
second_title: Aspose.Slides Android-hoz Java API hivatkozás
description: Lehetővé teszi a VBA projektreferenciák létrehozását COM interfészen keresztül
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

Lehetővé teszi a VBA projektreferenciák létrehozását COM interfészen keresztül
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInstance()](#getInstance--) | VBA projekt referenciák gyári statikus példánya. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Új OLE Automation típuskönyvtár-referenciát hoz létre. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA projekt referenciák gyári statikus példánya. Csak olvasható [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Visszatérési érték:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Új OLE Automation típuskönyvtár-referenciát hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Visszatérési érték:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Új OLE Automation típuskönyvtár-referenciát