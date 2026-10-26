---
title: CellCircularReferenceException
second_title: Aspose.Slides for Java API リファレンス
description: 数式が直接または間接的に自分のセルを参照する場合に、1つ以上の循環参照が検出されたときにスローされる例外です。
type: docs
url: /ja/com.aspose.slides/cellcircularreferenceexception/
---
**継承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

数式が自分のセルを直接または間接的に参照している場合に、1つ以上の循環参照が検出されたときにスローされる例外です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。 |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | 指定されたエラーメッセージを使用して、[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。 |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | 指定されたエラーメッセージと、この例外の原因となる内部例外への参照を使用して、[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。 |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | 指定されたエラーメッセージと循環セル参照を使用して、[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getReference()](#getReference--) | 循環セル参照を取得します。 |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを、指定されたエラーメッセージで初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列。 |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを、指定されたエラーメッセージと、この例外の原因となる内部例外への参照で初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列。 |
| innerException | java.lang.RuntimeException | 現在の例外の原因となっている例外。 |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを、指定されたエラーメッセージと循環セル参照で初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列。 |
| reference | java.lang.String | 循環セル参照。 |

### getReference() {#getReference--}
```
public final String getReference()
```

循環セル参照を取得します。

**戻り値:**
java.lang.String