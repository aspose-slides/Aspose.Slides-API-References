---
title: SlideSize
second_title: Java API リファレンスを介した Aspose.Slides for Android
description: スライドのサイズと向きを表します。
type: docs
url: /ja/com.aspose.slides/slidesize/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)  
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

スライドのサイズと向きを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSize()](#getSize--) | ポイント単位でスライドのサイズを取得します。 |
| [getType()](#getType--) | スライドのサイズタイプを取得します。 |
| [getOrientation()](#getOrientation--) | スライドの向きを取得または設定します。 |
| [setOrientation(int value)](#setOrientation-int-) | スライドの向きを取得または設定します。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | タイプでスライドサイズを設定し、既存のコンテンツをスケーリングします。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | スライドのサイズを明示的に設定し、既存のコンテンツをスケーリングします。 |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

ポイント単位でスライドのサイズを取得します。

--------------------

新しい値を割り当てると、\#getType.getType プロパティが [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) にリセットされ、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が設定されます。

**戻り値:**
[SizeF](../../com.aspose.slides.android/sizef)

### getType() {#getType--}
```
public final int getType()
```

スライドのサイズタイプを取得します。

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 以外の任意の値を割り当てると、事前定義されたサイズに従って \#getSize.getSize が調整され、現在の \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が保持されます。

**戻り値:**
int

### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

スライドの向きを取得または設定します。

--------------------

この値を変更すると、スライドの幅と高さが入れ替わります。

**戻り値:**
int

### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

スライドの向きを取得または設定します。

--------------------

この値を変更すると、スライドの幅と高さが入れ替わります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

タイプでスライドサイズを設定し、既存のコンテンツをスケーリングします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 適用する事前定義済みスライドサイズ。 |
| scaleType | int | 使用するコンテンツのスケーリングモード。 |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 以外の任意の値を割り当てると、選択されたタイプに基づいて \#getSize.getSize が調整され、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が保持されます。 |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

ポイント単位でスライドのサイズを明示的に設定し、既存のコンテンツをスケーリングします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | float | ポイント単位の新しいスライド幅。 |
| height | float | ポイント単位の新しいスライド高さ。 |
| scaleType | int | 使用するコンテンツのスケーリングモード。 |

--------------------

これにより、\#getType.getType プロパティが [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) にリセットされ、\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) が設定されます。 |