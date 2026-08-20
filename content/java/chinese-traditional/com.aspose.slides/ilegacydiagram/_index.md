---
title: ILegacyDiagram
second_title: Aspose.Slides for Java API 參考文件
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

| 方法 | 描述 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 將舊版圖表轉換為可編輯的 SmartArt 物件。 |
| [convertToGroupShape()](#convertToGroupShape--) | 將舊版圖表轉換為可編輯的 GroupShape。 |

### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

將舊版圖表轉換為可編輯的 SmartArt 物件。建立的 SmartArt 物件會加入到父群組形狀的相同位置。

**傳回：**
[ISmartArt](../../com.aspose.slides/ismartart) - 建立的 SmartArt 物件。

### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

將舊版圖表轉換為可編輯的 GroupShape。建立的 GroupShape 物件會加入到父群組形狀的相同位置。

**傳回：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 建立的 GroupShape 物件。