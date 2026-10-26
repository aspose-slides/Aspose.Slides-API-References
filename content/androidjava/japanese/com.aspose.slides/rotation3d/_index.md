---
title: Rotation3D
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: チャートの 3D 回転を表します。
type: docs
url: /ja/com.aspose.slides/rotation3d/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

チャートの 3D 回転を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRotationX()](#getRotationX--) | X 軸周りの回転角度を取得または設定します。つまり |
| [setRotationX(byte value)](#setRotationX-byte-) | X 軸周りの回転角度を取得または設定します。つまり |
| [getRotationY()](#getRotationY--) | Y 軸周りの回転角度を取得または設定します。つまり |
| [setRotationY(int value)](#setRotationY-int-) | Y 軸周りの回転角度を取得または設定します。つまり |
| [getPerspective()](#getPerspective--) | 3D グラフの視点値（視野角）を取得または設定します（0〜240 の範囲）。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D グラフの視点値（視野角）を取得または設定します（0〜240 の範囲）。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | チャートの軸が透視投影ではなく直角であるかどうかを判定します。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | チャートの軸が透視投影ではなく直角であるかどうかを判定します。 |
| [getDepthPercents()](#getDepthPercents--) | チャート幅に対する 3D グラフの深さをパーセンテージで取得または設定します（20〜2000% の範囲）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | チャート幅に対する 3D グラフの深さをパーセンテージで取得または設定します（20〜2000% の範囲）。 |
| [getHeightPercents()](#getHeightPercents--) | チャート幅に対する 3-D グラフの高さをパーセンテージで指定します（5〜500% の範囲）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | チャート幅に対する 3-D グラフの高さをパーセンテージで指定します（5〜500% の範囲）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X 軸周りの回転角度を取得または設定します。つまり 3D グラフでは Y 方向です（-90〜90 度の範囲）。このプロパティは ECMA-376 の 21.2.2.157 rotX (X Rotation) 項目および PowerPoint 2007+ の "Y Rotation" オプションと一致します。読み書き可能な byte。

**Returns:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X 軸周りの回転角度を取得または設定します。つまり 3D グラフでは Y 方向です（-90〜90 度の範囲）。このプロパティは ECMA-376 の 21.2.2.157 rotX (X Rotation) 項目および PowerPoint 2007+ の "Y Rotation" オプションと一致します。読み書き可能な byte。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y 軸周りの回転角度を取得または設定します。つまり 3D グラフでは X 方向です（0〜360 度の範囲）。このプロパティは ECMA-376 の 21.2.2.158 rotY (Y Rotation) 項目および PowerPoint 2007+ の "X Rotation" オプションと一致します。読み書き可能な int。

**Returns:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y 軸周りの回転角度を取得または設定します。つまり 3D グラフでは X 方向です（0〜360 度の範囲）。このプロパティは ECMA-376 の 21.2.158 rotY (Y Rotation) 項目および PowerPoint 2007+ の "X Rotation" オプションと一致します。読み書き可能な int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3D グラフの視点値（視野角）を取得または設定します（0〜240 の範囲）。RightAngleAxes プロパティの値が true の場合は無視されます。読み書き可能な byte。

**Returns:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3D グラフの視点値（視野角）を取得または設定します（0〜240 の範囲）。RightAngleAxes プロパティの値が true の場合は無視されます。読み書き可能な byte。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

チャートの軸が透視投影ではなく直角であるかどうかを判定します。つまり、軸の角度がチャートの回転や仰角とは独立しているかを決定します。読み書き可能な boolean。

**Returns:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

チャートの軸が透視投影ではなく直角であるかどうかを判定します。つまり、軸の角度がチャートの回転や仰角とは独立しているかを決定します。読み書き可能な boolean。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

チャート幅に対する 3D グラフの深さをパーセンテージで取得または設定します（20〜2000% の範囲）。読み書き可能な int。

**Returns:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

チャート幅に対する 3D グラフの深さをパーセンテージで取得または設定します（20〜2000% の範囲）。読み書き可能な int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

チャート幅に対する 3-D グラフの高さをパーセンテージで指定します（5〜500% の範囲）。読み書き可能な int。

**Returns:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

チャート幅に対する 3-D グラフの高さをパーセンテージで指定します（5〜500% の範囲）。読み書き可能な int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用の IDOMObject。

**Returns:**
com.aspose.slides.IDOMObject