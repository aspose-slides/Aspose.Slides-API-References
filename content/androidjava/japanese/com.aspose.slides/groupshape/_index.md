---
title: GroupShape
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: スライド上のシェイプのグループを表します。
type: docs
url: /ja/com.aspose.slides/groupshape/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

スライド上のシェイプのグループを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | シェイプのライン書式プロパティを含む LineFormat オブジェクトを返します。 |
| [getGroupShapeLock()](#getGroupShapeLock--) | シェイプのロックを返します。 |
| [getShapes()](#getShapes--) | グループ内のシェイプのコレクションを返します。 |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

シェイプのライン書式プロパティを含む LineFormat オブジェクトを返します。 注: GroupShape オブジェクトはラインプロパティを持たないため、null を返します。 読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

シェイプのロックを返します。 読み取り専用 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)。

**戻り値:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

グループ内のシェイプのコレクションを返します。 読み取り専用 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**戻り値:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)