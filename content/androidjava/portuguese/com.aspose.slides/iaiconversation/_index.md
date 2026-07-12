---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Representa uma instância de conversa.
type: docs
url: /pt/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Representa uma instância de conversa. Ao contrário das chamadas de IA regulares, as conversas mantêm todo o contexto.
## Métodos

| Método | Descrição |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Sends conversation request message including entire context and returns response. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Envia mensagem de solicitação de conversa incluindo todo o contexto e retorna a resposta.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String | A instrução ou mensagem a ser processada pelo modelo de IA. |

**Retorno:**
java.lang.String - A mensagem gerada pelo modelo de IA em resposta à instrução fornecida dentro do contexto da conversa.