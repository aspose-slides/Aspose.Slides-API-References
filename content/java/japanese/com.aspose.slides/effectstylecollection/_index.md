---
title: EffectStyleCollection
second_title: Aspose.Slides for Java API リファレンス
description: エフェクト スタイルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/effectstylecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

エフェクト スタイルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定された位置の要素を返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [size()](#size--) | コレクション内の要素数を返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション内のすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているかどうかを示す値を返します（スレッドセーフ）。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

指定された位置の要素を返します。読み取り専用 [EffectStyle](../../com.aspose.slides/effectstyle)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要素の位置。 |

**Returns:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - 指定された位置の要素。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

コレクションを反復処理する列挙子を返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

コレクション全体の java イテレータを返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - コレクション全体の java.util.Iterator。
### size() {#size--}
```
public final int size()
```

コレクション内の要素数を返します。読み取り専用 int, 読み取り専用 int。

**Returns:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクション内のすべての要素を指定された配列にコピーします。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているかどうかを示す値を返します（スレッドセーフ）。読み取り専用 boolean。

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**Returns:**
java.lang.Object