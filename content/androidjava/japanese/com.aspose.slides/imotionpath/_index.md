---
title: IMotionPath
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: モーションパスを表します。
type: docs
url: /ja/com.aspose.slides/imotionpath/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

モーションパスを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | パスに新しいコマンドを追加します |
| [getCount()](#getCount--) | コレクション内のパスの数を返します |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | パスに新しいコマンドを挿入します |
| [clear()](#clear--) | コレクションからすべてのコマンドを削除します |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | コレクションから指定されたコマンドを削除します |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのコマンドを削除します |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのコマンドを返します |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

パスに新しいコマンドを追加します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | アニメーションモーション効果動作のコマンドのタイプ [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | ポイント配列 android.graphics.PointF[] |
| ptsType | int | アニメーションモーションパスのポイントのタイプ [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相対座標を使用するかどうかを示す boolean |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - パスのコマンド [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクション内のパスの数を返します。読み取り専用 int。

**戻り値:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

パスに新しいコマンドを挿入します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コマンド挿入のインデックス int |
| type | int | アニメーションモーション効果動作のコマンドのタイプ [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | ポイント配列 android.graphics.PointF[] |
| ptsType | int | アニメーションモーションパスのポイントのタイプ [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相対座標を使用するかどうかを示す boolean |
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのコマンドを削除します。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

コレクションから指定されたコマンドを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 削除するモーションパス [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスのコマンドを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コマンド削除のインデックス int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

指定されたインデックスのコマンドを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 指定されたインデックスのコマンド [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)