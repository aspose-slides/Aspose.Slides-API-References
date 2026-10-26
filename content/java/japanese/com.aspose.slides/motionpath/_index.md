---
title: MotionPath
second_title: Aspose.Slides for Java API リファレンス
description: モーション パスを表します。
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

モーション パスを表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | パスに新しいコマンドを追加します |
| [getCount()](#getCount--) | コレクション内のパス数を返します。 |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | パスに新しいコマンドを挿入します |
| [clear()](#clear--) | コレクションからすべてのコマンドを削除します。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | コレクションから指定されたコマンドを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのコマンドを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのコマンドを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


パスに新しいコマンドを追加します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | ポイントの配列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相対座標のブール値 |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


コレクション内のパス数を返します。読み取り専用の int。

**戻り値:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


パスに新しいコマンドを挿入します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入すべき項目のゼロベースのインデックス。 |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | ポイントの配列 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 削除するモーション パス。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


指定されたインデックスのコマンドを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきコマンドのインデックス。 |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


指定されたインデックスのコマンドを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) オブジェクト
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - コレクションを反復処理できる IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


コレクション全体の java.util.Iterator を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - コレクション全体の java.util.Iterator