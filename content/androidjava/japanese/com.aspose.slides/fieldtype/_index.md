---
title: FieldType
second_title: Java API リファレンス（Android 用）Aspose.Slides
description: フィールドのタイプを表します。
type: docs
url: /ja/com.aspose.slides/fieldtype/
---
**継承:**  
java.lang.Object

**すべての実装済みインターフェイス:**  
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)  
```
public final class FieldType implements IFieldType
```

フィールドのタイプを表します。この値は、フィールド部分が更新される際に設定されるテキストを決定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | FieldType クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInternalString()](#getInternalString--) | この FieldType オブジェクトの内部名を返します。 |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | この FieldType オブジェクトの内部名を返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このフィールドが別のフィールドと等しいかどうかをチェックします。 |
| [hashCode()](#hashCode--) | このオブジェクトのハッシュコードを返します。 |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 2 つの FieldType オブジェクトが等しいかどうかをチェックします。 |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 2 つの FieldType オブジェクトが等しくないかどうかをチェックします。 |
| [getSlideNumber()](#getSlideNumber--) | 現在のスライド番号。 |
| [getFooter()](#getFooter--) | スライドのフッター。 |
| [getHeader()](#getHeader--) | スライドのヘッダー。 |
| [getDateTime()](#getDateTime--) | レンダリングアプリケーションのデフォルトの日付時刻形式での現在の日付と時刻。 |
| [getDateTime1()](#getDateTime1--) | 最初の事前定義形式（英語では MM/DD/YYYY）での現在の日付と時刻。 |
| [getDateTime2()](#getDateTime2--) | 2 番目の事前定義形式（英語では Day, Month DD, YYYY）での現在の日付と時刻。 |
| [getDateTime3()](#getDateTime3--) | 3 番目の事前定義形式（英語では DD Month YYYY）での現在の日付と時刻。 |
| [getDateTime4()](#getDateTime4--) | 4 番目の事前定義形式（英語では Month DD, YYYY）での現在の日付と時刻。 |
| [getDateTime5()](#getDateTime5--) | 5 番目の事前定義形式（英語では DD-Mon-YY）での現在の日付と時刻。 |
| [getDateTime6()](#getDateTime6--) | 6 番目の事前定義形式（英語では Month YY）での現在の日付と時刻。 |
| [getDateTime7()](#getDateTime7--) | 7 番目の事前定義形式（英語では Mon-YY）での現在の日付と時刻。 |
| [getDateTime8()](#getDateTime8--) | 8 番目の事前定義形式（英語では MM/DD/YYYY hh:mm AM/PM）での現在の日付と時刻。 |
| [getDateTime9()](#getDateTime9--) | 9 番目の事前定義形式（英語では MM/DD/YYYY hh:mm:ss AM/PM）での現在の日付と時刻。 |
| [getDateTime10()](#getDateTime10--) | 10 番目の事前定義形式（英語では hh:mm）での現在の日付と時刻。 |
| [getDateTime11()](#getDateTime11--) | 11 番目の事前定義形式（英語では hh:mm:ss）での現在の日付と時刻。 |
| [getDateTime12()](#getDateTime12--) | 12 番目の事前定義形式（英語では hh:mm AM/PM）での現在の日付と時刻。 |
| [getDateTime13()](#getDateTime13--) | 13 番目の事前定義形式（英語では hh:mm:ss AM/PM）での現在の日付と時刻。 |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

FieldType クラスの新しいインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

この FieldType オブジェクトの内部名を返します。読み書き可能な String。

**戻り値:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

この FieldType オブジェクトの内部名を返します。読み書き可能な String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

このフィールドが別のフィールドと等しいかどうかをチェックします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象のフィールド。 |

**戻り値:**
boolean - フィールドが等しい場合は true。

### hashCode() {#hashCode--}
```
public int hashCode()
```

このオブジェクトのハッシュコードを返します。

**戻り値:**
int - ハッシュコード int。

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

2 つの FieldType オブジェクトが等しいかどうかをチェックします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 比較対象の最初の FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 比較対象の2 番目の FieldType。 |

**戻り値:**
boolean - FieldType オブジェクトが等しい場合は true。

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

2 つの FieldType オブジェクトが等しくないかどうかをチェックします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 比較対象の最初の FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 比較対象の2 番目の FieldType。 |

**戻り値:**
boolean - FieldType オブジェクトが等しくない場合は true。

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

現在のスライド番号。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

スライドのフッター。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

スライドのヘッダー。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

レンダリングアプリケーションのデフォルトの日付時刻形式での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

最初の事前定義形式（英語では MM/DD/YYYY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

2 番目の事前定義形式（英語では Day, Month DD, YYYY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

3 番目の事前定義形式（英語では DD Month YYYY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldName getDateTime4()
```

4 番目の事前定義形式（英語では Month DD, YYYY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

5 番目の事前定義形式（英語では DD-Mon-YY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

6 番目の事前定義形式（英語では Month YY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

7 番目の事前定義形式（英語では Mon-YY）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

8 番目の事前定義形式（英語では MM/DD/YYYY hh:mm AM/PM）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

9 番目の事前定義形式（英語では MM/DD/YYYY hh:mm:ss AM/PM）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

10 番目の事前定義形式（英語では hh:mm）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

11 番目の事前定義形式（英語では hh:mm:ss）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

12 番目の事前定義形式（英語では hh:mm AM/PM）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

13 番目の事前定義形式（英語では hh:mm:ss AM/PM）での現在の日付と時刻。読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)