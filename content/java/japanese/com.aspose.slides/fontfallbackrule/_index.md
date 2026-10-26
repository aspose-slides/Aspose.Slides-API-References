---
title: FontFallBackRule
second_title: Aspose.Slides for Java API リファレンス
description: フォント フォールバック ルールを表します
type: docs
url: /ja/com.aspose.slides/fontfallbackrule/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Represents font fallback rule
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | 新しいインスタンスを作成します。 |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | 新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | フォールバックフォントのリストに新しいフォントを追加します。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | フォールバックフォントのリストに新しいフォントを追加します。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 連続する Unicode 範囲の最初のインデックスを取得します。 |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | 連続する Unicode 範囲の最初のインデックスを取得します。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 連続する Unicode 範囲の最後のインデックスを取得します。 |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | 連続する Unicode 範囲の最後のインデックスを取得します。 |
| [getCount()](#getCount--) | 範囲に実際に定義されたフォントの数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのフォント名を取得します。 |
| [clear()](#clear--) | リストからすべてのフォントを削除します。 |
| [remove(String fontName)](#remove-java.lang.String-) | リストから特定のフォールバックフォントの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | リストの指定されたインデックスにあるフォールバックフォントを削除します。 |
| [toArray()](#toArray--) | このルールのすべてのフォールバックフォントを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | リストの指定された範囲からすべてのフォールバックフォントを含む配列を作成して返します。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | コレクション内の指定されたルールのインデックスを返します。 |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


新しいインスタンスを作成します。

--------------------

> ```
> // Create new instance of FantFallBackRule with one font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | long | Unicode 範囲の開始インデックス |
| endIndex | long | Unicode 範囲の終了インデックス |
| fontNames | java.lang.String | フォールバック用のフォント名または複数名（カンマ区切り） |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


新しいインスタンスを作成します。

--------------------

> ```
> // Create new instance of FantFallBackRule with two fonts
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | long | Unicode 範囲の開始インデックス |
| endIndex | long | Unicode 範囲の終了インデックス |
| fontNames | java.lang.String[] | フォールバック用のフォント名または複数名（カンマ区切り） |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


フォールバックフォントのリストに新しいフォントを追加します。

--------------------

> ```
> // FontFallBackRule の新しいインスタンスを作成します
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //2 番目のフォントをルールに追加します
>  newRule.addFallBackFonts("MS Gothic");
>  //3 番目と4 番目のフォントをルールに追加します
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォールバック用のフォント名または複数名（カンマ区切り） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


フォールバックフォントのリストに新しいフォントを追加します。

--------------------

> ```
> // FontFallBackRule の新しいインスタンスを作成します
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // ルールに別の3つのフォントを追加します
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontNames | java.lang.String[] | フォールバック用のフォント名または複数名（カンマ区切り） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


連続する Unicode 範囲の最初のインデックスを取得します。

**戻り値:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


連続する Unicode 範囲の最初のインデックスを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


連続する Unicode 範囲の最後のインデックスを取得します。

**戻り値:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


連続する Unicode 範囲の最後のインデックスを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


範囲に実際に定義されたフォントの数を取得します。読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


指定されたインデックスのフォント名を取得します。読み取り専用 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


リストからすべてのフォントを削除します。

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


リストから特定のフォールバックフォントの最初の出現を削除します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // リストから Tahoma を削除します。
>  newRule.remove("Tahoma");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | リストから削除するフォントの名前。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


リストの指定されたインデックスにあるフォールバックフォントを削除します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // リストから Tahoma を削除します。
>  newRule.remove(2);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するフォントのゼロベースインデックス。 |

### toArray() {#toArray--}
```
public final String[] toArray()
```


このルールのすべてのフォールバックフォントを含む配列を作成して返します。

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Get all font names as array.
>  String[] fontNames = newRule.toArray();
> ```

**戻り値:**
java.lang.String[] - 文字列の配列
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


リストの指定された範囲からすべてのフォールバックフォントを含む配列を作成して返します。

```
// フォントのリストを含むルールを作成します。
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // 最後の 2 つのフォント名を配列として取得します。
 String[] fontNames = newRule.toArray(2, 2);
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 追加する最初のフォントのインデックス。 |
| count | int | 追加するフォントの数。 |

**戻り値:**
java.lang.String[] - 文字列の配列
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


コレクション内の指定されたルールのインデックスを返します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma のインデックスを取得します。
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | 検索するフォントの名前。 |

**戻り値:**
int - フォントのインデックス、またはリストにフォントが見つからない場合は -1。