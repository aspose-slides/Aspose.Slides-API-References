---
title: OdpException
second_title: Aspose.Slides for Java API リファレンス
description: 標準的な内部例外タイプを表します。
type: docs
url: /ja/com.aspose.slides/odpexception/
---
**継承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

標準的な内部例外タイプを表します。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [OdpException()](#OdpException--) | デフォルトコンストラクター |
| [OdpException(String message)](#OdpException-java.lang.String-) | この例外にメッセージを追加できるコンストラクター。 |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | メッセージと埋め込み例外を含む例外用のコンストラクター。 |
### OdpException() {#OdpException--}
```
public OdpException()
```


デフォルトコンストラクター

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


この例外にメッセージを追加できるコンストラクター。

**パラメーター：**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


メッセージと埋め込み例外を含む例外用のコンストラクター。

**パラメーター：**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | 元の例外 |