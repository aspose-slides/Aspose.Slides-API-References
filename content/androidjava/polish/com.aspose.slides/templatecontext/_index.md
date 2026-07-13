---
title: TemplateContext
second_title: Aspose.Slides dla Androida – odniesienie API Java
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
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Tworzy kontekst szablonu podrzędnego. |
| [getObject()](#getObject--) | Zwraca obiekt modelu. |
| [getOutput()](#getOutput--) | Zwraca kolekcję elementów wyjściowych dokumentu hosta. |
| [getLocal()](#getLocal--) | Zwraca lokalne przechowywanie bieżącego kontekstu szablonu. |
| [getGlobal()](#getGlobal--) | Zwraca globalne przechowywanie dokumentu hosta. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Tworzy kontekst szablonu podrzędnego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| subModel | TSubModel | Obiekt modelu podrzędnego. |

**Zwraca:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nowy kontekst szablonu z podanym modelem oraz wyjściową kolekcją rodzica i globalnym przechowywaniem.
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

Zwraca kolekcję elementów wyjściowych dokumentu hosta. Tylko do odczytu [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

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

Zwraca globalne przechowywanie dokumentu hosta. Tylko do odczytu [Storage](../../com.aspose.slides/storage).

**Zwraca:**
[Storage](../../com.aspose.slides/storage)