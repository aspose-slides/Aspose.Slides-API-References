---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Java API リファレンス
description: SmartArt シェイプのコレクションを表します
type: docs
url: /ja/com.aspose.slides/smartartshapecollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

SmartArt シェイプのコレクションを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれている要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期 (スレッドセーフ) されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションから指定された配列へすべての要素をコピーします。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれている要素数を取得します。読み取り専用 int.

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [SmartArtShape](../../com.aspose.slides/smartartshape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | シェイプのインデックス |

**戻り値:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt シェイプ
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期 (スレッドセーフ) されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションから指定された配列へすべての要素をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - コレクション全体の java.util.Iterator。