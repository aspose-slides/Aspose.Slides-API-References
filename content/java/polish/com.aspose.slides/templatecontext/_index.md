---
title: TemplateContext
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje interfejs obiektu modelu dla silnika szablonów.
type: docs
url: /pl/com.aspose.slides/templatecontext/
---
**Dziedziczenie:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Reprezentuje interfejs obiektu modelu dla silnika szablonów.
## Metody

| Metoda | Opis |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Tworzy kontekst szablonu potomnego. |
| [getObject()](#getObject--) | Zwraca obiekt modelu. |
| [getOutput()](#getOutput--) | Zwraca kolekcję elementów wyjścia dokumentu gospodarza. |
| [getLocal()](#getLocal--) | Zwraca lokalne przechowywanie bieżącego kontekstu szablonu. |
| [getGlobal()](#getGlobal--) | Zwraca globalne przechowywanie dokumentu gospodarza. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Tworzy kontekst szablonu potomnego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subModel | TSubModel | Obiekt modelu potomnego. |

**Zwraca:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nowy kontekst szablonu z podanym modelem i kolekcją wyjścia rodzica oraz globalnym magazynem.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Zwraca obiekt modelu. Tylko do odczytu Object.

**Zwraca:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Zwraca kolekcję elementów wyjścia dokumentu gospodarza. Tylko do odczytu [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Zwraca:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Zwraca lokalne przechowywanie bieżącego kontekstu szablonu. Tylko do odczytu [Storage](../../com.aspose.slides/storage).

**Zwraca:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Zwraca globalne przechowywanie dokumentu gospodarza. Tylko do odczytu [Storage](../../com.aspose.slides/storage).

**Zwraca:**
[Storage](../../com.aspose.slides/storage)