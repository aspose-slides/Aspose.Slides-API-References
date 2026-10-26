---
title: HyperlinkManager
second_title: Aspose.Slides for Java API 參考文件
description: 提供超連結管理（新增、移除）。
type: docs
url: /zh-hant/com.aspose.slides/hyperlinkmanager/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

提供超連結管理（新增、移除）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 設定外部超連結於點擊時。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 設定內部超連結於點擊時。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 移除點擊時的超連結。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 設定外部超連結於滑鼠懸停時。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 設定內部超連結於滑鼠懸停時。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 移除滑鼠懸停時的超連結。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 設定巨集超連結於點擊時。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

設定外部超連結於點擊時。

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // 建立一個代表 PPTX 的 Presentation 類別實例
>  Presentation pres = new Presentation();
>  try {
>      // 取得簡報中的第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 新增一個類型為 Rectangle 的 AutoShape 物件
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // 將形狀轉型為 AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // 存取與 AutoShape 相關聯的 ITextFrame 屬性
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 在框架中加入一些文字
>      portion.setText("Aspose.Slides");
>      // 為該段文字設定超連結
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // 儲存 PPTX 簡報
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

設定內部超連結於點擊時。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 超連結。

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

移除點擊時的超連結。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

設定外部超連結於滑鼠懸停時。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 超連結。

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

設定內部超連結於滑鼠懸停時。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 超連結。

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

移除滑鼠懸停時的超連結。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

設定巨集超連結於點擊時。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| macroName | java.lang.String | 巨集的名稱 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 超連結物件 [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject