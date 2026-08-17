---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /ja/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

スライドのサイズと向きを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | スライドの寸法をポイントで取得します。 |
| [getType()](#getType--) | スライドのサイズタイプを取得します。 |
| [getOrientation()](#getOrientation--) | スライドの向きを取得または設定します。 |
| [setOrientation(int value)](#setOrientation-int-) | スライドの向きを取得または設定します。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | タイプでスライドサイズを設定し、既存のコンテンツをスケールします。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | スライドの寸法を明示的に設定し、既存のコンテンツをスケールします。 |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

スライドの寸法をポイントで取得します。

--------------------

新しい値を割り当てると、\#getType.getType プロパティが [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) にリセットされ、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が設定されます。

**Returns:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

スライドのサイズタイプを取得します。

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 以外の任意の値を割り当てると、事前定義された寸法に従って \#getSize.getSize が調整され、現在の \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) は保持されます。

**Returns:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

スライドの向きを取得または設定します。

--------------------

この値を変更すると、スライドの幅と高さが入れ替わります。

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

スライドの向きを取得または設定します。

--------------------

この値を変更すると、スライドの幅と高さが入れ替わります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

タイプでスライドサイズを設定し、既存のコンテンツをスケールします。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 適用する事前定義されたスライドサイズ。 |
| scaleType | int | 使用するコンテンツのスケーリングモード。 |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 以外の任意の値を割り当てると、選択したタイプに基づいて \#getSize.getSize が調整され、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が保持されます。

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

スライドの寸法を明示的に設定し、既存のコンテンツをスケールします。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | 新しいスライド幅（ポイント単位）。 |
| height | float | 新しいスライド高さ（ポイント単位）。 |
| scaleType | int | 使用するコンテンツのスケーリングモード。 |

--------------------

\#getType.getType プロパティが [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) にリセットされ、\{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が設定されます。