---
title: IVbaReferenceFactory
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Umožňuje vytvářet VBA projektové reference prostřednictvím rozhraní COM
type: docs
url: /cs/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Umožňuje vytvářet VBA projektové reference prostřednictvím rozhraní COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Vytvoří novou referenci knihovny typů OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Vytvoří novou referenci knihovny typů OLE Automation.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název VBA projektové reference String |
| libid | java.lang.String | Identifikátor knihovny typů Automation String |

**Návratová hodnota:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nová referenace knihovny typů OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)