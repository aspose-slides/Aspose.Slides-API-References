---
title: ColorOperationCollection
second_title: Java 用 Aspose.Slides API リファレンス
description: カラー変換操作のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/coloroperationcollection/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

カラー変換操作のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内の操作数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの操作を取得または設定します。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 指定されたインデックスの操作を取得または設定します。 |
| [add(int operation, float parameter)](#add-int-float-) | 新しい操作をコレクションの末尾に追加します。 |
| [add(int operation)](#add-int-) | 新しい操作をコレクションの末尾に追加します。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 新しい操作をコレクションに挿入します。 |
| [insert(int position, int operation)](#insert-int-int-) | 新しい操作をコレクションに挿入します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションからカラー操作を削除します。 |
| [clear()](#clear--) | すべてのカラー操作を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列へコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期オブジェクトのルートを返します。 |
| [deepClone()](#deepClone--) | ColorOperationCollection コレクションのコピーを作成します。 |
| [cloneT()](#cloneT--) | 現在のオブジェクトをクローンします |

### size() {#size--}
```
public final int size()
```

コレクション内の操作数を返します。読み取り専用 int。

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

指定されたインデックスの操作を取得または設定します。読み書き可能 [ColorOperation](../../com.aspose.slides/coloroperation)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

指定されたインデックスの操作を取得または設定します。読み書き可能 [ColorOperation](../../com.aspose.slides/coloroperation)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

新しい操作をコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| operation | int | 操作の種類。 |
| parameter | float | 操作のパラメーター。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 追加された操作。

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

新しい操作をコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| operation | int | 操作の種類。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 追加された操作。

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

新しい操作をコレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | int | 操作が挿入されるインデックス。 |
| operation | int | 操作の種類。 |
| parameter | float | 操作のパラメーター。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 挿入された操作。

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

新しい操作をコレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | int | 操作が挿入されるインデックス。 |
| operation | int | 操作の種類。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 挿入された操作。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションからカラー操作を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するカラー操作のインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

すべてのカラー操作を削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - コレクションを反復処理するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - コレクション全体の java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列へコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ColorOperationCollection コレクションのコピーを作成します。

**戻り値:**
java.lang.Object - 新しい [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) コレクション。

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

現在のオブジェクトをクローンします

**戻り値:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - クローン