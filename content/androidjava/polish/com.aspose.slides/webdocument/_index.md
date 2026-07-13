---
title: WebDocument
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje formularz przejściowy prezentacji do zapisu w formacie internetowym.
type: docs
url: /pl/com.aspose.slides/webdocument/
---
**Dziedziczenie:**
java.lang.Object
```
public class WebDocument
```

Reprezentuje formę przejściową prezentacji do zapisu w formacie internetowym.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) konstruktor. |

## Metody

| Metoda | Opis |
| --- | --- |
| [save()](#save--) | Zapisuje wyjście dokumentu. |
| [getInput()](#getInput--) | Zwraca kolekcję elementów wejściowych (szablonów) dokumentu. |
| [getOutput()](#getOutput--) | Zwraca kolekcję elementów wyjściowych dokumentu. |
| [getGlobal()](#getGlobal--) | Zwraca globalne przechowywanie dokumentu. |

### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) konstruktor.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Opcje ustawione dla dokumentu. |

### save() {#save--}
```
public final void save()
```

Zapisuje wyjście dokumentu.

### getInput() {#getInput--}
```
public final Input getInput()
```

Zwraca kolekcję elementów wejściowych (szablonów) dokumentu. Tylko do odczytu [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Zwraca:**
[Input](../../com.aspose.slides/input)

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Zwraca kolekcję elementów wyjściowych dokumentu. Tylko do odczytu [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // umieść właściwość "slideMargin" do użycia z szablonów
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... skonfiguruj inne opcje dokumentu, a następnie zapisz dokument
>   document.save();
> ```

**Zwraca:**
[Output](../../com.aspose.slides/output)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Zwraca globalne przechowywanie dokumentu. Tylko do odczytu [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // umieść właściwość "slideMargin" do użycia z szablonów
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... skonfiguruj inne opcje dokumentu i następnie zapisz dokument
>   document.save();
> ```

**Zwraca:**
[Storage](../../com.aspose.slides/storage)