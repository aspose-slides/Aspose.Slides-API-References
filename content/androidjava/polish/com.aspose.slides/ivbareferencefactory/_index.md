---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia tworzenie referencji projektów VBA za pośrednictwem interfejsu COM
type: docs
url: /pl/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Umożliwia tworzenie referencji projektów VBA za pośrednictwem interfejsu COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Tworzy nową referencję biblioteki typów OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Tworzy nową referencję biblioteki typów OLE Automation.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa referencji projektu VBA String |
| libid | java.lang.String | Identyfikator biblioteki typów Automation String |

**Zwraca:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nową referencję biblioteki typów OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)