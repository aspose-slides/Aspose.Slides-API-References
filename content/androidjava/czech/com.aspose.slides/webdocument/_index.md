---
title: WebDocument
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje přechodový formát prezentace pro uložení do webového formátu.
type: docs
url: /cs/com.aspose.slides/webdocument/
---
**Dědičnost:**
java.lang.Object
```
public class WebDocument
```

Představuje přechodový formát prezentace pro uložení do webového formátu.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [save()](#save--) | Ukládá výstup dokumentu. |
| [getInput()](#getInput--) | Vrací kolekci vstupních prvků (šablon) dokumentu. |
| [getOutput()](#getOutput--) | Vrací kolekci výstupních prvků dokumentu. |
| [getGlobal()](#getGlobal--) | Vrací globální úložiště dokumentu. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) konstruktor.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Možnosti nastavené pro dokument. |

### save() {#save--}
```
public final void save()
```


Ukládá výstup dokumentu.

### getInput() {#getInput--}
```
public final Input getInput()
```


Vrací kolekci vstupních prvků (šablon) dokumentu. Pouze pro čtení [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Vrací:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Vrací kolekci výstupních prvků dokumentu. Pouze pro čtení [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ``` 
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // vložte vlastnost "slideMargin" pro použití ze šablon
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... nastavte další možnosti dokumentu a poté uložte dokument
>   document.save();
```

**Vrací:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Vrací globální úložiště dokumentu. Pouze pro čtení [Storage](../../com.aspose.slides/storage).

--------------------

> ``` 
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // vložte vlastnost "slideMargin" pro použití ze šablon
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... nastavte další možnosti dokumentu a poté uložte dokument
>   document.save();
```

**Vrací:**
[Storage](../../com.aspose.slides/storage)