---
title: PortionFormat
second_title: Aspose.Slides for Android 的 Java API 參考
description: 此類別包含文字片段格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/portionformat/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**全部已實作的介面:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

此類別包含文字片段格式屬性。與 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //實例化一個表示簡報檔案的簡報物件
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides 使用這些特殊識別碼（類似於 PowerPoint 中使用的）：
>      // +mn-lt - 正文拉丁字體（次要拉丁字體）
>      // +mj-lt - 標題字體拉丁語（主要拉丁字體）
>      // +mn-ea - 正文字體東亞語（次要東亞字體）
>      // +mj-ea - 正文字體東亞語（次要東亞字體）
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

此類別用於傳回與操作針對特定片段所定義的文字片段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下您會取得意指「未定義」的值。

若要取得包含繼承的有效格式參數值，必須使用 [getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法，該方法會回傳一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 實例。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | 初始化 [PortionFormat](../../com.aspose.slides/portionformat) 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 傳回或設定書籤識別碼。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 傳回或設定書籤識別碼。 |
| [getSmartTagClean()](#getSmartTagClean--) | 判斷是否應清除智慧標記。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 判斷是否應清除智慧標記。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 傳回或設定滑鼠點擊時的超連結。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 傳回或設定滑鼠點擊時的超連結。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 傳回或設定滑鼠懸停時的超連結。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 傳回或設定滑鼠懸停時的超連結。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | 超連結管理員。 |
| [getEffective()](#getEffective--) | 取得套用繼承的有效片段格式資料。 |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


初始化 [PortionFormat](../../com.aspose.slides/portionformat) 類別的新執行個體。

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


傳回或設定書籤識別碼。讀/寫 String。

**傳回值:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


傳回或設定書籤識別碼。讀/寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


判斷是否應清除智慧標記。未套用繼承。讀/寫 boolean 。

**傳回值:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


判斷是否應清除智慧標記。未套用繼承。讀/寫 boolean 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


傳回或設定滑鼠點擊時的超連結。讀/寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


傳回或設定滑鼠點擊時的超連結。讀/寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


傳回或設定滑鼠懸停時的超連結。讀/寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**傳回值:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


傳回或設定滑鼠懸停時的超連結。讀/寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


超連結管理員。唯讀 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**傳回值:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


取得套用繼承的有效片段格式資料。

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


**傳回值:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - 一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。