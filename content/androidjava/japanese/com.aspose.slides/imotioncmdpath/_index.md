---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represent one command of a path.
type: docs
url: /ja/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

パスのコマンドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPoints()](#getPoints--) | コマンドのポイントを指定します。 |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | コマンドのポイントを指定します。 |
| [getCommandType()](#getCommandType--) | コマンドのタイプを指定します。 |
| [setCommandType(int value)](#setCommandType-int-) | コマンドのタイプを指定します。 |
| [isRelative()](#isRelative--) | コマンド座標が相対的かどうかを判断します。 |
| [setRelative(boolean value)](#setRelative-boolean-) | コマンド座標が相対的かどうかを判断します。 |
| [getPointsType()](#getPointsType--) | コマンドポイントのタイプを指定します 読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
| [setPointsType(int value)](#setPointsType-int-) | コマンドポイントのタイプを指定します 読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

コマンドのポイントを指定します。読み取り/書き込み android.graphics.PointF[]。

**戻り値:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

コマンドのポイントを指定します。読み取り/書き込み android.graphics.PointF[]。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

コマンドのタイプを指定します。読み取り/書き込み [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**戻り値:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

コマンドのタイプを指定します。読み取り/書き込み [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

コマンド座標が相対的かどうかを判断します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

コマンド座標が相対的かどうかを判断します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

コマンドポイントのタイプを指定します 読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**戻り値:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

コマンドポイントのタイプを指定します 読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |