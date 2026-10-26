---
title: CellCircularReferenceException
second_title: Aspose.Slides for Android の Java API リファレンス
description: 数式が直接または間接的に自分のセルを参照し、1 つ以上の循環参照が検出されたときにスローされる例外です。
type: docs
url: /ja/com.aspose.slides/cellcircularreferenceexception/
---
**継承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

数式が自分のセルを直接または間接的に参照し、1 つ以上の循環参照が検出されたときにスローされる例外です。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | 新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。 |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | 指定されたエラーメッセージで新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。 |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | 指定されたエラーメッセージとこの例外の原因となる内部例外への参照で新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。 |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | 指定されたエラーメッセージと循環セル参照で新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getReference()](#getReference--) | 循環セル参照を取得します。 |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

指定されたエラーメッセージで新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列です。 |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

指定されたエラーメッセージとこの例外の原因となる内部例外への参照で新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列です。 |
| innerException | java.lang.RuntimeException | 現在の例外の原因となる例外です。 |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

指定されたエラーメッセージと循環セル参照で新しい [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスのインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列です。 |
| reference | java.lang.String | 循環セル参照です。 |

### getReference() {#getReference--}
```
public final String getReference()
```

循環セル参照を取得します。

**戻り値:**
java.lang.String