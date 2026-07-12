---
title: OpenAIWebClient
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 組み込みの軽量 OpenAI Web クライアント
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

組み込みの軽量 OpenAI Web クライアント
## コンストラクタ

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI Web クライアントのインスタンスを作成します。 |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI Web クライアントのインスタンスを作成します。 |
## メソッド

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 外部で管理されたインスタンスを使用して AI モデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。 |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |
| [close()](#close--) | このインスタンスが使用するリソースを解放します。 |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


OpenAI Web クライアントのインスタンスを作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI 言語モデル。可能な値: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API キー |
| organizationId | java.lang.String | 組織 ID（オプション） |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


OpenAI Web クライアントのインスタンスを作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI 言語モデル。可能な値: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API キー |
| organizationId | java.lang.String | 組織 ID（オプション） |
| httpClient | java.net.HttpURLConnection | 外部で管理された HttpURLConnection インスタンス。 |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


外部で管理されたインスタンスを使用して AI モデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | AI モデルが処理する指示またはメッセージ |

**Returns:**
java.lang.String - 指定された指示に応答して AI モデルが生成したメッセージ。

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


会話インスタンスを作成します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### close() {#close--}
```
public final void close()
```


このインスタンスが使用するリソースを解放します。