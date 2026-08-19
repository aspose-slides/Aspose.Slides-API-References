---
title: TemplateContext
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een modelobjectinterface voor een sjabloonengine.
type: docs
url: /nl/com.aspose.slides/templatecontext/
---
**Erfenis:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Vertegenwoordigt een modelobjectinterface voor een sjabloonengine.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Maakt een kindsjablooncontext. |
| [getObject()](#getObject--) | Retourneert het modelobject. |
| [getOutput()](#getOutput--) | Retourneert de collectie uitvoerelementen van het hostdocument. |
| [getLocal()](#getLocal--) | Retourneert lokale opslag van de huidige sjablooncontext. |
| [getGlobal()](#getGlobal--) | Retourneert globale opslag van het hostdocument. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Maakt een kindsjablooncontext.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subModel | TSubModel | Kindmodelobject. |

**Retour:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nieuwe sjablooncontext met gegeven model en de uitvoercollectie van de ouder en globale opslag.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Retourneert het modelobject. Alleen-lezen Object.

**Retour:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Retourneert de collectie uitvoerelementen van het hostdocument. Alleen-lezen [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Retour:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Retourneert lokale opslag van de huidige sjablooncontext. Alleen-lezen [Storage](../../com.aspose.slides/storage).

**Retour:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Retourneert globale opslag van het hostdocument. Alleen-lezen [Storage](../../com.aspose.slides/storage).

**Retour:**
[Storage](../../com.aspose.slides/storage)