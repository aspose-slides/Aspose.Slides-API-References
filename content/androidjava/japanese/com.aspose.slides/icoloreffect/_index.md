---
title: IColorEffect
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: アニメーション 動作のカラー効果を表します。
type: docs
url: /ja/com.aspose.slides/icoloreffect/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

アニメーション動作のカラー効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrom()](#getFrom--) | この値は動作の開始カラーを指定するために使用されます。 |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | この値は動作の開始カラーを指定するために使用されます。 |
| [getTo()](#getTo--) | アニメーションのカラー変更の結果となるカラーを記述します。 |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | アニメーションのカラー変更の結果となるカラーを記述します。 |
| [getBy()](#getBy--) | カラーアニメーションの相対オフセット値を記述します。 |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | カラーアニメーションの相対オフセット値を記述します。 |
| [getColorSpace()](#getColorSpace--) | 動作のカラー空間を表します。 |
| [setColorSpace(int value)](#setColorSpace-int-) | 動作のカラー空間を表します。 |
| [getDirection()](#getDirection--) | カラーホイール上で色相を回す方向を指定します。 |
| [setDirection(int value)](#setDirection-int-) | カラーホイール上で色相を回す方向を指定します。 |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

この値は動作の開始カラーを指定するために使用されます。読み書き [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

この値は動作の開始カラーを指定するために使用されます。読み書き [IColorFormat](../../com.aspose.slides/icolorformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

アニメーションのカラー変更の結果となるカラーを記述します。読み書き [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

アニメーションのカラー変更の結果となるカラーを記述します。読み書き [IColorFormat](../../com.aspose.slides/icolorformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

カラーアニメーションの相対オフセット値を記述します。読み書き [IColorOffset](../../com.aspose.slides/icoloroffset)。

**戻り値:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

カラーアニメーションの相対オフセット値を記述します。読み書き [IColorOffset](../../com.aspose.slides/icoloroffset)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

動作のカラー空間を表します。読み書き [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**戻り値:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

動作のカラー空間を表します。読み書き [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

カラーホイール上で色相を回す方向を指定します。読み書き [ColorDirection](../../com.aspose.slides/colordirection)。

**戻り値:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

カラーホイール上で色相を回す方向を指定します。読み書き [ColorDirection](../../com.aspose.slides/colordirection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |