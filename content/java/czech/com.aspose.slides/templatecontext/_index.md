---
title: TemplateContext
second_title: Aspose.Slides pro Java - referenční API
description: Reprezentuje rozhraní modelového objektu pro šablonový engine.
type: docs
url: /cs/com.aspose.slides/templatecontext/
---
**Inheritance:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Representuje rozhraní modelového objektu pro šablonový engine.
## Metody

| Metoda | Popis |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Vytvoří kontext podřízené šablony. |
| [getObject()](#getObject--) | Vrací modelový objekt. |
| [getOutput()](#getOutput--) | Vrací kolekci výstupních prvků hostitelského dokumentu. |
| [getLocal()](#getLocal--) | Vrací místní úložiště aktuálního kontextu šablony. |
| [getGlobal()](#getGlobal--) | Vrací globální úložiště hostitelského dokumentu. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Vytvoří kontext podřízené šablony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| subModel | TSubModel | Podřízený modelový objekt. |

**Vrací:**
[TemplateContext](../../com.aspose.slides/templatecontext) – Nový kontext šablony s daným modelem a výstupní kolekcí rodiče a globálním úložištěm.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Vrací modelový objekt. Pouze pro čtení Object.

**Vrací:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Vrací kolekci výstupních prvků hostitelského dokumentu. Pouze pro čtení [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Vrací:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Vrací místní úložiště aktuálního kontextu šablony. Pouze pro čtení [Storage](../../com.aspose.slides/storage).

**Vrací:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Vrací globální úložiště hostitelského dokumentu. Pouze pro čtení [Storage](../../com.aspose.slides/storage).

**Vrací:**
[Storage](../../com.aspose.slides/storage)