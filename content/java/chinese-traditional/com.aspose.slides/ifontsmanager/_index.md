---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: 管理整個簡報的字型。
type: docs
url: /zh-hant/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

管理簡報中的字型。
## 方法

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 在渲染時使用的字型替代方案 Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 在渲染時使用的字型替代方案 Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 表示使用者的 FontFallBack 規則集合，用於通過回退功能管理字型集合，以正確替代，Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 表示使用者的 FontFallBack 規則集合，用於通過回退功能管理字型集合，以正確替代，Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 返回簡報中使用的字型 |
| [getSubstitutions()](#getSubstitutions--) | 取得在簡報渲染時將被取代的字型資訊。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 取得在指定投影片渲染期間將被取代的字型資訊。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 返回嵌入於簡報中的字型 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 移除嵌入的字型 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 新增嵌入的字型。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 新增嵌入的字型 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 在簡報中取代字型 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 中提供的資訊在簡報中取代字型 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合中提供的資訊在簡報中取代字型 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 取得指定字型樣式與字型資料的位元組陣列，代表字型資料。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 根據給定的位元組陣列和字型名稱判定字型的嵌入層級。 |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | 指定是否應該優先使用已註冊的字型，而非同名稱與樣式的嵌入字型。 |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | 指定是否應該優先使用已註冊的字型，而非同名稱與樣式的嵌入字型。 |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

在渲染時使用的字型替代方案 Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**傳回：**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

在渲染時使用的字型替代方案 Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

表示使用者的 FontFallBack 規則集合，用於通過回退功能管理字型集合，以正確替代，Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 取得來自 FontsManager 的空或已預初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 並在 FontsManager 中以新集合取代現有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

表示使用者的 FontFallBack 規則集合，用於通過回退功能管理字型集合，以正確替代，Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 取得來自 FontsManager 的空或已預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或 
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 並在 FontsManager 中以新集合取代現有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

返回簡報中使用的字型

**傳回：**
com.aspose.slides.IFontData[] - 字型陣列
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

取得在簡報渲染時將被取代的字型資訊。

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


**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字型替代的集合 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)。
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

取得在指定投影片渲染期間將被取代的字型資訊。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slides | int[] | 一個包含投影片索引的陣列，用以取得字型替代資訊，索引從 1 開始。 |

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字型替代的集合 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) 用於指定的投影片。
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

返回嵌入於簡報中的字型

**傳回：**
com.aspose.slides.IFontData[] - 嵌入的字型 IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

移除嵌入的字型

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字型資料物件 [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

新增嵌入的字型。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 字型資料物件 [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | 嵌入字型規則 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

請記住，複製字型時大多數字型都有版權。請先確認字型的授權，並確保其可以自由轉移至其他機器。 |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

新增嵌入的字型

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | byte[] | 字型資料  byte[]  |
| embedFontRule | int | 嵌入字型規則 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

請記住，複製字型時大多數字型都有版權。請先確認字型的授權，並確保其可以自由轉移至其他機器。 |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

在簡報中取代字型

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 中提供的資訊在簡報中取代字型

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 字型替代資訊 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合中提供的資訊在簡報中取代字型

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 字型替代資訊集合 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

取得表示指定字型樣式與字型資料的位元組陣列。

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 取得簡報中使用的所有字型
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型的常規樣式所對應的位元組陣列
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 包含字型資訊的字型資料物件 [IFontData](../../com.aspose.slides/ifontdata)。 |
| fontStyle | int | 要取得資料的字型樣式 [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**傳回：**
byte[] - 包含指定字型樣式資料的位元組陣列。如果找不到字型資料或樣式，則返回 null。
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

根據給定的位元組陣列和字型名稱判定字型的嵌入層級。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 取得簡報中使用的所有字型
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型的常規樣式所對應的位元組陣列
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // 判斷字型的嵌入層級
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontBytes | byte[] | 包含字型資料的位元組陣列。 |
| fontName | java.lang.String | 字型的名稱。 |

**傳回：**
int - 指定字型的嵌入層級。
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

指定是否應該優先使用已註冊的字型，而非同名稱與樣式的嵌入字型。啟用時，匹配的嵌入字型在匯出期間會暫時被相應的已註冊字型取代。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設為 **false** 。

**傳回：**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

指定是否應該優先使用已註冊的字型，而非同名稱與樣式的嵌入字型。啟用時，匹配的嵌入字型在匯出期間會暫時被相應的已註冊字型取代。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設為 **false** 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |