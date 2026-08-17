---
title: FieldType
second_title: Aspose.Slides for Java API リファレンス
description: フィールドの型を表します。
type: docs
url: /ja/com.aspose.slides/fieldtype/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

フィールドの型を表します。この値は、フィールドが更新される際にフィールド部分に設定されるテキストを決定します。

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
| [getDateTime()](#getDateTime--) | レンダリング アプリケーションのデフォルト日時形式で現在の日付と時刻を返します。 |
| [getDateTime1()](#getDateTime1--) | 英語用の最初の事前定義フォーマット (MM/DD/YYYY) で現在の日付と時刻を返します。 |
| [getDateTime2()](#getDateTime2--) | 英語用の二番目の事前定義フォーマット (Day, Month DD, YYYY) で現在の日付と時刻を返します。 |
| [getDateTime3()](#getDateTime3--) | 英語用の三番目の事前定義フォーマット (DD Month YYYY) で現在の日付と時刻を返します。 |
| [getDateTime4()](#getDateTime4--) | 英語用の四番目の事前定義フォーマット (Month DD, YYYY) で現在の日付と時刻を返します。 |
| [getDateTime5()](#getDateTime5--) | 英語用の五番目の事前定義フォーマット (DD-Mon-YY) で現在の日付と時刻を返します。 |
| [getDateTime6()](#getDateTime6--) | 英語用の六番目の事前定義フォーマット (Month YY) で現在の日付と時刻を返します。 |
| [getDateTime7()](#getDateTime7--) | 英語用の七番目の事前定義フォーマット (Mon-YY) で現在の日付と時刻を返します。 |
| [getDateTime8()](#getDateTime8--) | 英語用の八番目の事前定義フォーマット (MM/DD/YYYY hh:mm AM/PM) で現在の日付と時刻を返します。 |
| [getDateTime9()](#getDateTime9--) | 英語用の九番目の事前定義フォーマット (MM/DD/YYYY hh:mm:ss AM/PM) で現在の日付と時刻を返します。 |
| [getDateTime10()](#getDateTime10--) | 英語用の十番目の事前定義フォーマット (hh:mm) で現在の日付と時刻を返します。 |
| [getDateTime11()](#getDateTime11--) | 英語用の十一番目の事前定義フォーマット (hh:mm:ss) で現在の日付と時刻を返します。 |
| [getDateTime12()](#getDateTime12--) | 英語用の十二番目の事前定義フォーマット (hh:mm AM/PM) で現在の日付と時刻を返します。 |
| [getDateTime13()](#getDateTime13--) | 英語用の十三番目の事前定義フォーマット (hh:mm:ss AM/PM) で現在の日付と時刻を返します。 |

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

この FieldType オブジェクトの内部名を返します。 読み取り/書き込み String。

**戻り値:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

この FieldType オブジェクトの内部名を返します。 読み取り/書き込み String。

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
int - ハッシュコード。

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

2 つの FieldType オブジェクトが等しいかどうかをチェックします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 比較する最初の FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 比較する二番目の FieldType。 |

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
| a | [FieldType](../../com.aspose.slides/fieldtype) | 比較する最初の FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 比較する二番目の FieldType。 |

**戻り値:**
boolean - FieldType オブジェクトが等しくない場合は true。

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

現在のスライド番号。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

スライドのフッター。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

スライドのヘッダー。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

レンダリング アプリケーションのデフォルト日時形式で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

英語用の最初の事前定義フォーマット (MM/DD/YYYY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

英語用の二番目の事前定義フォーマット (Day, Month DD, YYYY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

英語用の三番目の事前定義フォーマット (DD Month YYYY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

英語用の四番目の事前定義フォーマット (Month DD, YYYY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

英語用の五番目の事前定義フォーマット (DD-Mon-YY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

英語用の六番目の事前定義フォーマット (Month YY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

英語用の七番目の事前定義フォーマット (Mon-YY) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

英語用の八番目の事前定義フォーマット (MM/DD/YYYY hh:mm AM/PM) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

英語用の九番目の事前定義フォーマット (MM/DD/YYYY hh:mm:ss AM/PM) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

英語用の十番目の事前定義フォーマット (hh:mm) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

英語用の十一番目の事前定義フォーマット (hh:mm:ss) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

英語用の十二番目の事前定義フォーマット (hh:mm AM/PM) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldRange getDateTime13()
```

英語用の十三番目の事前定義フォーマット (hh:mm:ss AM/PM) で現在の日付と時刻を返します。 読み取り専用 [FieldType](../../com.aspose.slides/fieldtype)。

**戻り値:**
[FieldType](../../com.aspose.slides/fieldtype)