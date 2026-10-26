---
title: IGroupShape
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド上のシェイプのグループを表します。
type: docs
url: /ja/com.aspose.slides/igroupshape/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

スライド上のシェイプのグループを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | シェイプのロックを返します。 |
| [getShapes()](#getShapes--) | グループ内のシェイプのコレクションを返します。 |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```

シェイプのロックを返します。読み取り専用 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)。

**戻り値:**  
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

グループ内のシェイプのコレクションを返します。読み取り専用 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**戻り値:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)