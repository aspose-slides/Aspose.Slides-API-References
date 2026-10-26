---
title: TextAnimationCollection
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: テキストアニメーションのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/textanimationcollection/
---
**継承:**  
java.lang.Object  

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)  
```
public class TextAnimationCollection implements ITextAnimationCollection
```

テキストアニメーションのコレクションを表します。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内の要素数を返します。 |
| [add()](#add--) | コレクションに新しいテキストアニメーションを追加します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスで要素を返します。 |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | すべての要素を返します |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション内のすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化 (スレッドセーフ) されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |

### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

コレクション内の要素数を返します。読み取り専用 int。

**戻り値:**  
int

### add() {#add--}
```
public final TextAnimation add()
```

コレクションに新しいテキストアニメーションを追加します。

**戻り値:**  
[TextAnimation](../../com.aspose.slides/textanimation) - 追加された [TextAnimation](../../com.aspose.slides/textanimation)

### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

インデックスで要素を返します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

すべての要素を返します

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) を削除する。 |

**戻り値:**  
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) の配列

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - コレクションを反復処理できる IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - コレクション全体の java.util.Iterator

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクション内のすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 埋める配列。 |
| index | int | 対象配列の開始位置。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化 (スレッドセーフ) されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**戻り値:**  
java.lang.Object