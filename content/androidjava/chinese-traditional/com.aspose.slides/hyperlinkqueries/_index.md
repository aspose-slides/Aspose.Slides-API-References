---
title: HyperlinkQueries
second_title: Aspose.Slides for Android 之 Java API 參考
description: 提供對包含的超連結的簡易存取。
type: docs
url: /zh-hant/com.aspose.slides/hyperlinkqueries/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

提供對包含的超連結的簡易存取。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | 取得所有包含非 null HyperlinkClick 的 IHyperlinkContainer 子物件。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | 取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | 取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 移除所有包含的 HyperlinkClick 與 HyperlinkMouseOver 超連結（在所有 IHyperlinkContainer 子物件中）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

取得所有包含非 null HyperlinkClick 的 IHyperlinkContainer 子物件。使用給定的 IHyperlinkContainer 物件，您可以管理其超連結（讀取、更新或移除）。請參閱 IHyperlinkContainer 介面。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。使用給定的 IHyperlinkContainer 物件，您可以管理其超連結（讀取、更新或移除）。請參閱 IHyperlinkContainer 介面。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。使用給定的 IHyperlinkContainer 物件，您可以管理其超連結（讀取、更新或移除）。請參閱 IHyperlinkContainer 介面。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

移除所有包含的 HyperlinkClick 與 HyperlinkMouseOver 超連結（在所有 IHyperlinkContainer 子物件中）。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent\_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject