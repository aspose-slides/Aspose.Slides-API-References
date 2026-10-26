---
title: ILegacyDiagram
second_title: Aspose.Slides for Java API リファレンス
description: レガシーダイアグラム オブジェクトを表します
type: docs
url: /ja/com.aspose.slides/ilegacydiagram/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

レガシーダイアグラム オブジェクトを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | レガシーダイアグラムを編集可能な SmartArt オブジェクトに変換します。 |
| [convertToGroupShape()](#convertToGroupShape--) | レガシーダイアグラムを編集可能なグループシェイプに変換します。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

レガシーダイアグラムを編集可能な SmartArt オブジェクトに変換します。作成された SmartArt オブジェクトは、同じ位置にある親グループシェイプに追加されます。

**戻り値:**
[ISmartArt](../../com.aspose.slides/ismartart) - 作成された SmartArt オブジェクト。
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

レガシーダイアグラムを編集可能なグループシェイプに変換します。作成された GroupShape オブジェクトは、同じ位置にある親グループシェイプに追加されます。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 作成された GroupShape オブジェクト。