---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /pt/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Representa um mecanismo de modelo que transforma o par de modelo e dados em uma saída resultante (geralmente HTML).
## Métodos

| Método | Descrição |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adds the template to the template collection. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforms the template with the given key and model object to output. |
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
| modelType | com.aspose.ms.System.Type | Tipo de um objeto modelo para o modelo. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Transforma o modelo com a chave fornecida e o objeto modelo para saída.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | java.lang.String | Chave para o modelo na coleção de modelos. |
| model | java.lang.Object | Objeto modelo com dados para a transformação. |

**Retorna:**
java.lang.String - Saída resultante como uma String.