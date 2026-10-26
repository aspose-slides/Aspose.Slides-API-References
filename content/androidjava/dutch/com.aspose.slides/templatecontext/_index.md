---
title: TemplateContext
second_title: Aspose.Slides voor Android via Java API-referentie
description: Representeert een modelobjectinterface voor een sjabloonengine.
type: docs
url: /nl/com.aspose.slides/templatecontext/
---
**Erfenis:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Representeert een modelobjectinterface voor een sjabloonengine.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Maakt een kind sjablooncontext. |
| [getObject()](#getObject--) | Retourneert het modelobject. |
| [getOutput()](#getOutput--) | Retourneert een collectie van uitvoerelementen van het hostdocument. |
| [getLocal()](#getLocal--) | Retourneert lokale opslag van de huidige sjablooncontext. |
| [getGlobal()](#getGlobal--) | Retourneert globale opslag van het hostdocument. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Maakt een kind sjablooncontext.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subModel | TSubModel | Kindermodelobject. |

**Returns:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nieuwe sjablooncontext met gegeven model en de outputcollectie van de ouder en globale opslag.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Retourneert het modelobject. Alleen-lezen Object.

**Returns:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Retourneert een collectie van uitvoerelementen van het hostdocument. Alleen-lezen [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Returns:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Retourneert lokale opslag van de huidige sjablooncontext. Alleen-lezen [Storage](../../com.aspose.slides/storage).

**Returns:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Retourneert globale opslag van het hostdocument. Alleen-lezen [Storage](../../com.aspose.slides/storage).

**Returns:**
[Storage](../../com.aspose.slides/storage)