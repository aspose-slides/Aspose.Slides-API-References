---
title: TemplateContext
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett modellobjektgränssnitt för en mallmotor.
type: docs
url: /sv/com.aspose.slides/templatecontext/
---
**Arv:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Representerar ett modellobjektgränssnitt för en mallmotor.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Skapar ett barnmallkontext. |
| [getObject()](#getObject--) | Returnerar modellobjektet. |
| [getOutput()](#getOutput--) | Returnerar en samling av utdataelement i värddokumentet. |
| [getLocal()](#getLocal--) | Returnerar lokal lagring av det aktuella mallkontextet. |
| [getGlobal()](#getGlobal--) | Returnerar global lagring av värddokumentet. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Skapar ett barnmallkontext.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subModel | TSubModel | Barnmodellobjekt. |

**Returnerar:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nytt mallkontext med given modell och förälderns utdata-samling samt global lagring.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Returnerar modellobjektet. Skrivskyddad Object.

**Returnerar:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Returnerar en samling av utdataelement i värddokumentet. Skrivskyddad [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Returnerar:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Returnerar lokal lagring av det aktuella mallkontextet. Skrivskyddad [Storage](../../com.aspose.slides/storage).

**Returnerar:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Returnerar global lagring av värddokumentet. Skrivskyddad [Storage](../../com.aspose.slides/storage).

**Returnerar:**
[Storage](../../com.aspose.slides/storage)