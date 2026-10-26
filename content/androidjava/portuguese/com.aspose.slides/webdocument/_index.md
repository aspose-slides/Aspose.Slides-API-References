---
title: WebDocument
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma forma de transição da apresentação para salvar em um formato web.
type: docs
url: /pt/com.aspose.slides/webdocument/
---
**Inheritance:**
java.lang.Object
```
public class WebDocument
```

Representa uma forma de transição da apresentação para salvar em formato web.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) construtor. |
## Métodos

| Método | Descrição |
| --- | --- |
| [save()](#save--) | Salva a saída do documento. |
| [getInput()](#getInput--) | Retorna a coleção de elementos de entrada (modelos) do documento. |
| [getOutput()](#getOutput--) | Retorna a coleção de elementos de saída do documento. |
| [getGlobal()](#getGlobal--) | Retorna o armazenamento global do documento. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) construtor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Conjunto de opções para o documento. |

### save() {#save--}
```
public final void save()
```

Salva a saída do documento.

### getInput() {#getInput--}
```
public final Input getInput()
```

Retorna a coleção de elementos de entrada (modelos) do documento. Somente leitura [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Retorna:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Retorna a coleção de elementos de saída do documento. Somente leitura [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // colocar a propriedade "slideMargin" para usar nos modelos
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... configurar outras opções do documento e então salvar o documento
>   document.save();
> ```


**Retorna:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Retorna o armazenamento global do documento. Somente leitura [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // colocar a propriedade "slideMargin" para usar nos modelos
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... configurar outras opções do documento e então salvar o documento
>   document.save();
> ```

**Retorna:**
[Storage](../../com.aspose.slides/storage)