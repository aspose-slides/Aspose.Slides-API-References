---
title: PortionFormat
second_title: Aspose.Slides for Java API 參考文件
description: 此類別包含文字片段格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/portionformat/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**所有已實作的介面:**  
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)  
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

此類別包含文字片段格式屬性。與 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //實例化一個代表簡報檔案的簡報物件
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides 使用這些特殊標識符（類似於 PowerPoint 中使用的）：
>      // +mn-lt - 正文字體拉丁文（次要拉丁字體）
>      // +mj-lt -標題字體拉丁文（主要拉丁字體）
>      // +mn-ea - 正文字體東亞語系（次要東亞字體）
>      // +mj-ea - 正文字體東亞語系（次要東亞字體）
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

此類別用於返回和操作針對特定片段定義的文字片段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會得到表示「undefined」的值。

為了取得包括繼承在內的有效格式參數值，您需要使用 [getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法，該方法會傳回一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 實例。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | 初始化 [PortionFormat](../../com.aspose.slides/portionformat) 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 傳回或設定書籤識別碼。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 傳回或設定書籤識別碼。 |
| [getSmartTagClean()](#getSmartTagClean--) | 判斷是否應該清除智慧標記。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 判斷是否應該清除智慧標記。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 傳回或設定滑鼠點擊時的超連結。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 傳回或設定滑鼠點擊時的超連結。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 傳回或設定滑鼠懸停時的超連結。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 傳回或設定滑鼠懸停時的超連結。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | 超連結管理員。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效片段格式資料。 |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

初始化 [PortionFormat](../../com.aspose.slides/portionformat) 類別的新執行個體。

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

傳回或設定書籤識別碼。可讀寫 String。

**傳回:**  
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

傳回或設定書籤識別碼。可讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

判斷是否應該清除智慧標記。未套用繼承。可讀寫 boolean 。

**傳回:**  
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

判斷是否應該清除智慧標記。未套用繼承。可讀寫 boolean 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

傳回或設定滑鼠點擊時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**傳回:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

傳回或設定滑鼠點擊時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

傳回或設定滑鼠懸停時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**傳回:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

傳回或設定滑鼠懸停時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

超連結管理員。唯讀 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**傳回:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

取得套用繼承後的有效片段格式資料。

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**傳回:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - 一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).