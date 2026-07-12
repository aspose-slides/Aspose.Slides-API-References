---
title: EffectStyleCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: エフェクトスタイルのコレクションを表します。
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

エフェクトスタイルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定された位置の要素を返します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [size()](#size--) | コレクション内の要素数を返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列へコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

指定された位置の要素を返します。 読み取り専用 [EffectStyle](../../com.aspose.slides/effectstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素の位置。 |

**戻り値:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - 指定された位置の要素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - コレクションを反復するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - コレクション全体の java.util.Iterator。

### size() {#size--}
```
public final int size()
```

コレクション内の要素数を返します。 読み取り専用 int, 読み取り専用 int。

**戻り値:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列へコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 読み取り専用 boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。 読み取り専用 Object。

**戻り値:**
java.lang.Object