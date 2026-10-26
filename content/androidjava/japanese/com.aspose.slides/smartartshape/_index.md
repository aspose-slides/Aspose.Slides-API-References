---
title: SmartArtShape
second_title: Java API リファレンスによる Android 用 Aspose.Slides
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
| [getShapeType()](#getShapeType--) | ジオメトリプリセットタイプを取得または設定します。 |
| [setShapeType(int value)](#setShapeType-int-) | ジオメトリプリセットタイプを取得または設定します。 |
| [getTextFrame()](#getTextFrame--) | SmartArt シェイプのテキストを取得します。 |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ジオメトリプリセットタイプを取得または設定します。 注: 値を変更すると、すべての調整値はデフォルト値にリセットされます。 読み書き可能 [ShapeType](../../com.aspose.slides/shapetype)。

**戻り値:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ジオメトリプリセットタイプを取得または設定します。 注: 値を変更すると、すべての調整値はデフォルト値にリセットされます。 読み書き可能 [ShapeType](../../com.aspose.slides/shapetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

SmartArt シェイプのテキストを取得します。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**  
[ITextFrame](../../com.aspose.slides/itextframe)