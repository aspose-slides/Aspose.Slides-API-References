---
title: AsposeAIWebClient
second_title: Aspose.Slides の Java API リファレンス
description: Asposeの独自LLMに接続する組み込み実装です。
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

Aspose独自のLLMに接続する組み込み[IAIWebClient](../../com.aspose.slides/iaiwebclient)実装です。これはパラメータなしの SlidesAIAgent() コンストラクタで使用されるデフォルトのクライアントです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | AsposeのデフォルトLLMエンドポイントに接続するAspose AIウェブクライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 外部で管理された  HttpURLConnection  を使用して、AsposeのデフォルトLLMエンドポイントに接続するAspose AIウェブクライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | カスタムエンドポイントURLに接続するAspose AIウェブクライアントのインスタンスを作成します。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 外部で管理された  HttpURLConnection  を使用して、カスタムエンドポイントURLに接続するAspose AIウェブクライアントのインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | AIモデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。 |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [dispose()](#dispose--) | このインスタンスが使用するリソースを解放します。 |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


デフォルトのAspose LLMエンドポイントに接続するAspose AIウェブクライアントのインスタンスを作成します。これはパラメータなしの SlidesAIAgent() コンストラクタで使用されるクライアントであるため、クライアントを SlidesAIAgent(IAIWebClient) コンストラクタに直接渡す場合にのみ、明示的に作成する必要があります。

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


外部で管理された  HttpURLConnection  を使用して、デフォルトのAspose LLMエンドポイントに接続するAspose AIウェブクライアントのインスタンスを作成します。提供された  HttpURLConnection  はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 外部で管理された  HttpURLConnection  インスタンスです。

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


カスタムエンドポイントURLに接続するAspose AIウェブクライアントのインスタンスを作成します。Aspose.Slidesチームが提供するURLがある場合にこのオーバーロードを使用し、それ以外の場合はデフォルトURLの AsposeAIWebClient() オーバーロードを使用してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slidesチームが提供するAspose LLMのエンドポイントURLです。

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


外部で管理された  HttpURLConnection  を使用して、カスタムエンドポイントURLに接続するAspose AIウェブクライアントのインスタンスを作成します。提供された  HttpURLConnection  はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。Aspose.Slidesチームが提供するURLがあり、独自の  HttpURLConnection  を提供したい場合にこのオーバーロードを使用してください。デフォルトURLで独自の  HttpURLConnection  のみが必要な場合は、AsposeAIWebClient(HttpURLConnection) オーバーロードを使用してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slidesチームが提供するAspose LLMのエンドポイントURLです。 |
| httpClient | java.net.HttpURLConnection | 外部で管理された  HttpURLConnection  インスタンスです。

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
| --- | --- | |
| instruction | java.lang.String | AIモデルが処理する指示またはメッセージです。

**戻り値:**
java.lang.String - 指定された指示に応答してAIモデルが生成したメッセージです。
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```


会話インスタンスを作成します。通常のAI呼び出しとは異なり、会話は全体のコンテキストを保持します。

**戻り値:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) インスタンスです。
### dispose() {#dispose--}
```
public final void dispose()
```


このインスタンスが使用するリソースを解放します。