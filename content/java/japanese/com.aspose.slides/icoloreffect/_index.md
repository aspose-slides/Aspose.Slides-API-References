---
title: IColorEffect
second_title: Aspose.Slides for Java API リファレンス
description: アニメーション 動作のためのカラーエフェクトを表します。
type: docs
url: /ja/com.aspose.slides/icoloreffect/
---
**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

アニメーション 動作のためのカラーエフェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrom()](#getFrom--) | この値は動作の開始色を指定するために使用されます。 |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | この値は動作の開始色を指定するために使用されます。 |
| [getTo()](#getTo--) | アニメーションの色変更の結果となる色を記述します。 |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | アニメーションの色変更の結果となる色を記述します。 |
| [getBy()](#getBy--) | カラー アニメーションの相対オフセット値を記述します。 |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | カラー アニメーションの相対オフセット値を記述します。 |
| [getColorSpace()](#getColorSpace--) | 動作のカラースペースを表します。 |
| [setColorSpace(int value)](#setColorSpace-int-) | 動作のカラースペースを表します。 |
| [getDirection()](#getDirection--) | カラーホイール上で色相を回転させる方向を指定します。 |
| [setDirection(int value)](#setDirection-int-) | カラーホイール上で色相を回転させる方向を指定します。 |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

この値は動作の開始色を指定するために使用されます。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

この値は動作の開始色を指定するために使用されます。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

**パラメータ:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

アニメーションの色変更の結果となる色を記述します。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

アニメーションの色変更の結果となる色を記述します。読み取り/書き込み [IColorFormat](../../com.aspose.slides/icolorformat)。

**パラメータ:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

カラー アニメーションの相対オフセット値を記述します。読み取り/書き込み [IColorOffset](../../com.aspose.slides/icoloroffset)。

**戻り値:**  
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

カラー アニメーションの相対オフセット値を記述します。読み取り/書き込み [IColorOffset](../../com.aspose.slides/icoloroffset)。

**パラメータ:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

動作のカラースペースを表します。読み取り/書き込み [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**戻り値:**  
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

動作のカラースペースを表します。読み取り/書き込み [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**パラメータ:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

カラーホイール上で色相を回転させる方向を指定します。読み取り/書き込み [ColorDirection](../../com.aspose.slides/colordirection)。

**戻り値:**  
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

カラーホイール上で色相を回転させる方向を指定します。読み取り/書き込み [ColorDirection](../../com.aspose.slides/colordirection)。

**パラメータ:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |