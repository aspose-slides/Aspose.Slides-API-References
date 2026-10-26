---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /ja/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web クライアント インターフェイス。このインターフェイスは、さまざまな AI 言語モデルを置き換えることを可能にします。このインターフェイスを実装するクラスは、SlidesAIAgent と共に使用することが想定されています。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 提供された HttpConnection インスタンスを使用して AI モデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。 |
| [createConversation()](#createConversation--) | 会話インスタンスを作成します。 |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

提供された HttpConnection インスタンスを使用して AI モデルにチャット指示を送信し、指定された指示に対する応答メッセージを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instruction | java.lang.String | AI モデルによって処理される指示またはメッセージ。 |

**戻り値:**
java.lang.String - 指定された指示に対する応答として AI モデルが生成したメッセージ。

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

会話インスタンスを作成します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。

**戻り値:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) のインスタンス。