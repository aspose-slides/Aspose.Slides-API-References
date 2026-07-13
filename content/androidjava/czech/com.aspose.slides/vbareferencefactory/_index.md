---
title: VbaReferenceFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvářet reference projektů VBA přes COM rozhraní
type: docs
url: /cs/com.aspose.slides/vbareferencefactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Umožňuje vytvářet reference projektů VBA přes COM rozhraní
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInstance()](#getInstance--) | Statická instance továrny na reference projektů VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Vytváří novou referenci knihovny typů OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Statická instance továrny na reference projektů VBA. Pouze pro čtení [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Vrací:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Vytváří novou referenci knihovny typů OLE Automation.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Vrací:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nová reference knihovny typů OLE Automation