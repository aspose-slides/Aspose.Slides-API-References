---
title: PptxException
second_title: Aspose.Slides for Android の Java API リファレンス
description: 標準的な内部例外タイプを表します。
type: docs
url: /ja/com.aspose.slides/pptxexception/
---
**継承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

標準的な内部例外タイプを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PptxException()](#PptxException--) | デフォルトコンストラクタ。 |
| [PptxException(String message)](#PptxException-java.lang.String-) | この例外にメッセージを追加できるコンストラクタ。 |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | メッセージと埋め込み例外を含む例外用のコンストラクタ。 |
### PptxException() {#PptxException--}
```
public PptxException()
```

デフォルトコンストラクタ。

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```

この例外にメッセージを追加できるコンストラクタ。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```

メッセージと埋め込み例外を含む例外用のコンストラクタ。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |