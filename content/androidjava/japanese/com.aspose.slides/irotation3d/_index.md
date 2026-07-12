---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: チャートの 3D 回転を表します。
type: docs
url: /ja/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

チャートの 3D 回転を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRotationX()](#getRotationX--) | X 軸周りの回転角度を取得または設定します。 |
| [setRotationX(byte value)](#setRotationX-byte-) | X 軸周りの回転角度を取得または設定します。 |
| [getRotationY()](#getRotationY--) | Y 軸周りの回転角度を取得または設定します。 |
| [setRotationY(int value)](#setRotationY-int-) | Y 軸周りの回転角度を取得または設定します。 |
| [getPerspective()](#getPerspective--) | 3D チャートのパースペクティブ値（視野角）を取得または設定します（0〜100 の範囲）。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D チャートのパースペクティブ値（視野角）を取得または設定します（0〜100 の範囲）。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | チャートの軸が透視投影ではなく直角であるかどうかを判定します。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | チャートの軸が透視投影ではなく直角であるかどうかを判定します。 |
| [getDepthPercents()](#getDepthPercents--) | チャート幅に対するパーセンテージとして 3D チャートの深さを取得または設定します（20〜2000% の範囲）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | チャート幅に対するパーセンテージとして 3D チャートの深さを取得または設定します（20〜2000% の範囲）。 |
| [getHeightPercents()](#getHeightPercents--) | チャート幅に対するパーセンテージとして 3-D チャートの高さを指定します（5〜500% の範囲）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | チャート幅に対するパーセンテージとして 3-D チャートの高さを指定します（5〜500% の範囲）。 |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

X 軸周りの回転角度を取得または設定します（3D チャートの Y 方向、-90〜90 度）。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007 以降の「Y Rotation」オプションに対応しています。読み取り/書き込み byte。

**戻り値:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

X 軸周りの回転角度を取得または設定します（3D チャートの Y 方向、-90〜90 度）。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007 以降の「Y Rotation」オプションに対応しています。読み取り/書き込み byte。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Y 軸周りの回転角度を取得または設定します（3D チャートの X 方向、0〜360 度）。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007 以降の「X Rotation」オプションに対応しています。読み取り/書き込み int。

**戻り値:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Y 軸周りの回転角度を取得または設定します（3D チャートの X 方向、0〜360 度）。このプロパティは ECMA-376 の 21.2.158 rotY（Y Rotation）項目および PowerPoint 2007 以降の「X Rotation」オプションに対応しています。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

3D チャートのパースペクティブ値（視野角）を取得または設定します（0〜100 の範囲）。RightAngleAxes プロパティが true の場合は無視されます。読み取り/書き込み byte。

**戻り値:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

3D チャートのパースペクティブ値（視野角）を取得または設定します（0〜100 の範囲）。RightAngleAxes プロパティが true の場合は無視されます。読み取り/書き込み byte。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

チャートの軸が透視投影ではなく直角であるかどうかを判定します。つまり、軸の角度がチャートの回転や傾きに依存しないかどうかを判断します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

チャートの軸が透視投影ではなく直角であるかどうかを判定します。つまり、軸の角度がチャートの回転や傾きに依存しないかどうかを判断します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

チャート幅に対するパーセンテージとして 3D チャートの深さを取得または設定します（20〜2000% の範囲）。読み取り/書き込み int。

**戻り値:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

チャート幅に対するパーセンテージとして 3D チャートの深さを取得または設定します（20〜2000% の範囲）。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

チャート幅に対するパーセンテージとして 3-D チャートの高さを指定します（5〜500% の範囲）。読み取り/書き込み int。

**戻り値:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

チャート幅に対するパーセンテージとして 3-D チャートの高さを指定します（5〜500% の範囲）。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |