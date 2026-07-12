---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| instruction | java.lang.String | AI モデルで処理される指示またはメッセージ。 |

**戻り値:**
java.lang.String - 会話コンテキスト内で与えられた指示に対する AI モデルが生成したメッセージ。