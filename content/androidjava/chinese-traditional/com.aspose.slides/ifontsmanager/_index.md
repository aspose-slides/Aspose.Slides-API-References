---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 管理簡報中的字型。
type: docs
url: /zh-hant/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

管理簡報中的字型。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 在渲染時使用的字型替代規則，讀寫 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 在渲染時使用的字型替代規則，讀寫 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 代表使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理，讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 代表使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理，讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 返回簡報中使用的字型 |
| [getSubstitutions()](#getSubstitutions--) | 取得在簡報渲染時將被替換的字型資訊 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 取得在指定投影片渲染期間將被替換的字型資訊 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 返回嵌入於簡報中的字型 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 移除嵌入的字型 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 新增嵌入的字型。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 新增嵌入的字型 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 在簡報中取代字型 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 提供的資訊在簡報中取代字型 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合提供的資訊在簡報中取代字型 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 取得指定字型樣式及字型資料的位元組陣列 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 根據給定的位元組陣列與字型名稱判斷字型的嵌入層級 |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

在渲染時使用的字型替代規則，讀寫 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**返回值：**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

在渲染時使用的字型替代規則，讀寫 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

代表使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理，讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 從 FontsManager 取得空的或已預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 並在 FontsManager 中以新集合取代現有集合
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

代表使用者的 FontFallBack 規則集合，用於透過備援功能正確替代字型的管理，讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 從 FontsManager 取得空的或已預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或 
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合中添加規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 並在 FontsManager 中以新集合取代現有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

返回簡報中使用的字型

**返回值：**
com.aspose.slides.IFontData[] - 字型陣列

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

取得在簡報渲染時將被替換的字型資訊。

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


**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字型替代的集合 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)。

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

取得在指定投影片渲染期間將被替換的字型資訊。

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


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| slides | int[] | 要檢索字型替代資訊的投影片索引陣列，從 1 開始。 |

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 針對指定投影片的所有字型替代集合 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))。

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

返回嵌入於簡報中的字型

**返回值：**
com.aspose.slides.IFontData[] - 嵌入的字型 IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

移除嵌入的字型

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字型資料物件 [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

新增嵌入的字型。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字型資料物件 [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | 嵌入字型規則 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

請注意，複製任何字型時大多數字型皆受版權保護。請先確認字型的授權，並驗證其可以自由轉移至其他機器。 |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

新增嵌入的字型

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontData | byte[] | 字型資料 byte[] |
| embedFontRule | int | 嵌入字型規則 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

請注意，新增任何字型時大多數字型皆受版權保護。請先確認字型的授權，並驗證其可以自由轉移至其他機器。 |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

在簡報中取代字型

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 提供的資訊在簡報中取代字型

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 字型替代資訊 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合提供的資訊在簡報中取代字型

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 字型替代資訊集合 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

取得指定字型樣式及字型資料的位元組陣列。

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 取得簡報中使用的全部字型
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型的常規樣式之位元組陣列
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 包含字型資訊的字型資料物件 [IFontData](../../com.aspose.slides/ifontdata)。 |
| fontStyle | int | 要取得資料的字型樣式 [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**返回值：**
byte[] - 包含指定字型樣式字型資料的位元組陣列。如果找不到字型資料或樣式，則返回 null。

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

根據給定的位元組陣列與字型名稱判斷字型的嵌入層級。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 取得簡報中使用的全部字型
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型的常規樣式之位元組陣列
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // 判斷該字型的嵌入層級
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontBytes | byte[] | 包含字型資料的位元組陣列。 |
| fontName | java.lang.String | 字型名稱。 |

**返回值：**
int - 指定字型的嵌入層級。