---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: Interface do cliente AI Web.
type: docs
url: /pt/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interface do cliente AI Web. Esta interface permite substituir diferentes modelos de linguagem AI. Classes que implementam esta interface devem ser usadas juntamente com SlidesAIAgent.
## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envia uma instrução de chat para o modelo AI usando uma instância HttpConnection fornecida e retorna a mensagem de resposta para a instrução dada. |
| [createConversation()](#createConversation--) | Cria uma instância de conversa. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Envia uma instrução de chat para o modelo AI usando uma instância HttpConnection fornecida e retorna a mensagem de resposta para a instrução dada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String | A instrução ou mensagem a ser processada pelo modelo AI. |

**Retorna:**
java.lang.String - A mensagem gerada pelo modelo AI em resposta à instrução fornecida.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Cria uma instância de conversa. Ao contrário das chamadas AI regulares, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma instância [IAIConversation](../../com.aspose.slides/iaiconversation).