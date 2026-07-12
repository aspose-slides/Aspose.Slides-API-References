---
title: OOXMLException
second_title: Aspose.Slides for Android の Java API リファレンス
description: Office Open XML ファイル形式に関連する標準的な内部例外タイプを表します。
type: docs
url: /ja/com.aspose.slides/ooxmlexception/
---
**継承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Office Open XML ファイル形式に関連する標準的な内部例外タイプを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | デフォルトコンストラクタ。 |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | この例外にメッセージを追加できるコンストラクタ。 |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | メッセージと埋め込み例外を含む例外用のコンストラクタ。 |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```

デフォルトコンストラクタ。

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```

この例外にメッセージを追加できるコンストラクタ。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```

メッセージと埋め込み例外を含む例外用のコンストラクタ。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | 元の例外 |