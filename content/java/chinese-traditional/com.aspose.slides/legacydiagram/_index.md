---
title: LegacyDiagram
second_title: Aspose.Slides for Java API 參考
description: 表示舊版圖表物件。
type: docs
url: /zh-hant/com.aspose.slides/legacydiagram/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已實作的介面：**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

表示舊版 digram 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 將舊版 digram 轉換為可編輯的 SmartArt 物件。 |
| [convertToGroupShape()](#convertToGroupShape--) | 將舊版 digram 轉換為可編輯的群組形狀。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


將舊版 digram 轉換為可編輯的 SmartArt 物件。建立的 SmartArt 物件會加入父群組形狀於相同位置。

**傳回值：**
[ISmartArt](../../com.aspose.slides/ismartart) - 已建立的 SmartArt 物件。

### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


將舊版 digram 轉換為可編輯的群組形狀。建立的 GroupShape 物件會加入父群組形狀於相同位置。

**傳回值：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 已建立的 GroupShape 物件。