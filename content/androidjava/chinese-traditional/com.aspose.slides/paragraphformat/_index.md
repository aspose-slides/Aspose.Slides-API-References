---
title: ParagraphFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 此類別包含段落格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/paragraphformat/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**全部已實作的介面:**  
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)  
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

此類別包含段落格式屬性。與 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

此類別用於返回和操作針對特定段落定義的段落格式屬性。這表示在取得值時不套用繼承，因此在大多數情況下會取得「未定義」的值。

若要取得包含繼承的有效格式參數值，必須使用 [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法，該方法會返回一個 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 實例。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | 初始化 [ParagraphFormat](../../com.aspose.slides/paragraphformat) 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBullet()](#getBullet--) | 傳回段落的項目符號格式。 |
| [getDepth()](#getDepth--) | 傳回或設定段落的深度。 |
| [setDepth(short value)](#setDepth-short-) | 傳回或設定段落的深度。 |
| [getAlignment()](#getAlignment--) | 傳回或設定段落的文字對齊（不套用繼承）。 |
| [setAlignment(int value)](#setAlignment-int-) | 傳回或設定段落的文字對齊（不套用繼承）。 |
| [getSpaceWithin()](#getSpaceWithin--) | 傳回或設定段落基線之間的間距。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 傳回或設定段落基線之間的間距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 傳回或設定段落第一行前的間距（不套用繼承）。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 傳回或設定段落第一行前的間距（不套用繼承）。 |
| [getSpaceAfter()](#getSpaceAfter--) | 傳回或設定段落最後一行後的間距（不套用繼承）。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 傳回或設定段落最後一行後的間距（不套用繼承）。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 判斷段落是否使用東亞斷行。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 判斷段落是否使用東亞斷行。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷段落是否使用從右至左書寫。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 判斷段落是否使用從右至左書寫。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 判斷段落是否使用拉丁斷行。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 判斷段落是否使用拉丁斷行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 判斷段落是否使用懸掛標點。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 判斷段落是否使用懸掛標點。 |
| [getMarginLeft()](#getMarginLeft--) | 傳回或設定段落的左邊距（不套用繼承）。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 傳回或設定段落的左邊距（不套用繼承）。 |
| [getMarginRight()](#getMarginRight--) | 傳回或設定段落的右邊距（不套用繼承）。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 傳回或設定段落的右邊距（不套用繼承）。 |
| [getIndent()](#getIndent--) | 傳回或設定段落的首行縮排/懸掛縮排（不套用繼承）。 |
| [setIndent(float value)](#setIndent-float-) | 傳回或設定段落的首行縮排/懸掛縮排（不套用繼承）。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 傳回或設定預設定位點大小（不套用繼承）。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 傳回或設定預設定位點大小（不套用繼承）。 |
| [getTabs()](#getTabs--) | 傳回段落的定位點設定。 |
| [getFontAlignment()](#getFontAlignment--) | 傳回或設定段落的字型對齊（不套用繼承）。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 傳回或設定段落的字型對齊（不套用繼承）。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 傳回段落的預設部份格式。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效段落格式資料。 |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

初始化 [ParagraphFormat](../../com.aspose.slides/paragraphformat) 類別的新執行個體。

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

傳回段落的項目符號格式。唯讀 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**傳回:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

傳回或設定段落的深度。值 0 表示未定義的值。讀寫 short 。

**傳回:**  
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

傳回或設定段落的深度。值 0 表示未定義的值。讀寫 short 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

傳回或設定段落的文字對齊（不套用繼承）。讀寫 [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // 實例化一個代表 PPTX 檔案的 Presentation 物件
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 存取第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 存取投影片中的第一個和第二個占位符，並將其類型轉換為 AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 更改兩個占位符中的文字
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 取得占位符的第一段落
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 將文字段落置中對齊
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // 將簡報寫入為 PPTX 檔案
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**  
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

傳回或設定段落的文字對齊（不套用繼承）。讀寫 [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // 實例化一個代表 PPTX 檔案的 Presentation 物件
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 存取第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 存取投影片中的第一個和第二個占位符，並將其類型轉換為 AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 更改兩個占位符中的文字
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 取得占位符的第一段落
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 將文字段落置中對齊
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // 將簡報寫入為 PPTX 檔案
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

傳回或設定段落基線之間的間距。正值表示百分比，負值表示點數大小。不套用繼承。讀寫 float 。

**傳回:**  
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

傳回或設定段落基線之間的間距。正值表示百分比，負值表示點數大小。不套用繼承。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

傳回或設定段落第一行前的間距（不套用繼承）。正值指定以字型大小的百分比計算的空白，負值指定以點數計算的空白。讀寫 float 。

**傳回:**  
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

傳回或設定段落第一行前的間距（不套用繼承）。正值指定以字型大小的百分比計算的空白，負值指定以點數計算的空白。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

傳回或設定段落最後一行後的間距（不套用繼承）。正值指定以字型大小的百分比計算的空白，負值指定以點數計算的空白。讀寫 float 。

**傳回:**  
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

傳回或設定段落最後一行後的間距（不套用繼承）。正值指定以字型大小的百分比計算的空白，負值指定以點數計算的空白。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

判斷段落是否使用東亞斷行。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

判斷段落是否使用東亞斷行。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

判斷段落是否使用從右至左書寫。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

判斷段落是否使用從右至左書寫。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

判斷段落是否使用拉丁斷行。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

判斷段落是否使用拉丁斷行。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

判斷段落是否使用懸掛標點。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

判斷段落是否使用懸掛標點。不套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

傳回或設定段落的左邊距（不套用繼承）。讀寫 float 。

**傳回:**  
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

傳回或設定段落的左邊距（不套用繼承）。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

傳回或設定段落的右邊距（不套用繼承）。讀寫 float 。

**傳回:**  
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

傳回或設定段落的右邊距（不套用繼承）。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

傳回或設定段落的首行縮排/懸掛縮排（不套用繼承）。懸掛縮排可使用負值。讀寫 float 。

**傳回:**  
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

傳回或設定段落的首行縮排/懸掛縮排（不套用繼承）。懸掛縮排可使用負值。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

傳回或設定預設定位點大小（不套用繼承）。讀寫 float 。

**傳回:**  
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

傳回或設定預設定位點大小（不套用繼承）。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

傳回段落的定位點設定。不套用繼承。唯讀 [ITabCollection](../../com.aspose.slides/itabcollection)。

**傳回:**  
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

傳回或設定段落的字型對齊（不套用繼承）。讀寫 [FontAlignment](../../com.aspose.slides/fontalignment)。

**傳回:**  
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

傳回或設定段落的字型對齊（不套用繼承）。讀寫 [FontAlignment](../../com.aspose.slides/fontalignment)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

傳回段落的預設部份格式。不套用繼承。唯讀 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**傳回:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

取得套用繼承後的有效段落格式資料。

--------------------

> ```
> 此範例示範取得一些有效的段落格式屬性。
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**傳回:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回:**  
long