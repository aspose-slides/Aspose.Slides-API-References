---
title: CellInvalidReferenceException
second_title: Aspose.Slides for Android の Java API リファレンス
description: 無効なセル参照が検出されたときにスローされる例外です。
type: docs
url: /ja/com.aspose.slides/cellinvalidreferenceexception/
---
**継承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

無効なセル参照が検出されたときにスローされる例外です。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) クラスの新しいインスタンスを初期化します。 |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | 指定されたエラーメッセージを使用して、[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) クラスの新しいインスタンスを初期化します。 |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | 指定されたエラーメッセージと、この例外の原因となる内部例外への参照を使用して、[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) クラスの新しいインスタンスを初期化します。 |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | 指定されたエラーメッセージと無効なセル参照を使用して、[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getReference()](#getReference--) | 無効なセル参照を取得します。 |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) クラスの新しいインスタンスを初期化します。

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) クラスの新しいインスタンスを指定されたエラーメッセージで初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列。 |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

指定されたエラーメッセージと、この例外の原因となる内部例外への参照を使用して、[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) クラスの新しいインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列。 |
| innerException | java.lang.RuntimeException | 現在の例外の原因となる例外です。 |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

指定されたエラーメッセージと無効なセル参照を使用して、[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) クラスの新しいインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列。 |
| reference | java.lang.String | 無効なセル参照です。 |

### getReference() {#getReference--}
```
public final String getReference()
```

無効なセル参照を取得します。

**戻り値:**
java.lang.String