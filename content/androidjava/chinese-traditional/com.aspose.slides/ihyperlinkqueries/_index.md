---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API 參考文件
description: 提供對包含的超連結的簡易存取。
type: docs
url: /zh-hant/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

提供對包含的超連結的簡易存取。

## Methods

| Method | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | 取得所有包含非 null HyperlinkClick 的 IHyperlinkContainer 子物件。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | 取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | 取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 移除所有包含的 HyperlinkClick 與 HyperlinkMouseOver 超連結（在所有 IHyperlinkContainer 子物件中）。 |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

取得所有包含非 null HyperlinkClick 的 IHyperlinkContainer 子物件。使用給定的 IHyperlinkContainer 物件，您可以管理其超連結（讀取、更新或移除）。請參閱 IHyperlinkContainer 介面。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。使用給定的 IHyperlinkContainer 物件，您可以管理其超連結（讀取、更新或移除）。請參閱 IHyperlinkContainer 介面。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

取得所有包含非 null HyperlinkMouseOver 的 IHyperlinkContainer 子物件。使用給定的 IHyperlinkContainer 物件，您可以管理其超連結（讀取、更新或移除）。請參閱 IHyperlinkContainer 介面。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

移除所有包含的 HyperlinkClick 與 HyperlinkMouseOver 超連結（在所有 IHyperlinkContainer 子物件中）。