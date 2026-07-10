---
title: IHyperlinkManager
second_title: Aspose.Slides for Android 的 Java API 参考
description: 提供超链接管理（添加，删除）。
type: docs
url: /zh/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

提供超链接管理（添加，删除）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


在单击时设置外部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 对象 [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


在单击时设置内部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


在单击时移除超链接。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


在鼠标悬停时设置外部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 对象。
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


在鼠标悬停时设置内部超链接。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 对象。
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


在鼠标悬停时移除超链接。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


在单击时设置 Macro 超链接。

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

**返回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 对象 [IHyperlink](../../com.aspose.slides/ihyperlink)