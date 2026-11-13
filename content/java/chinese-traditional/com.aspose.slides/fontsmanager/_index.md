---
title: FontsManager
second_title: Aspose.Slides for Java API 參考
description: 管理簡報中的字型。
type: docs
url: /zh-hant/com.aspose.slides/fontsmanager/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

管理簡報中的字型。

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // 載入簡報
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 載入要被取代的來源字型
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // 儲存簡報
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 渲染時使用的字型替代。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 渲染時使用的字型替代。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 代表使用者的 FontFallBack 規則集合，用於管理字型集合以透過回退功能正確替代。讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 代表使用者的 FontFallBack 規則集合，用於管理字型集合以透過回退功能正確替代。讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 返回簡報中使用的字型 |
| [getSubstitutions()](#getSubstitutions--) | 取得簡報渲染時將被替換的字型資訊。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 取得指定投影片渲染期間將被替換的字型資訊。 |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | 指定是否應優先使用已註冊的字型而非具有相同字型名稱和樣式的嵌入字型。 |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | 指定是否應優先使用已註冊的字型而非具有相同字型名稱和樣式的嵌入字型。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 返回嵌入在簡報中的字型 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 移除嵌入的字型 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 新增嵌入的字型 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 新增嵌入的字型 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 取代簡報中的字型 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 提供的資訊取代簡報中的字型 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 集合提供的資訊取代簡報中的字型 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 取得代表指定字型樣式與字型資料之字型資料的位元組陣列。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 根據給定的位元組陣列與字型名稱判斷字型的嵌入層級。 |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

渲染時使用的字型替代。讀寫 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**返回:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

渲染時使用的字型替代。讀寫 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

代表使用者的 FontFallBack 規則集合，用於管理字型集合以透過回退功能正確替代。讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或 
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 在 FontsManager 中以新集合取代現有的集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

代表使用者的 FontFallBack 規則集合，用於管理字型集合以透過回退功能正確替代。讀寫 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或 
>      // 初始化規則集合的新實例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 將規則加入集合
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 在 FontsManager 中以新集合取代現有的集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

返回簡報中使用的字型

**返回:**
com.aspose.slides.IFontData[] - 字型陣列
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

取得簡報渲染時將被替換的字型資訊。

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


**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有字型替代的集合 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)。
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

取得指定投影片渲染期間將被替換的字型資訊。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slides | int[] | 要檢索字型替代資訊的投影片索引陣列，起始值為 1。 |

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 所有指定投影片的字型替代集合 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))。
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

指定是否應優先使用已註冊的字型而非具有相同字型名稱和樣式的嵌入字型。啟用時，匹配的嵌入字型會在匯出期間暫時被相應的已註冊字型取代。

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

預設為 **false**。

**返回:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

指定是否應優先使用已註冊的字型而非具有相同字型名稱和樣式的嵌入字型。啟用時，匹配的嵌入字型會在匯出期間暫時被相應的已註冊字型取代。

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

預設為 **false**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

返回嵌入在簡報中的字型

**返回:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

移除嵌入的字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

新增嵌入的字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

新增嵌入的字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

取代簡報中的字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 原始字型 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 提供的資訊取代簡報中的字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 字型替代資訊 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

使用 [FontSubstRule](../../com.aspose.slides/fontsubstrule) 集合提供的資訊取代簡報中的字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 字型替代規則集合 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

取得代表指定字型樣式與字型資料之字型資料的位元組陣列。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 包含字型 [IFontData](../../com.aspose.slides/ifontdata) 資訊的字型資料物件。 |
| fontStyle | int | 要取得資料的字型樣式 [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**返回:**
byte[] - 位元組陣列，包含指定字型樣式的字型資料。如果找不到字型資料或樣式，返回 null。
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

根據給定的位元組陣列與字型名稱判斷字型的嵌入層級。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 取得簡報中使用的全部字型
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 取得簡報中第一個字型的常規樣式之位元組陣列
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // 判斷字型的嵌入層級
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontBytes | byte[] | 包含字型資料的位元組陣列。 |
| fontName | java.lang.String | 字型的名稱。 |

**返回:**
int - 指定字型的嵌入層級。