---
title: OpenAIWebClient
second_title: Aspose.Slides Androidra Java API referencia segítségével
description: Beépített implementáció, amely az OpenAI API-hoz csatlakozik.
type: docs
url: /hu/com.aspose.slides/openaiwebclient/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Beépített [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás, amely az OpenAI API-hoz kapcsolódik.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Létrehoz egy példányt az OpenAI webkliensből. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Létrehoz egy példányt az OpenAI webkliensből, amely egy külsőleg kezelt HttpClient-et használ. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetés példányt. |
| [close()](#close--) | Felszabadítja az ezen példány által használt erőforrásokat. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Létrehoz egy példányt az OpenAI webkliensből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | OpenAI nyelvi modell. Lehetséges értékek: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API kulcs. |
| organizationId | java.lang.String | Szervezet azonosító (opcionális). |

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

Létrehoz egy példányt az OpenAI webkliensből, amely egy külsőleg kezelt HttpClient-et használ. A megadott HttpClient-et ez a példány nem zárja le, és a hívó birtokában marad.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | OpenAI nyelvi modell. Lehetséges értékek: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API kulcs |
| organizationId | java.lang.String | Szervezet azonosító (opcionális) |
| httpClient | java.net.HttpURLConnection | Egy külsőleg kezelt HttpClient példány |

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

Küld egy csevegési utasítást az AI modellnek egy megadott HttpConnection példány használatával, és visszaadja a válaszüzenetet a megadott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Visszatér:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Létrehoz egy beszélgetés példányt. A szokásos AI hívásokkal ellentétben a beszélgetések megőrzik a teljes kontextust.

**Visszatér:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.

### close() {#close--}
```
public final void close()
```

Felszabadítja az ezen példány által használt erőforrásokat.