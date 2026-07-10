---
title: HyperlinkQueries
second_title: Aspose.Slides for Android via Java API 参考
description: 提供对包含的超链接的便捷访问。
type: docs
url: /zh/com.aspose.slides/hyperlinkqueries/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

提供对包含的超链接的便捷访问。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | 获取所有包含非 null HyperlinkClick 的 IHyperlinkContainer 子对象。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | 获取所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子对象。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | 获取所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子对象。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 删除所有包含的 HyperlinkClick 和 HyperlinkMouseOver 超链接（在所有 IHyperlinkContainer 子对象中）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

获取所有包含非 null HyperlinkClick 的 IHyperlinkContainer 子对象。使用给定的 IHyperlinkContainer 对象，您可以管理其超链接（读取、更新或删除）。请参阅 IHyperlinkContainer 接口。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

获取所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子对象。使用给定的 IHyperlinkContainer 对象，您可以管理其超链接（读取、更新或删除）。请参阅 IHyperlinkContainer 接口。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

获取所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子对象。使用给定的 IHyperlinkContainer 对象，您可以管理其超链接（读取、更新或删除）。请参阅 IHyperlinkContainer 接口。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

删除所有包含的 HyperlinkClick 和 HyperlinkMouseOver 超链接（在所有 IHyperlinkContainer 子对象中）。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject