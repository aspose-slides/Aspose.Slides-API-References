---
title: TemplateContext
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje rozhraní objektu modelu pro šablonovací engine.
type: docs
url: /cs/com.aspose.slides/templatecontext/
---
**Dědičnost:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Představuje rozhraní objektu modelu pro šablonovací engine.
## Metody

| Metoda | Popis |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Vytvoří podkontext šablony. |
| [getObject()](#getObject--) | Vrací objekt modelu. |
| [getOutput()](#getOutput--) | Vrací kolekci výstupních prvků hostitelského dokumentu. |
| [getLocal()](#getLocal--) | Vrací lokální úložiště aktuálního kontextu šablony. |
| [getGlobal()](#getGlobal--) | Vrací globální úložiště hostitelského dokumentu. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Vytvoří podkontext šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subModel | TSubModel | Objekt podřízeného modelu. |

**Vrací:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nový kontext šablony s daným modelem a kolekcí výstupu rodiče a globálním úložištěm.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Vrací objekt modelu. Pouze pro čtení Object.

**Vrací:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Vrací kolekci výstupních prvků hostitelského dokumentu. Pouze ke čtení [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Vrací:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Vrací lokální úložiště aktuálního kontextu šablony. Pouze ke čtení [Storage](../../com.aspose.slides/storage).

**Vrací:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Vrací globální úložiště hostitelského dokumentu. Pouze ke čtení [Storage](../../com.aspose.slides/storage).

**Vrací:**
[Storage](../../com.aspose.slides/storage)