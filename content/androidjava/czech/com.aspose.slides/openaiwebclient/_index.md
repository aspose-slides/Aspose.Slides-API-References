---
title: OpenAIWebClient
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Vestavěný lehký webový klient OpenAI
type: docs
url: /cs/com.aspose.slides/openaiwebclient/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Vestavěný lehký webový klient OpenAI
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Vytvoří instanci OpenAI Web client. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Vytvoří instanci OpenAI Web client. |
## Metody

| Metoda | Popis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Odešle chat instrukci modelu AI pomocí externě spravované  instance a vrátí odpovědní zprávu na danou instrukci. |
| [createConversation()](#createConversation--) | Vytvoří instanci konverzace. |
| [close()](#close--) | Uvolní prostředky používané touto instancí. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Vytvoří instanci OpenAI Web client.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | Jazykový model OpenAI. Možné hodnoty: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klíč API OpenAI |
| organizationId | java.lang.String | ID organizace (volitelné) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Vytvoří instanci OpenAI Web client.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| model | java.lang.String | Jazykový model OpenAI. Možné hodnoty: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Klíč API OpenAI |
| organizationId | java.lang.String | ID organizace (volitelné) |
| httpClient | java.net.HttpURLConnection | Externě spravovaná instance HttpURLConnection. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Odešle chat instrukci modelu AI pomocí externě spravované  instance a vrátí odpovědní zprávu na danou instrukci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukce nebo zpráva, která má být zpracována modelem AI |

**Vrací:**
java.lang.String - Zpráva vygenerovaná modelem AI jako odpověď na danou instrukci.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Vytvoří instanci konverzace. Na rozdíl od běžných volání AI konverzace uchovávají celý kontext.

**Vrací:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instanci [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```


Uvolní prostředky používané touto instancí.