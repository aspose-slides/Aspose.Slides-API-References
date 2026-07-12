---  
title: IFontFallBackRule  
second_title: Aspose.Slides for Android via Java API Reference  
description: Represents font fallback rule  
type: docs  
url: /ja/com.aspose.slides/ifontfallbackrule/  
---```
public interface IFontFallBackRule
```

フォントフォールバックルールを表します  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 新しいフォントをフォールバックフォントのリストに追加します。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 新しいフォントをフォールバックフォントのリストに追加します。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 連続する Unicode 範囲の開始インデックスを取得します。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 連続する Unicode 範囲の終了インデックスを取得します。 |
| [getCount()](#getCount--) | 範囲に実際に定義されているフォントの数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのフォント名を取得します。 |
| [clear()](#clear--) | リストからすべてのフォントを削除します。 |
| [remove(String fontName)](#remove-java.lang.String-) | リストから特定のフォールバックフォントの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | リストの指定インデックスにあるフォールバックフォントを削除します。 |
| [toArray()](#toArray--) | このルールのすべてのフォールバックフォントを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | リスト内の指定範囲からすべてのフォールバックフォントを含む配列を作成して返します。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | コレクション内の指定されたルールのインデックスを返します。 |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

新しいフォントをフォールバックフォントのリストに追加します。

--------------------

> ```
> //新しい FantFallBackRule のインスタンスを作成
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //ルールに 2 番目のフォントを追加
>  newRule.addFallBackFonts("MS Gothic");
>  //ルールに 3 番目と 4 番目のフォントを追加
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォールバック用のフォント名またはカンマで区切られた複数の名前 |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

新しいフォントをフォールバックフォントのリストに追加します。

--------------------

> ```
> //FontFallBackRule の新しいインスタンスを作成
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //ルールに別の 3 つのフォントを追加 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontNames | java.lang.String[] | フォールバック用のフォント名またはカンマで区切られた複数の名前 |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

連続する Unicode 範囲の開始インデックスを取得します。

**戻り値:**  
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

連続する Unicode 範囲の終了インデックスを取得します。

**戻り値:**  
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

範囲に実際に定義されているフォントの数を取得します。

**戻り値:**  
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

指定されたインデックスのフォント名を取得します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**  
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

リストからすべてのフォントを削除します。

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

リストから特定のフォールバックフォントの最初の出現を削除します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // リストから Tahoma を削除
>  newRule.remove("Tahoma");
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | リストから削除するフォントの名前。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

リストの指定インデックスにあるフォールバックフォントを削除します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //リストから Tahoma を削除
>  newRule.remove(2);
```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するフォントのゼロベースインデックス。 |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

このルールのすべてのフォールバックフォントを含む配列を作成して返します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //すべてのフォント名を配列として取得
>  String[] fontNames = newRule.toArray();
> ```

**戻り値:**  
java.lang.String[] - 文字列の配列
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

リスト内の指定範囲からすべてのフォールバックフォントを含む配列を作成して返します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //最後の 2 つのフォント名を配列として取得
>  String[] fontNames = newRule.toArray(2,2);
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 追加する最初のフォントのインデックス。 |
| count | int | 追加するフォントの数。 |

**戻り値:**  
java.lang.String[] - 文字列の配列
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

コレクション内の指定されたルールのインデックスを返します。

--------------------

> ```
> // フォントのリストを含むルールを作成します。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma のインデックスを取得
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | 検索するフォント名。 |

**戻り値:**  
int - フォントのインデックス、フォントがリストに見つからない場合は -1。