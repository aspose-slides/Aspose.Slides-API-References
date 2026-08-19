---
title: IAIWebClient
second_title: Aspose.Slides för Java API-referens
description: AI Web-klientgränssnitt.
type: docs
url: /sv/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web-klientgränssnitt. Detta gränssnitt möjliggör att ersätta olika AI-språkmodeller. Klasser som implementerar detta gränssnitt bör användas tillsammans med SlidesAIAgent.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Skickar en chatinstruktion till AI-modellen med en tillhandahållen HttpConnection-instans och returnerar svarmeddelandet till den angivna instruktionen. |
| [createConversation()](#createConversation--) | Skapar en konversationsinstans. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Skickar en chatinstruktion till AI-modellen med en tillhandahållen HttpConnection-instans och returnerar svarmeddelandet till den angivna instruktionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String | Instruktionen eller meddelandet som ska bearbetas av AI-modellen. |

**Returnerar:**
java.lang.String - Meddelandet som genererats av AI-modellen som svar på den angivna instruktionen.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.

**Returnerar:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation)-instans.