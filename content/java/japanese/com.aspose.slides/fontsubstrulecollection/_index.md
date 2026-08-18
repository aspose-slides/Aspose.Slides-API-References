---
title: FontSubstRuleCollection
second_title: Aspose.Slides for Java API リファレンス
description: フォント置換のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/fontsubstrulecollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

フォント置換のコレクションを表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素の数を取得します。 |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | 新しいフォント置換ルールをコレクションに追加します。 |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


コレクションに実際に含まれる要素の数を取得します。読み取り専用 int。

**戻り値:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


新しいフォント置換ルールをコレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | コレクションから削除するフォント置換ルール。 |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | ターゲット配列。 |
| index | int | ターゲット配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期されているか（スレッドセーフか）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object