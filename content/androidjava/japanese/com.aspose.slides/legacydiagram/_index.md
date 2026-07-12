---
title: LegacyDiagram
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: レガシーダイアグラムオブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/legacydiagram/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

レガシーダイアグラムオブジェクトを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | レガシーダイアグラムを編集可能な SmartArt オブジェクトに変換します。 |
| [convertToGroupShape()](#convertToGroupShape--) | レガシーダイアグラムを編集可能なグループシェイプに変換します。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


レガシーダイアグラムを編集可能な SmartArt オブジェクトに変換します。作成された SmartArt オブジェクトは同じ位置にある親グループシェイプに追加されます。

**戻り値:**
[ISmartArt](../../com.aspose.slides/ismartart) - 作成された SmartArt オブジェクト。
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


レガシーダイアグラムを編集可能なグループシェイプに変換します。作成された GroupShape オブジェクトは同じ位置にある親グループシェイプに追加されます。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 作成された GroupShape オブジェクト。