---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API 参考
description: 提供超链接的管理，包括添加和移除。
type: docs
url: /zh/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

提供超链接的管理（添加，移除）。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 设置点击时的外部超链接。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 设置点击时的内部超链接。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 移除点击时的超链接。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 设置鼠标悬停时的外部超链接。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 设置鼠标悬停时的内部超链接。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 移除鼠标悬停时的超链接。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 设置点击时的宏超链接。 |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

设置点击时的外部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 对象 [IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

设置点击时的内部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink。

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

移除点击时的超链接。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

设置鼠标悬停时的外部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink。

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

设置鼠标悬停时的内部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink。

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

移除鼠标悬停时的超链接。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

设置点击时的宏超链接。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| macroName | java.lang.String | 宏的名称 |

**返回:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 对象 [IHyperlink](../../com.aspose.slides/ihyperlink)