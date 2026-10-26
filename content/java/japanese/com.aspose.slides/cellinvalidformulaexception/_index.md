---
title: CellInvalidFormulaException
second_title: Aspose.Slides for Java API リファレンス
description: 計算された数式が正しくない、または解析できなかった場合にスローされる例外です。
type: docs
url: /ja/com.aspose.slides/cellinvalidformulaexception/
---
**継承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

計算された数式が正しくない、または解析できなかった場合にスローされる例外です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを初期化します。 |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを指定されたエラーメッセージで初期化します。 |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを、指定されたエラーメッセージと、この例外の原因となる内部例外への参照で初期化します。 |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを、指定されたエラーメッセージと、無効な数式を含むセル参照で初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getReference()](#getReference--) | 無効な数式を含むセル参照を取得します。 |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを初期化します。

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを指定されたエラーメッセージで初期化します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列です。 |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを、指定されたエラーメッセージと、この例外の原因となる内部例外への参照で初期化します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列です。 |
| innerException | java.lang.RuntimeException | 現在の例外の原因となる例外です。 |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) クラスの新しいインスタンスを、指定されたエラーメッセージと、無効な数式を含むセル参照で初期化します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | java.lang.String | エラーを説明する文字列です。 |
| reference | java.lang.String | 内部例外への参照を説明する文字列です。 |

### getReference() {#getReference--}
```
public final String getReference()
```

無効な数式を含むセル参照を取得します。

**戻り値:**
java.lang.String