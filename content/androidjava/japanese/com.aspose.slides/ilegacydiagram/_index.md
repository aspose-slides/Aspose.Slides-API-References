---
title: ILegacyDiagram
second_title: Android 用 Aspose.Slides（Java API リファレンス）
description: レガシー ダイアグラム オブジェクトを表します
type: docs
url: /ja/com.aspose.slides/ilegacydiagram/
---
**実装されたすべてのインターフェース:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

レガシー digram オブジェクトを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | legacy digram を編集可能な SmartArt オブジェクトに変換します。 |
| [convertToGroupShape()](#convertToGroupShape--) | legacy digram を編集可能なグループ シェイプに変換します。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

legacy digram を編集可能な SmartArt オブジェクトに変換します。作成された SmartArt オブジェクトは、同じ位置の親グループ シェイプに追加されます。

**戻り値:**
[ISmartArt](../../com.aspose.slides/ismartart) - 作成された SmartArt オブジェクト。
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

legacy digram を編集可能なグループ シェイプに変換します。作成された GroupShape オブジェクトは、同じ位置の親グループ シェイプに追加されます。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 作成された GroupShape オブジェクト。