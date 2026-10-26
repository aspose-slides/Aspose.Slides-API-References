---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides for Java API 参考
description: 表示管理占位符行为的管理器，包括所有类型的讲义和备注幻灯片的标题占位符。
type: docs
url: /zh/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

代表管理占位符行为的管理器，包括所有类型的讲义和备注幻灯片的标题占位符。

--------------------

原始接口名称 “IBaseHandoutNotesSlideHeaderFooterManager” 为了 COM 兼容性被截断为 “IBaseHandoutNotesSlideHeaderFooterManag”（类型名称长度不得超过 39）。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 获取指示标题占位符是否存在的值。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 更改幻灯片标题占位符的可见性。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 设置幻灯片标题占位符的文本。 |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

获取指示标题占位符是否存在的值。读取 boolean。

**返回：**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

更改幻灯片标题占位符的可见性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使标题占位符可见，otherwise - 隐藏它。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

设置幻灯片标题占位符的文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |