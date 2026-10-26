---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi VBA projekt hivatkozások létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Lehetővé teszi VBA projekt hivatkozások létrehozását COM interfészen keresztül
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Új OLE Automation típusú könyvtár hivatkozást hoz létre. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Új OLE Automation típusú könyvtár hivatkozást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A VBA projekt hivatkozás neve String |
| libid | java.lang.String | Az Automation típusú könyvtár azonosítója String |

**Visszatérési érték:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Új OLE Automation típusú könyvtár hivatkozás [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)