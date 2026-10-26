---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: チャートの3D回転を表します。
type: docs
url: /ja/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

チャートの3D回転を表します。
## メソッド

| Method | 説明 |
| --- | --- |
| [getRotationX()](#getRotationX--) | X軸周りの回転角度を取得または設定します。すなわち |
| [setRotationX(byte value)](#setRotationX-byte-) | X軸周りの回転角度を取得または設定します。すなわち |
| [getRotationY()](#getRotationY--) | Y軸周りの回転角度を取得または設定します。すなわち |
| [setRotationY(int value)](#setRotationY-int-) | Y軸周りの回転角度を取得または設定します。すなわち |
| [getPerspective()](#getPerspective--) | 3Dチャートのパースペクティブ値（視野角）を取得または設定します（0〜100の範囲）。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 3Dチャートのパースペクティブ値（視野角）を取得または設定します（0〜100の範囲）。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | チャートの軸が透視投影ではなく直角であるかどうかを決定します。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | チャートの軸が透視投影ではなく直角であるかどうかを決定します。 |
| [getDepthPercents()](#getDepthPercents--) | 3Dチャートの深さをチャート幅のパーセンテージ（20〜2000%）で取得または設定します。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 3Dチャートの深さをチャート幅のパーセンテージ（20〜2000%）で取得または設定します。 |
| [getHeightPercents()](#getHeightPercents--) | 3Dチャートの高さをチャート幅のパーセンテージ（5〜500%）で指定します。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3Dチャートの高さをチャート幅のパーセンテージ（5〜500%）で指定します。 |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

X軸周りの回転角度を取得または設定します。すなわち3DチャートのY方向の回転（-90〜90度の範囲）です。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007+ の「Y Rotation」オプションに対応しています。読み取り/書き込み可能な byte 型です。

**戻り値:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

X軸周りの回転角度を取得または設定します。すなわち3DチャートのY方向の回転（-90〜90度の範囲）です。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007+ の「Y Rotation」オプションに対応しています。読み取り/書き込み可能な byte 型です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Y軸周りの回転角度を取得または設定します。すなわち3DチャートのX方向の回転（0〜360度の範囲）です。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007+ の「X Rotation」オプションに対応しています。読み取り/書き込み可能な int 型です。

**戻り値:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Y軸周りの回転角度を取得または設定します。すなわち3DチャートのX方向の回転（0〜360度の範囲）です。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007+ の「X Rotation」オプションに対応しています。読み取り/書き込み可能な int 型です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

3Dチャートのパースペクティブ値（視野角）を取得または設定します（0〜100の範囲）。RightAngleAxes プロパティが true の場合は無視されます。読み取り/書き込み可能な byte 型です。

**戻り値:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

3Dチャートのパースペクティブ値（視野角）を取得または設定します（0〜100の範囲）。RightAngleAxes プロパティが true の場合は無視されます。読み取り/書き込み可能な byte 型です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

チャートの軸が透視投影ではなく直角であるかどうかを決定します。言い換えれば、軸の角度がチャートの回転や標高から独立しているかを示します。読み取り/書き込み可能な boolean 型です。

**戻り値:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

チャートの軸が透視投影ではなく直角であるかどうかを決定します。言い換えれば、軸の角度がチャートの回転や標高から独立しているかを示します。読み取り/書き込み可能な boolean 型です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

3Dチャートの深さをチャート幅のパーセンテージ（20〜2000%）で取得または設定します。読み取り/書き込み可能な int 型です。

**戻り値:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

3Dチャートの深さをチャート幅のパーセンテージ（20〜2000%）で取得または設定します。読み取り/書き込み可能な int 型です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

3Dチャートの高さをチャート幅のパーセンテージ（5〜500%）で指定します。読み取り/書き込み可能な int 型です。

**戻り値:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

3Dチャートの高さをチャート幅のパーセンテージ（5〜500%）で指定します。読み取り/書き込み可能な int 型です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |