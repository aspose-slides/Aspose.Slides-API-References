---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Interface do cliente web AI.
type: docs
url: /pt/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interface do cliente web AI. Esta interface permite substituir diferentes modelos de linguagem AI. Classes que implementam esta interface devem ser usadas juntamente com SlidesAIAgent.
## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Envia uma instrução de chat ao modelo AI usando uma instância HttpConnection fornecida e retorna a mensagem de resposta para a instrução dada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String | A instrução ou mensagem a ser processada pelo modelo AI. |

**Retorna:**
java.lang.String - A mensagem gerada pelo modelo AI em resposta à instrução dada.
### createConversation() {#createConversation--}
```
public abstract IIAConversation createConversation()
```


Cria uma instância de conversa. Ao contrário das chamadas AI regulares, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma instância [IAIConversation](../../com.aspose.slides/iaiconversation).