---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /zh/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

管理整个演示文稿中的字体。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 在渲染时使用的字体替代，读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 在渲染时使用的字体替代，读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体集合并进行适当的替代，读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体集合并进行适当的替代，读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | 返回演示文稿中使用的字体 |
| [getSubstitutions()](#getSubstitutions--) | 获取将在演示文稿渲染时被替换的字体信息。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 获取在渲染指定幻灯片时将被替换的字体信息。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 返回嵌入在演示文稿中的字体 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 删除嵌入的字体 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 添加嵌入的字体。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 添加嵌入的字体 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 在演示文稿中替换字体 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 中提供的信息在演示文稿中替换字体 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 使用 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 集合中提供的信息在演示文稿中替换字体 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 检索表示指定字体样式和字体数据的字节数组。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 根据给定的字节数组和字体名称确定字体的嵌入级别。 |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


在渲染时使用的字体替代，读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**返回：**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


在渲染时使用的字体替代，读/写 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |
### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体集合并进行适当的替代，读/写 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 从 FontsManager 获取空的或预先初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或者 
>      // 初始化规则集合的新实例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 通过 FontsManager 用新集合替换现有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```
Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // 从 FontsManager 获取空的或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 或者 
>      // 初始化规则集合的新实例
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 向集合添加规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 并在 FontsManager 中用新集合替换现有集合 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Returns the fonts used in the presentation

**Returns:**
com.aspose.slides.IFontData[] - An array of fonts
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```
Gets the information about fonts that will be replaced on the presentation's rendering.

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

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collection of all fonts substitution [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```
Gets the information about fonts that will be replaced during rendering of the specified slides.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slides | int[] | An array of slide indexes for which to retrieve font substitution information, starting from 1. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A collection of all font substitutions ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) for the specified slides.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Returns the fonts embedded in the presentation

**Returns:**
com.aspose.slides.IFontData[] - Embedded fonts IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Removes the embedded font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font data object [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Adds the embedded font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font data object [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Embedded font rule [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Adds the embedded font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | byte[] | Font data  byte[]  |
| embedFontRule | int | Embedded font rule [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Replace font in presentation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```
Replace font in presentation using information provided in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Font substitution info |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Replace font in presentation using information provided in collection of [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Font substitution info collection |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Retrieves the byte array representing the font data for a specified font style and font data.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 检索演示文稿中使用的所有字体
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 获取演示文稿中第一个字体的常规样式对应的字节数组
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | The font data object containing the information about the font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | The style of the font for which the data is to be retrieved [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Returns:**
byte[] - A byte array containing the font data for the specified font style. If the font data or style is not found, returns null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)


根据给定的字节数组和字体名称确定字体的嵌入级别。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Retrieve all fonts used in the presentation
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Get the byte array representing the regular style of the first font in the presentation
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Determine the embedding level of the font
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontBytes | byte[] | 包含字体数据的字节数组。 |
| fontName | java.lang.String | 字体的名称。 |

**返回：**
int - 指定字体的嵌入级别。