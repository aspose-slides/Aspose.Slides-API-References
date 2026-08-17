---
title: IMotionPath
second_title: Aspose.Slides for Java API リファレンス
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
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | パスに新しいコマンドを追加します |
| [getCount()](#getCount--) | コレクション内のパスの数を返します。 |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | パスに新しいコマンドを挿入します |
| [clear()](#clear--) | コレクションからすべてのコマンドを削除します。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | コレクションから指定されたコマンドを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのコマンドを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのコマンドを返します。 |

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

パスに新しいコマンドを追加します

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | アニメーションモーション効果の動作に対するコマンドのタイプ [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | ポイント配列 java.awt.geom.Point2D.Float[] |
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

### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

パスに新しいコマンドを挿入します

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コマンド挿入用インデックス int |
| type | int | アニメーションモーション効果の動作に対するコマンドのタイプ [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | ポイント配列 java.awt.geom.Point2D.Float[] |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 削除するモーションパス [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスのコマンドを削除します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コマンドを削除するインデックス int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

指定されたインデックスのコマンドを返します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 指定されたインデックスのコマンド [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)