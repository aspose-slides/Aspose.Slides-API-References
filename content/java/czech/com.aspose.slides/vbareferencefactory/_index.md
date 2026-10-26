---
title: VbaReferenceFactory
second_title: Aspose.Slides pro Java API referenci
description: Umožňuje vytvářet odkazy na projekty VBA přes rozhraní COM
type: docs
url: /cs/com.aspose.slides/vbareferencefactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Umožňuje vytvářet odkazy na projekt VBA přes rozhraní COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInstance()](#getInstance--) | Statická instance továrny referencí projektu VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Vytvoří novou referenci na knihovnu typů OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Statická instance továrny referencí projektu VBA. Pouze pro čtení [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Vrací:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Vytvoří novou referenci na knihovnu typů OLE Automation.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Vrací:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nová reference na knihovnu typů OLE Automation