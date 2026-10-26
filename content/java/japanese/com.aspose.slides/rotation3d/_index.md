---
title: Rotation3D
second_title: Aspose.Slides for Java API リファレンス
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
| [getRotationX()](#getRotationX--) | X 軸周りの回転角度を取得または設定します。 |
| [setRotationX(byte value)](#setRotationX-byte-) | X 軸周りの回転角度を取得または設定します。 |
| [getRotationY()](#getRotationY--) | Y 軸周りの回転角度を取得または設定します。 |
| [setRotationY(int value)](#setRotationY-int-) | Y 軸周りの回転角度を取得または設定します。 |
| [getPerspective()](#getPerspective--) | 3D チャートの透視値（視野角）を取得または設定します（0 から 240 の範囲）。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D チャートの透視値（視野角）を取得または設定します（0 から 240 の範囲）。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | チャート軸が透視で描画されず、直角であるかどうかを判定します。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | チャート軸が透視で描画されず、直角であるかどうかを判定します。 |
| [getDepthPercents()](#getDepthPercents--) | チャート幅に対する割合として、3D チャートの深さを取得または設定します（20% から 2000% の範囲）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | チャート幅に対する割合として、3D チャートの深さを取得または設定します（20% から 2000% の範囲）。 |
| [getHeightPercents()](#getHeightPercents--) | チャート幅に対する割合として、3-D チャートの高さを指定します（5% から 500% の範囲）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | チャート幅に対する割合として、3-D チャートの高さを指定します（5% から 500% の範囲）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X 軸周りの回転角度を取得または設定します（3D チャートの Y 方向に相当し、-90 から 90 度の範囲）。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007+ の「Y Rotation」オプションに対応しています。読み書き可能な byte 型です。

**戻り値:**
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X 軸周りの回転角度を取得または設定します（3D チャートの Y 方向に相当し、-90 から 90 度の範囲）。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007+ の「Y Rotation」オプションに対応しています。読み書き可能な byte 型です。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y 軸周りの回転角度を取得または設定します（3D チャートの X 方向に相当し、0 から 360 度の範囲）。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007+ の「X Rotation」オプションに対応しています。読み書き可能な int 型です。

**戻り値:**
int

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y 軸周りの回転角度を取得または設定します（3D チャートの X 方向に相当し、0 から 360 度の範囲）。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007+ の「X Rotation」オプションに対応しています。読み書き可能な int 型です。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3D チャートの透視値（視野角）を取得または設定します（0 から 240 の範囲）。RightAngleAxes プロパティの値が true の場合は無視されます。読み書き可能な byte 型です。

**戻り値:**
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3D チャートの透視値（視野角）を取得または設定します（0 から 240 の範囲）。RightAngleAxes プロパティの値が true の場合は無視されます。読み書き可能な byte 型です。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

チャート軸が透視で描画されず、直角であるかどうかを判定します。言い換えれば、軸の角度がチャートの回転や仰角に依存しないかどうかを判定します。読み書き可能な boolean 型です。

**戻り値:**
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

チャート軸が透視で描画されず、直角であるかどうかを判定します。言い換えれば、軸の角度がチャートの回転や仰角に依存しないかどうかを判定します。読み書き可能な boolean 型です。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

チャート幅に対する割合として、3D チャートの深さを取得または設定します（20% から 2000% の範囲）。読み書き可能な int 型です。

**戻り値:**
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

チャート幅に対する割合として、3D チャートの深さを取得または設定します（20% から 2000% の範囲）。読み書き可能な int 型です。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

チャート幅に対する割合として、3-D チャートの高さを指定します（5% から 500% の範囲）。読み書き可能な int 型です。

**戻り値:**
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

チャート幅に対する割合として、3-D チャートの高さを指定します（5% から 500% の範囲）。読み書き可能な int 型です。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用の IDOMObject です。

**戻り値:**
com.aspose.slides.IDOMObject