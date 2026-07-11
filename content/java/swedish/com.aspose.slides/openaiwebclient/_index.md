---
title: OpenAIWebClient
second_title: Aspose.Slides för Java API-referens
description: En inbyggd implementation som ansluter till OpenAI API:et.
type: docs
url: /sv/com.aspose.slides/openaiwebclient/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

En inbyggd [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementering som ansluter till OpenAI API:et.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Skapar en instans av OpenAI-webbklienten. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Skapar en instans av OpenAI-webbklienten som använder en externt hanterad HttpClient. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Skapar en konversationsinstans. |
| [close()](#close--) | Frigör resurser som används av denna instans. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Skapar en instans av OpenAI-webbklienten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | OpenAI språkmodell. Möjliga värden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API-nyckel. |
| organizationId | java.lang.String | Organisations-ID (valfritt). |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Skapar en instans av OpenAI-webbklienten som använder en externt hanterad HttpClient. Den tillhandahållna HttpClienten avallokeras inte av denna instans och förblir ägd av anroparen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | OpenAI språkmodell. Möjliga värden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API-nyckel |
| organizationId | java.lang.String | Organisations-ID (valfritt) |
| httpClient | java.net.HttpURLConnection | En externt hanterad HttpClient-instans |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Skickar en chattinstruktion till AI-modellen med en tillhandahållen HttpConnection-instans och returnerar svarmeddelandet för den givna instruktionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returnerar:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.

**Returnerar:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation)-instans.

### close() {#close--}
```
public final void close()
```

Frigör resurser som används av denna instans.