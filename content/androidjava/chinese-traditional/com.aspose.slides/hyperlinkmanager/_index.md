---
title: HyperlinkManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 提供超連結管理（新增、移除）。
type: docs
url: /zh-hant/com.aspose.slides/hyperlinkmanager/
---
**繼承：**
java.lang.Object

**已實作的所有介面：**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

提供超連結管理（新增、移除）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 在點擊時設定外部超連結。 |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 在點擊時設定內部超連結。 |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 在點擊時移除超連結。 |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 在滑鼠懸停時設定外部超連結。 |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 在滑鼠懸停時設定內部超連結。 |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 在滑鼠懸停時移除超連結。 |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 在點擊時設定巨集超連結。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


在點擊時設定外部超連結。

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // 實例化一個代表 PPTX 的 Presentation 類別
>  Presentation pres = new Presentation();
>  try {
>      // 取得簡報中的第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 新增一個類型為矩形的 AutoShape 物件
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // 將形狀轉型為 AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // 存取與 AutoShape 相關聯的 ITextFrame 屬性
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 在框架中加入一些文字
>      portion.setText("Aspose.Slides");
>      // 設定文字段的超連結
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


在點擊時設定內部超連結。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


在點擊時移除超連結。

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


在滑鼠懸停時設定外部超連結。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


在滑鼠懸停時設定內部超連結。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


在滑鼠懸停時移除超連結。

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


在點擊時設定巨集超連結。

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
| macroName | java.lang.String | 巨集名稱 |

**返回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 物件。 唯讀 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject