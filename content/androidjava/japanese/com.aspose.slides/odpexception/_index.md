---
title: OdpException
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: 標準的な内部例外型を表します。
type: docs
url: /ja/com.aspose.slides/odpexception/
---
**継承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

標準的な内部例外型を表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OdpException()](#OdpException--) | デフォルトコンストラクタ |
| [OdpException(String message)](#OdpException-java.lang.String-) | コンストラクタは、この例外にメッセージを追加できるようにします。 |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | メッセージと埋め込み例外を含む例外のコンストラクタ。 |
### OdpException() {#OdpException--}
```
public OdpException()
```


デフォルトコンストラクタ

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


コンストラクタは、この例外にメッセージを追加できるようにします。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


メッセージと埋め込み例外を含む例外のコンストラクタ。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |