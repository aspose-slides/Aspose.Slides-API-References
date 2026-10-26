---
title: TabFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許建立 ITab 實例
type: docs
url: /zh-hant/com.aspose.slides/tabfactory/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.ITabFactory](../../com.aspose.slides/itabfactory)  
```
public class TabFactory implements ITabFactory
```

允許建立 ITab 實例

--------------------

用於 COM 相容性。  
## 建構式

| 建構式 | 說明 |
| --- | --- |
| [TabFactory()](#TabFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createTab(double position, int align)](#createTab-double-int-) | 建立新的 ITab 實例。 |
### TabFactory() {#TabFactory--}
```
public TabFactory()
```

### createTab(double position, int align) {#createTab-double-int-}
```
public final ITab createTab(double position, int align)
```

建立新的 ITab 實例。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| position | double | Tab 位置。 |
| align | int | 對齊方式。 |

**傳回值:**
[ITab](../../com.aspose.slides/itab) - 已建立的 tab。