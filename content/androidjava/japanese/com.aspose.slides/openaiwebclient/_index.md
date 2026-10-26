---
title: OpenAIWebClient
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: OpenAI API に接続する組み込み実装です。
type: docs
url: /ja/com.aspose.slides/openaiwebclient/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

OpenAI API に接続する組み込みの [IAIWebClient](../../com.aspose.slides/iaiwebclient) 実装です。

## コンストラクタ

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI Web クライアントのインスタンスを作成します。 |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 外部で管理された HttpClient を使用する OpenAI Web クライアントのインスタンスを作成します。 |

## メソッド

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [close()](#close--) | このインスタンスが使用しているリソースを解放します。 |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI Web クライアントのインスタンスを作成します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI 言語モデル。可能な値: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API キー。 |
| organizationId | java.lang.String | 組織 ID（オプション）。 |
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

外部で管理された HttpClient を使用する OpenAI Web クライアントのインスタンスを作成します。提供された HttpClient はこのインスタンスによって破棄されず、呼び出し元が所有し続けます。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI 言語モデル。可能な値: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API キー |
| organizationId | java.lang.String | 組織 ID（オプション） |
| httpClient | java.net.HttpURLConnection | 外部で管理された HttpClient インスタンス |
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

提供された HttpConnection インスタンスを使用して AI モデルにチャット指示を送信し、指示に対する応答メッセージを返します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**戻り値:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

会話インスタンスを作成します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。

**戻り値:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) のインスタンス。

### close() {#close--}
```
public final void close()
```

このインスタンスが使用しているリソースを解放します。