---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API リファレンス
description: 指定されたベースURLのOpenAI互換LLMプロバイダーに接続する組み込み実装です。
type: docs
url: /ja/com.aspose.slides/openaicompatiblewebclient/
---

**継承:**  
java.lang.Object

**すべての実装インターフェイス:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

組み込みの[IAIWebClient](../../com.aspose.slides/iaiwebclient)実装で、指定されたベースURLのOpenAI互換LLMプロバイダーに接続します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI互換Webクライアントのインスタンスを作成します。 |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI互換Webクライアントのインスタンスを作成します。このクライアントは外部で管理されたHttpClientを使用します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [dispose()](#dispose--) | このインスタンスが使用したリソースを解放します。 |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI互換Webクライアントのインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| model | java.lang.String | LLMプロバイダーがサポートするモデル名。 |
| apiKey | java.lang.String | APIキー（トークン）。 |
| baseUrl | java.lang.String | OpenAI互換LLMのベースURL。 |
```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

外部で管理されたHttpClientを使用するOpenAI互換Webクライアントのインスタンスを作成します。提供されたHttpClientはこのインスタンスによって破棄されず、呼び出し側が所有し続けます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| model | java.lang.String | LLMプロバイダーがサポートするモデル名。 |
| apiKey | java.lang.String | APIキー（トークン）。 |
| baseUrl | java.lang.String | OpenAI互換LLMのベースURL。 |
| httpClient | java.net.HttpURLConnection | 外部で管理されたHttpClientインスタンスです。 |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

提供されたHttpConnectionインスタンスを使用してAIモデルへチャット指示を送信し、指示に対する応答メッセージを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instruction | java.lang.String |  |

**戻り値:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

会話インスタンスを作成します。通常のAI呼び出しとは異なり、会話は全体のコンテキストを保持します。

**戻り値:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) のインスタンス。

### dispose() {#dispose--}
```
public final void dispose()
```

このインスタンスが使用したリソースを解放します。