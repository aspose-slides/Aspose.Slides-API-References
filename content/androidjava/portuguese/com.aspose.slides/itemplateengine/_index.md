---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Representa um mecanismo de modelo que transforma pares de modelo e dados em saída resultante, normalmente HTML.
type: docs
url: /pt/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Representa um mecanismo de modelo que transforma pares de modelo e dados em saída resultante (normalmente HTML).

## Métodos

| Método | Descrição |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adiciona o modelo à coleção de modelos. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforma o modelo com a chave fornecida e o objeto de modelo para saída. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Adiciona o modelo à coleção de modelos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | java.lang.String | Chave para o modelo na coleção de modelos. |
| template | java.lang.String | Conteúdo do modelo. |
| modelType | com.aspose.ms.System.Type | Tipo de um objeto de modelo para o modelo. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Transforma o modelo com a chave fornecida e o objeto de modelo para saída.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | java.lang.String | Chave para o modelo na coleção de modelos. |
| model | java.lang.Object | Objeto de modelo com dados para a transformação. |

**Retorno:**
java.lang.String - Resultado da saída como uma String.