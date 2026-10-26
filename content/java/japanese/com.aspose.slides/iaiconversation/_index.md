---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: 会話インスタンスを表します。
type: docs
url: /ja/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

会話インスタンスを表します。通常の AI 呼び出しとは異なり、会話は全体のコンテキストを保持します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | 全体のコンテキストを含む会話リクエストメッセージを送信し、応答を返します。 |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

全体のコンテキストを含む会話リクエストメッセージを送信し、応答を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instruction | java.lang.String | AI モデルによって処理される指示またはメッセージです。 |

**戻り値:**
java.lang.String - 与えられた指示に対し、会話コンテキスト内で AI モデルが生成したメッセージです。