---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: スライドのサイズと向き（オリエンテーション）を表します。
type: docs
url: /ja/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

スライドのサイズと向き（オリエンテーション）を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSize()](#getSize--) | スライドのサイズをポイント単位で取得します。 |
| [getType()](#getType--) | スライドのサイズタイプを取得します。 |
| [getOrientation()](#getOrientation--) | スライドの向きを取得または設定します。 |
| [setOrientation(int value)](#setOrientation-int-) | スライドの向きを取得または設定します。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | タイプでスライドサイズを設定し、既存のコンテンツをスケールします。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | スライドのサイズを明示的に設定し、既存のコンテンツをスケールします。 |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

スライドのサイズをポイント単位で取得します。

--------------------

新しい値を代入すると、\#getType.getType プロパティが [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) にリセットされ、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が設定されます。

**戻り値:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

スライドのサイズタイプを取得します。

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 以外の任意の値を代入すると、\#getSize.getSize が事前定義されたサイズに合わせて調整され、現在の \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) は保持されます。

**戻り値:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

スライドの向きを取得または設定します。

--------------------

この値を変更すると、スライドの幅と高さが入れ替わります。

**戻り値:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

スライドの向きを取得または設定します。

--------------------

この値を変更すると、スライドの幅と高さが入れ替わります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

タイプでスライドサイズを設定し、既存のコンテンツをスケールします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | 適用する事前定義されたスライドサイズ。 |
| scaleType | int | 使用するコンテンツのスケーリングモード。 |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 以外の任意の値を代入すると、選択されたタイプに基づいて \#getSize.getSize が調整され、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が保持されます。 |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

スライドのサイズを明示的に設定し、既存のコンテンツをスケールします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | float | 新しいスライド幅（ポイント単位）。 |
| height | float | 新しいスライド高さ（ポイント単位）。 |
| scaleType | int | 使用するコンテンツのスケーリングモード。 |

--------------------

これにより、\#getType.getType プロパティが [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) にリセットされ、\{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が設定されます。 |