---
title: ILegacyDiagram
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示舊版圖表物件
type: docs
url: /zh-hant/com.aspose.slides/ilegacydiagram/
---
**所有已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

表示舊版圖表物件

## 方法

| 方法 | 說明 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converts legacy digram to editable SmartArt object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converts legacy digram to editable group shape. |

### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Converts legacy digram to editable SmartArt object. Created SmartArt object adds to parent group shape at the same position.

**傳回值:**
[ISmartArt](../../com.aspose.slides/ismartart) - 建立的 SmartArt 物件。

### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Converts legacy digram to editable group shape. Created GroupShape object adds to parent group shape at the same position.

**傳回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 建立的 GroupShape 物件。