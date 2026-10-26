---
title: TemplateContext
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un'interfaccia di oggetto modello per un motore di template.
type: docs
url: /it/com.aspose.slides/templatecontext/
---
**Ereditarietà:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Rappresenta un'interfaccia di oggetto modello per un motore di template.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Crea un contesto di template figlio. |
| [getObject()](#getObject--) | Restituisce l'oggetto modello. |
| [getOutput()](#getOutput--) | Restituisce la collezione di elementi di output del documento host. |
| [getLocal()](#getLocal--) | Restituisce lo storage locale del contesto di template corrente. |
| [getGlobal()](#getGlobal--) | Restituisce lo storage globale del documento host. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Crea un contesto di template figlio.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subModel | TSubModel | Oggetto modello figlio. |

**Restituisce:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nuovo contesto di template con il modello fornito e la collezione di output del genitore e lo storage globale.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Restituisce l'oggetto modello. Sola lettura Object.

**Restituisce:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Restituisce la collezione di elementi di output del documento host. Sola lettura [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Restituisce:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Restituisce lo storage locale del contesto di template corrente. Sola lettura [Storage](../../com.aspose.slides/storage).

**Restituisce:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Restituisce lo storage globale del documento host. Sola lettura [Storage](../../com.aspose.slides/storage).

**Restituisce:**
[Storage](../../com.aspose.slides/storage)