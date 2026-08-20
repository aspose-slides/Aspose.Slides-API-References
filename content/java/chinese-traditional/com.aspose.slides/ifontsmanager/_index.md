---
title: IFontsManager
second_title: Aspose.Slides for Java API 參考
description: 管理整個簡報中的字型。
type: docs
url: /zh-hant/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

管理整個簡報中的字型。
## 方法

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 於呈現時使用的字型替代（Read/write）[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 於呈現時使用的字型替代（Read/write）[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 表示使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理（Read/write）[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 表示使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理（Read/write）[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 傳回簡報中使用的字型 |
| [getSubstitutions()](#getSubstitutions--) | 取得在簡報呈現時將被取代的字型資訊。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 取得在指定投影片的呈現過程中將被取代的字型資訊。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 傳回簡報中嵌入的字型 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 移除嵌入的字型 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 新增嵌入的字型。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 新增嵌入的字型 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 取代簡報中的字型 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 提供的資訊取代簡報中的字型 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合提供的資訊取代簡報中的字型 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 取得表示指定字型樣式與字型資料之字型資料的位元組陣列。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 判斷給定位元組陣列與字型名稱之字型嵌入層級。 |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

於呈現時使用的字型替代（Read/write）[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**傳回:**  
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

於呈現時使用的字型替代（Read/write）[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

表示使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理（Read/write）[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 並在 FontsManager 中用新集合取代現有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**  
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

表示使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理（Read/write）[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或 
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 並在 FontsManager 中用新集合取代現有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

傳回簡報中使用的字型

**傳回:**  
com.aspose.slides.IFontData[] - 字型陣列

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

取得在簡報呈現時將被取代的字型資訊。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字型替代的集合 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)。

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

取得在指定投影片的呈現過程中將被取代的字型資訊。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| slides | int[] | 一個包含要取得字型替代資訊之投影片索引的陣列，索引值從 1 開始。 |

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 指定投影片的所有字型替代集合 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))。

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

傳回簡報中嵌入的字型

**傳回:**  
com.aspose.slides.IFontData[] - 嵌入字型 IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

移除嵌入的字型

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字型資料物件 [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

新增嵌入的字型。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字型資料物件 [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | 嵌入字型規則 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

請留意，複製任何字型時，大多數字型皆受版權保護。請先確認字型的授權，並確定其可自由轉移至其他機器。

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

新增嵌入的字型

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | byte[] | 字型資料  byte[]  |
| embedFontRule | int | 嵌入字型規則 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

請留意，新增任何字型時，大多數字型皆受版權保護。請先確認字型的授權，並確定其可自由轉移至其他機器。

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

取代簡報中的字型

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 提供的資訊取代簡報中的字型

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 字型替代資訊 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合提供的資訊取代簡報中的字型

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 字型替代資訊集合 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

取得表示指定字型樣式與字型資料之字型資料的位元組陣列。

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 取得簡報中使用的所有字型
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型之常規樣式的位元組陣列
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 包含字型資訊的字型資料物件 [IFontData](../../com.aspose.slides/ifontdata)。 |
| fontStyle | int | 要取得資料的字型樣式 [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**傳回:**  
byte[] - 包含指定字型樣式之字型資料的位元組陣列。若未找到字型資料或樣式，則傳回 null。

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

判斷給定位元組陣列與字型名稱之字型嵌入層級。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 取得簡報中使用的所有字型
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型之常規樣式的位元組陣列
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // 判斷字型的嵌入層級
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | 包含字型資料的位元組陣列。 |
| fontName | java.lang.String | 字型的名稱。 |

**傳回:**  
int - 指定字型的嵌入層級。