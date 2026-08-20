---
title: GroupShape
second_title: Aspose.Slides for Java API 參考
description: 表示投影片上形狀的群組。
type: docs
url: /zh-hant/com.aspose.slides/groupshape/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**所有已實作的介面：**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

表示投影片上形狀的群組。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 傳回包含形狀線條格式屬性的 LineFormat 物件。 |
| [getGroupShapeLock()](#getGroupShapeLock--) | 傳回形狀的鎖定。 |
| [getShapes()](#getShapes--) | 傳回群組內形狀的集合。 |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


傳回包含形狀線條格式屬性的 LineFormat 物件。注意：對於 GroupShape 物件會傳回 null，因為它們沒有線條屬性。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


傳回形狀的鎖定。唯讀 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)。

**傳回：**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


傳回群組內形狀的集合。唯讀 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**傳回：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)