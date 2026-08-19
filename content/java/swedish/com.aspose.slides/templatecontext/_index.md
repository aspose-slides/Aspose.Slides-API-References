---
title: TemplateContext
second_title: Aspose.Slides för Java API-referens
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
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Skapar ett underliggande mallkontext. |
| [getObject()](#getObject--) | Returnerar modellobjektet. |
| [getOutput()](#getOutput--) | Returnerar samling av utskelement i värddokumentet. |
| [getLocal()](#getLocal--) | Returnerar lokal lagring för den aktuella mallkontexten. |
| [getGlobal()](#getGlobal--) | Returnerar global lagring för värddokumentet. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Skapar ett underliggande mallkontext.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subModel | TSubModel | Underordnat modellobjekt. |

**Returnerar:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nytt mallkontext med given modell och förälderns utsamlingssamling samt global lagring.
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


Returnerar samling av utskelement i värddokumentet. Skrivskyddad [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Returnerar:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Returnerar lokal lagring för den aktuella mallkontexten. Skrivskyddad [Storage](../../com.aspose.slides/storage).

**Returnerar:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Returnerar global lagring för värddokumentet. Skrivskyddad [Storage](../../com.aspose.slides/storage).

**Returnerar:**
[Storage](../../com.aspose.slides/storage)