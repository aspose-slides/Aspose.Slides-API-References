---
title: ControlCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: ActiveX コントロールのコレクションです。
type: docs
url: /ja/com.aspose.slides/controlcollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX コントロールのコレクションです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のオブジェクト数を返します。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | コレクションに新しいコントロールを作成して追加します。 |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | コレクションから ActiveX コントロールを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定された位置に格納された ActiveX コントロールをコレクションから削除します。 |
| [clear()](#clear--) | コレクションからすべてのコントロールを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定された位置のコントロールを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション全体を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

コレクション内のオブジェクト数を返します。読み取り専用 int.

**戻り値:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

コレクションに新しいコントロールを作成して追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| controlType | int | 追加するコントロールのタイプ。 |
| x | float | シェイプのフレーム左側の X 座標。 |
| y | float | シェイプのフレーム上側の Y 座標。 |
| width | float | シェイプのフレームの幅。 |
| height | float | シェイプのフレームの高さ。 |

**戻り値:**
[IControl](../../com.aspose.slides/icontrol) - 作成されたコントロール。

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

コレクションから ActiveX コントロールを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 削除するコントロール。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定された位置に格納された ActiveX コントロールをコレクションから削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するコントロールのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのコントロールを削除します。

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

指定された位置のコントロールを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コントロールのインデックス。 |

**戻り値:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - コレクション全体の java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクション全体を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列 |
| index | int | 対象配列内のインデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean.

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object.

**戻り値:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject