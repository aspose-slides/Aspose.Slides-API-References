---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides の Java 用 API リファレンス
description: 指定されたベース URL の OpenAI 互換 LLM プロバイダーに接続する組み込み実装です。
type: docs
url: /ja/com.aspose.slides/openaicompatiblewebclient/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

指定されたベース URL の OpenAI 互換 LLM プロバイダーに接続する組み込み [IAIWebClient](../../com.aspose.slides/iaiwebclient) 実装です。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI 互換 Web クライアントのインスタンスを作成します。 |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 外部で管理された  HttpURLConnection を使用する OpenAI 互換 Web クライアントのインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 外部で管理された HttpURLConnection インスタンスを使用して AI モデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。 |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [dispose()](#dispose--) | このインスタンスが使用するリソースを解放します。 |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI 互換 Web クライアントのインスタンスを作成します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| model | java.lang.String | LLM プロバイダーがサポートするモデル名です。 |
| apiKey | java.lang.String | API キー（トークン）。 |
| baseUrl | java.lang.String | OpenAI 互換 LLM のベース URL。 |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
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

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

外部で管理された  HttpURLConnection を使用する OpenAI 互換 Web クライアントのインスタンスを作成します。提供された  HttpURLConnection はこのインスタンスによって破棄されず、呼び出し元が所有したままです。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| model | java.lang.String | LLM プロバイダーがサポートするモデル名です。 |
| apiKey | java.lang.String | API キー（トークン）。 |
| baseUrl | java.lang.String | OpenAI 互換 LLM のベース URL。 |
| httpClient | java.net.HttpURLConnection | 外部で管理された  HttpURLConnection  インスタンスです。 |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

外部で管理された HttpURLConnection インスタンスを使用して AI モデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instruction | java.lang.String | AI モデルによって処理される指示またはメッセージです。 |

**戻り値:**
java.lang.String - 指定された指示に対する AI モデルが生成したメッセージです。
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

会話インスタンスを作成します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。

**戻り値:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) のインスタンスです。
### dispose() {#dispose--}
```
public final void dispose()
```

このインスタンスが使用するリソースを解放します。