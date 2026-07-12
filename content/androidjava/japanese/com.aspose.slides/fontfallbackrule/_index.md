---
title: FontFallBackRule
second_title: Aspose.Slides for Android の Java API リファレンス
description: フォントのフォールバック規則を表します
type: docs
url: /ja/com.aspose.slides/fontfallbackrule/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェース:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

フォントフォールバック規則を表します
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | 新しいインスタンスを作成します。 |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | 新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | FallBack フォントのリストに新しいフォントを追加します。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | FallBack フォントのリストに新しいフォントを追加します。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 連続 Unicode 範囲の最初のインデックスを取得します。 |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | 連続 Unicode 範囲の最初のインデックスを取得します。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 連続 Unicode 範囲の最後のインデックスを取得します。 |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | 連続 Unicode 範囲の最後のインデックスを取得します。 |
| [getCount()](#getCount--) | 範囲に実際に定義されたフォントの数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのフォント名を取得します。 |
| [clear()](#clear--) | リストからすべてのフォントを削除します。 |
| [remove(String fontName)](#remove-java.lang.String-) | リストから特定の FallBack フォントの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | リストの指定インデックスにある FallBack フォントを削除します。 |
| [toArray()](#toArray--) | この規則のすべての FallBack フォントを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | リストの指定範囲からすべての FallBack フォントを含む配列を作成して返します。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | コレクション内の指定された規則のインデックスを返します。 |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

新しいインスタンスを作成します。

--------------------

> ```
> // 1 つのフォントで FantFallBackRule の新しいインスタンスを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // 複数のフォントで FantFallBackRule の新しいインスタンスを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | long | Unicode 範囲の開始インデックス |
| endIndex | long | Unicode 範囲の終了インデックス |
| fontNames | java.lang.String | FallBack 用のフォント名または複数名（カンマで区切り） |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

新しいインスタンスを作成します。

--------------------

> ```
> // 2 つのフォントで FantFallBackRule の新しいインスタンスを作成します
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // 複数のフォントで FantFallBackRule の新しいインスタンスを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | long | Unicode 範囲の開始インデックス |
| endIndex | long | Unicode 範囲の終了インデックス |
| fontNames | java.lang.String[] | FallBack 用のフォント名または複数名（カンマで区切り） |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

FallBack フォントのリストに新しいフォントを追加します。

--------------------

> ```
> // FontFallBackRule の新しいインスタンスを作成します
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //ルールに 2 番目のフォントを追加します
>  newRule.addFallBackFonts("MS Gothic");
>  //ルールに 3 番目と 4 番目のフォントを追加します
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | FallBack 用のフォント名または複数名（カンマで区切り） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

FallBack フォントのリストに新しいフォントを追加します。

--------------------

> ```
> //FontFallBackRule の新しいインスタンスを作成します
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //ルールにさらに 3 つのフォントを追加します 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack 用のフォント名または複数名（カンマで区切り） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

連続 Unicode 範囲の最初のインデックスを取得します。

**戻り値:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

連続 Unicode 範囲の最初のインデックスを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

連続 Unicode 範囲の最後のインデックスを取得します。

**戻り値:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

連続 Unicode 範囲の最後のインデックスを取得します。

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

リストから特定の FallBack フォントの最初の出現を削除します。

--------------------

> ```
> // フォントのリストを含む規則を作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // リストから Tahoma を削除します。
>  newRule.remove("Tahoma");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | リストから削除するフォントの名前 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

リストの指定インデックスにある FallBack フォントを削除します。

--------------------

> ```
> // フォントのリストを含む規則を作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //リストから Tahoma を削除します。
>  newRule.remove(2);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するフォントのゼロベースインデックス |

### toArray() {#toArray--}
```
public final String[] toArray()
```

この規則のすべての FallBack フォントを含む配列を作成して返します。

--------------------

> ```
> // フォントのリストを含む規則を作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // すべてのフォント名を配列として取得します。
>  String[] fontNames = newRule.toArray();
> ```

**戻り値:**
java.lang.String[] - 文字列の配列
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

リストの指定範囲からすべての FallBack フォントを含む配列を作成して返します。

```
// フォントのリストを含む規則を作成します。
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // 最後の 2 つのフォント名を配列として取得します。
 String[] fontNames = newRule.toArray(2, 2);
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 追加する最初のフォントのインデックス |
| count | int | 追加するフォントの数 |

**戻り値:**
java.lang.String[] - 文字列の配列
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

コレクション内の指定された規則のインデックスを返します。

--------------------

> ```
> // フォントのリストを含む規則を作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma のインデックスを取得します。
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | 検索するフォント名 |

**戻り値:**
int - フォントのインデックス、フォントがリストに見つからない場合は -1。