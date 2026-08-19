---
title: IVbaReferenceFactory
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje vytvořit reference na VBA projekt přes rozhraní COM
type: docs
url: /cs/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Umožňuje vytvořit reference na VBA projekt přes rozhraní COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Vytvoří novou referenci na typovou knihovnu OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Vytvoří novou referenci na typovou knihovnu OLE Automation.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název reference na VBA projekt String |
| libid | java.lang.String | Identifikátor typové knihovny Automation String |

**Návratová hodnota:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nová referenace na typovou knihovnu OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)