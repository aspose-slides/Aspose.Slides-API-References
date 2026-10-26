---
title: IMotionCmdPath
second_title: Aspose.Slides for Java API Reference
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
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | コマンドのポイントを指定します。 |
| [getCommandType()](#getCommandType--) | コマンドのタイプを指定します。 |
| [setCommandType(int value)](#setCommandType-int-) | コマンドのタイプを指定します。 |
| [isRelative()](#isRelative--) | コマンドの座標が相対かどうかを決定します。 |
| [setRelative(boolean value)](#setRelative-boolean-) | コマンドの座標が相対かどうかを決定します。 |
| [getPointsType()](#getPointsType--) | コマンドのポイントタイプを指定します。読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
| [setPointsType(int value)](#setPointsType-int-) | コマンドのポイントタイプを指定します。読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。 |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

コマンドのポイントを指定します。読み取り/書き込み java.awt.geom.Point2D.Float[]。

**戻り値:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```

コマンドのポイントを指定します。読み取り/書き込み java.awt.geom.Point2D.Float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

コマンドの座標が相対かどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

コマンドの座標が相対かどうかを決定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

コマンドのポイントタイプを指定します。読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**戻り値:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

コマンドのポイントタイプを指定します。読み取り/書き込み [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |