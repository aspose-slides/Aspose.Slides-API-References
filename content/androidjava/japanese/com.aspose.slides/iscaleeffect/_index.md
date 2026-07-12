---
title: IScaleEffect
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: アニメーションのスケール効果を表します。
type: docs
url: /ja/com.aspose.slides/iscaleeffect/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IScaleEffect extends IBehavior
```

アニメーションのスケール効果を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | コンテンツをズームするかどうかを判定します。 |
| [setZoomContent(byte value)](#setZoomContent-byte-) | コンテンツをズームするかどうかを判定します。 |
| [getFrom()](#getFrom--) | アニメーションの開始座標 (パーセンテージ) を指定します。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | アニメーションの開始座標 (パーセンテージ) を指定します。 |
| [getTo()](#getTo--) | アニメーションのスケール効果の対象位置 (パーセンテージ) を指定します。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | アニメーションのスケール効果の対象位置 (パーセンテージ) を指定します。 |
| [getBy()](#getBy--) | アニメーションの相対オフセット値 (パーセンテージ) を示します。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | アニメーションの相対オフセット値 (パーセンテージ) を示します。 |

### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

コンテンツをズームするかどうかを判定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

コンテンツをズームするかどうかを判定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

アニメーションの開始座標 (パーセンテージ) を指定します。読み取り/書き込み android.graphics.PointF。

**戻り値:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

アニメーションの開始座標 (パーセンテージ) を指定します。読み取り/書き込み android.graphics.PointF。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

アニメーションのスケール効果の対象位置 (パーセンテージ) を指定します。読み取り/書き込み android.graphics.PointF。

**戻り値:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

アニメーションのスケール効果の対象位置 (パーセンテージ) を指定します。読み取り/書き込み android.graphics.PointF。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

アニメーションの相対オフセット値 (パーセンテージ) を示します。読み取り/書き込み android.graphics.PointF。

**戻り値:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

アニメーションの相対オフセット値 (パーセンテージ) を示します。読み取り/書き込み android.graphics.PointF。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |