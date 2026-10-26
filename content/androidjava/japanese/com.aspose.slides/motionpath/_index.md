---
title: MotionPath
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: モーションパスを表します。
type: docs
url: /ja/com.aspose.slides/motionpath/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)  
```
public class MotionPath implements IMotionPath
```

モーションパスを表します。

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | パスに新しいコマンドを追加します |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | パスに新しいコマンドを挿入します |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |

### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

パスに新しいコマンドを追加します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | ポイントの配列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相対座標のブール値 |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内のパスの数を返します。読み取り専用 int。

**戻り値:**
int

### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

パスに新しいコマンドを挿入します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | アイテムを挿入するゼロベースのインデックス。 |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | ポイントの配列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相対座標のブール値 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのコマンドを削除します。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

コレクションから指定されたコマンドを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 削除するモーションパス。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのコマンドを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきコマンドのインデックス。 |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

指定されたインデックスのコマンドを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - The [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - コレクションを反復処理するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - コレクション全体の java.util.Iterator。