---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /pl/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Umożliwia tworzenie odwołań do projektów VBA za pośrednictwem interfejsu COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Tworzy nowe odwołanie do biblioteki typów OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Tworzy nowe odwołanie do biblioteki typów OLE Automation.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa odwołania do projektu VBA typu String |
| libid | java.lang.String | Identyfikator biblioteki typów Automation typu String |

**Zwraca:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nowe odwołanie do biblioteki typów OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)