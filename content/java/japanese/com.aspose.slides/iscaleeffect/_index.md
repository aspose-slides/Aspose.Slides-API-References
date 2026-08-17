---
title: IScaleEffect
second_title: Aspose.Slides for Java API リファレンス
description: アニメーションのスケール効果を表します。
type: docs
url: /ja/com.aspose.slides/iscaleeffect/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IScaleEffect extends IBehavior
```

アニメーションスケール効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | コンテンツをズームするかどうかを判定します。 |
| [setZoomContent(byte value)](#setZoomContent-byte-) | コンテンツをズームするかどうかを判定します。 |
| [getFrom()](#getFrom--) | アニメーションの開始位置となる x/y 座標を指定します（パーセント単位）。 |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | アニメーションの開始位置となる x/y 座標を指定します（パーセント単位）。 |
| [getTo()](#getTo--) | アニメーションスケール効果の対象位置を指定します（パーセント単位）。 |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | アニメーションスケール効果の対象位置を指定します（パーセント単位）。 |
| [getBy()](#getBy--) | アニメーションの相対オフセット値を記述します（パーセント単位）。 |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | アニメーションの相対オフセット値を記述します（パーセント単位）。 |

### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

コンテンツをズームするかどうかを判定します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte

### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

コンテンツをズームするかどうかを判定します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

アニメーションの開始位置となる x/y 座標を指定します（パーセント単位）。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

アニメーションの開始位置となる x/y 座標を指定します（パーセント単位）。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

アニメーションスケール効果の対象位置を指定します（パーセント単位）。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

アニメーションスケール効果の対象位置を指定します（パーセント単位）。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

アニメーションの相対オフセット値を記述します（パーセント単位）。 読み取り/書き込み java.awt.geom.Point2D.Float.

**戻り値:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

アニメーションの相対オフセット値を記述します（パーセント単位）。 読み取り/書き込み java.awt.geom.Point2D.Float.

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |