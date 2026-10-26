---
title: IAIWebClient
second_title: Aspose.Slides per Android via Riferimento API Java
description: Interfaccia client Web AI.
type: docs
url: /it/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interfaccia client Web AI. Questa interfaccia consente di sostituire diversi modelli di linguaggio AI. Le classi che implementano questa interfaccia devono essere utilizzate insieme a SlidesAIAgent.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Invia un'istruzione di chat al modello AI utilizzando un'istanza HttpConnection fornita e restituisce il messaggio di risposta all'istruzione fornita. |
| [createConversation()](#createConversation--) | Crea un'istanza di conversazione. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Invia un'istruzione di chat al modello AI utilizzando un'istanza HttpConnection fornita e restituisce il messaggio di risposta all'istruzione fornita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instruction | java.lang.String | L'istruzione o il messaggio da elaborare dal modello AI. |

**Restituisce:**
java.lang.String - Il messaggio generato dal modello AI in risposta all'istruzione fornita.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni mantengono l'intero contesto.

**Restituisce:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Un'[IAIConversation](../../com.aspose.slides/iaiconversation) istanza.