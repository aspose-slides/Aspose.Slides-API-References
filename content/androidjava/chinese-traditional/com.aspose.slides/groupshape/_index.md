---
title: GroupShape
second_title: Aspose.Slides for Android 透過 Java API 參考
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

| 方法 | 描述 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 傳回包含形狀線條格式屬性的 LineFormat 物件。 |
| [getGroupShapeLock()](#getGroupShapeLock--) | 傳回形狀的鎖定。 |
| [getShapes()](#getShapes--) | 傳回群組內的形狀集合。 |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

傳回包含形狀線條格式屬性的 LineFormat 物件。注意：對於 GroupShape 物件傳回 null，因為它們沒有線條屬性。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回值：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

傳回形狀的鎖定。唯讀 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)。

**傳回值：**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

傳回群組內的形狀集合。唯讀 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**傳回值：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)