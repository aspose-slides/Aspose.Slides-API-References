---
title: TemplateContext
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma interface de objeto modelo para um mecanismo de modelo.
type: docs
url: /pt/com.aspose.slides/templatecontext/
---
**Herança:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Representa uma interface de objeto modelo para um mecanismo de modelo.
## Métodos

| Método | Descrição |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Cria um contexto de modelo filho. |
| [getObject()](#getObject--) | Retorna o objeto modelo. |
| [getOutput()](#getOutput--) | Retorna a coleção de elementos de saída do documento host. |
| [getLocal()](#getLocal--) | Retorna o armazenamento local do contexto de modelo atual. |
| [getGlobal()](#getGlobal--) | Retorna o armazenamento global do documento host. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Cria um contexto de modelo filho.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subModel | TSubModel | Objeto modelo filho. |

**Retorna:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Novo contexto de modelo com o modelo fornecido e a coleção de saída do pai e o armazenamento global.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Retorna o objeto modelo. Somente leitura Object.

**Retorna:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Retorna a coleção de elementos de saída do documento host. Somente leitura [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Retorna:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Retorna o armazenamento local do contexto de modelo atual. Somente leitura [Storage](../../com.aspose.slides/storage).

**Retorna:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Retorna o armazenamento global do documento host. Somente leitura [Storage](../../com.aspose.slides/storage).

**Retorna:**
[Storage](../../com.aspose.slides/storage)