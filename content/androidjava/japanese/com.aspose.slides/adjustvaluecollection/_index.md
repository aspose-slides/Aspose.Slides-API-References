---
title: AdjustValueCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: シェイプの調整のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/adjustvaluecollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているインターフェイス:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

シェイプの調整のコレクションを表します。
## メソッド

| Method | Description |
| --- | --- |
| [size()](#size--) | 調整の数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスで調整を返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化 (スレッドセーフ) されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化のルートを返します。 |
| [iterator()](#iterator--) | コレクション全体の列挙子を返します。 |
### size() {#size--}
```
public final int size()
```

調整の数を返します。読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

インデックスで調整を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 調整のインデックス。 |

**戻り値:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

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

同期化のルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

コレクション全体の列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.IEnumerator