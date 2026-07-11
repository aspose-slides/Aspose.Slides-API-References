---
title: AsposeAIWebClient
second_title: Aspose.Slides の Java API リファレンス
description: Aspose 独自の LLM に接続する組み込み実装です。
type: docs
url: /ja/com.aspose.slides/asposeaiwebclient/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Aspose独自のLLMに接続する組み込みの[IAIWebClient](../../com.aspose.slides/iaiwebclient)実装です。これはパラメータなしの  SlidesAIAgent()  コンストラクタで使用されるデフォルトクライアントです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Web クライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 外部で管理された  HttpClient  を使用して、デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Web クライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | カスタムエンドポイント URL に接続する Aspose AI Web クライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 外部で管理された  HttpClient  を使用して、カスタムエンドポイント URL に接続する Aspose AI Web クライアントのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [dispose()](#dispose--) | このインスタンスが使用するリソースを解放します。 |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Web クライアントのインスタンスを作成します。これはパラメータなしの  SlidesAIAgent()  コンストラクタで使用されるクライアントであるため、クライアントを  SlidesAIAgent(IAIWebClient)  コンストラクタに直接渡す場合にのみ明示的に作成する必要があります。

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

外部で管理された  HttpClient  を使用して、デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Web クライアントのインスタンスを作成します。提供された  HttpClient  はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 外部で管理された  HttpClient  インスタンス。```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

カスタムエンドポイント URL に接続する Aspose AI Web クライアントのインスタンスを作成します。Aspose.Slides チームから提供された URL がある場合にこのオーバーロードを使用し、そうでない場合はデフォルト URL を持つ  AsposeAIWebClient()  オーバーロードを使用してください。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides チームが提供する Aspose LLM のエンドポイント URL。```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

外部で管理された  HttpClient  を使用して、カスタムエンドポイント URL に接続する Aspose AI Web クライアントのインスタンスを作成します。提供された  HttpClient  はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。Aspose.Slides チームが提供する URL があり、独自の  HttpClient  を使用したい場合にこのオーバーロードを使用してください。デフォルト URL で独自の  HttpClient  のみが必要な場合は、  AsposeAIWebClient(HttpClient)  オーバーロードを使用してください。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides チームが提供する Aspose LLM のエンドポイント URL。 |
| httpClient | java.net.HttpURLConnection | 外部で管理された  HttpClient  インスタンス。```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

提供された HttpConnection インスタンスを使用して AI モデルにチャット指示を送信し、指示に対する応答メッセージを返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returns:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

会話インスタンスを作成します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

このインスタンスが使用するリソースを解放します。