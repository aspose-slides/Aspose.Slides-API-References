---
title: SmartArtShape
second_title: Aspose.Slides for Java API リファレンス
description: SmartArt シェイプを表します
type: docs
url: /ja/com.aspose.slides/smartartshape/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

SmartArt シェイプを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapeType()](#getShapeType--) | ジオメトリのプリセットタイプを取得または設定します。 |
| [setShapeType(int value)](#setShapeType-int-) | ジオメトリのプリセットタイプを取得または設定します。 |
| [getTextFrame()](#getTextFrame--) | SmartArt シェイプのテキストを取得します。 |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ジオメトリのプリセットタイプを取得または設定します。注: 値を変更すると、すべての調整値はデフォルト値にリセットされます。読み取り/書き込み [ShapeType](../../com.aspose.slides/shapetype)。

**戻り値:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ジオメトリのプリセットタイプを取得または設定します。注: 値を変更すると、すべての調整値はデフォルト値にリセットされます。読み取り/書き込み [ShapeType](../../com.aspose.slides/shapetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

SmartArt シェイプのテキストを取得します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)