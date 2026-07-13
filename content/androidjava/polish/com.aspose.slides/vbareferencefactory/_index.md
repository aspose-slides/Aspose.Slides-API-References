---
title: VbaReferenceFactory
second_title: Aspose.Slides dla Androida poprzez dokumentację API Java
description: Umożliwia tworzenie odwołań do projektów VBA za pośrednictwem interfejsu COM
type: docs
url: /pl/com.aspose.slides/vbareferencefactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Umożliwia tworzenie odwołań do projektów VBA za pośrednictwem interfejsu COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInstance()](#getInstance--) | Statyczna instancja fabryki odwołań do projektów VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Tworzy nowe odwołanie do biblioteki typów OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Statyczna instancja fabryki odwołań do projektów VBA. Tylko do odczytu [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Zwraca:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Tworzy nowe odwołanie do biblioteki typów OLE Automation.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Zwraca:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nowe odwołanie do biblioteki typów OLE Automation