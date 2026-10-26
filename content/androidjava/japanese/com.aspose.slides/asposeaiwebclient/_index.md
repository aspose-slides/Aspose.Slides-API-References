---
title: AsposeAIWebClient
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: Aspose独自のLLMに接続する組み込み実装です。
type: docs
url: /ja/com.aspose.slides/asposeaiwebclient/
---
**継承:**  
java.lang.Object

**実装されているインターフェイス:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Aspose独自のLLMに接続する組み込み[IAIWebClient](../../com.aspose.slides/iaiwebclient)実装です。パラメータなしの SlidesAIAgent() コンストラクタで使用されるデフォルトクライアントです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Aspose AI Webクライアントのインスタンスを作成し、デフォルトの Aspose LLM エンドポイントに接続します。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 外部で管理された HttpURLConnection を使用して、デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Webクライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | カスタムエンドポイント URL に接続する Aspose AI Webクライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 外部で管理された HttpURLConnection を使用して、カスタムエンドポイント URL に接続する Aspose AI Webクライアントのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | AIモデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。 |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [dispose()](#dispose--) | このインスタンスが使用しているリソースを解放します。 |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Webクライアントのインスタンスを作成します。これはパラメータなしの SlidesAIAgent() コンストラクタで使用されるクライアントであり、明示的に作成する必要があるのは、クライアントを SlidesAIAgent(IAIWebClient) コンストラクタに直接渡す場合のみです。

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

外部で管理された HttpURLConnection を使用して、デフォルトの Aspose LLM エンドポイントに接続する Aspose AI Webクライアントのインスタンスを作成します。提供された HttpURLConnection はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 外部で管理された HttpURLConnection インスタンス。 |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

カスタムエンドポイント URL に接続する Aspose AI Webクライアントのインスタンスを作成します。Aspose.Slides チームから提供された URL がある場合はこのオーバーロードを使用し、そうでない場合はデフォルト URL の AsposeAIWebClient() オーバーロードを使用してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides チームが提供する Aspose LLM のエンドポイント URL。 |

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

外部で管理された HttpURLConnection を使用して、カスタムエンドポイント URL に接続する Aspose AI Webクライアントのインスタンスを作成します。提供された HttpURLConnection はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。Aspose.Slides チームが提供した URL があり独自の HttpURLConnection を使用したい場合にこのオーバーロードを使用し、デフォルト URL で独自の HttpURLConnection のみが必要な場合は AsposeAIWebClient(HttpURLConnection) オーバーロードを使用してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides チームが提供する Aspose LLM のエンドポイント URL。 |
| httpClient | java.net.HttpURLConnection | 外部で管理された HttpURLConnection インスタンス。 |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

AIモデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instruction | java.lang.String | AIモデルが処理する指示またはメッセージ。 |

**戻り値:**
java.lang.String - 指定された指示に対して AIモデルが生成したメッセージ。

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

会話インスタンスを作成します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。

**戻り値:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) のインスタンス。

### dispose() {#dispose--}
```
public final void dispose()
```

このインスタンスが使用しているリソースを解放します。