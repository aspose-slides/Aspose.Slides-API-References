---
title: DrawingGuidesCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 調整可能な描画ガイドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/drawingguidescollection/
---
**Inheritance:**  
継承:

java.lang.Object

**All Implemented Interfaces:**  
実装されているすべてのインターフェイス:

[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

調整可能な描画ガイドのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで描画ガイドを返します。 |
| [add(byte orientation, float position)](#add-byte-float-) | コレクションの末尾に描画ガイドを追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの描画ガイドを削除します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [getCount()](#getCount--) | コレクション内の要素数を返します。 |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | コレクションのすべての要素を指定された配列にコピーします。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

インデックスで描画ガイドを返します。読み取り専用 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

コレクションの末尾に描画ガイドを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientation | byte | 描画ガイドの向き。 |
| position | float | 描画ガイドの位置（ポイント単位）。 |

**戻り値:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスの描画ガイドを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき描画ガイドのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - コレクション全体の java.util.Iterator。

### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内の要素数を返します。読み取り専用 int。

**戻り値:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |