---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Manages fonts across the presentation.
## Methods

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Font substitutions to use when rendering Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Font substitutions to use when rendering Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Returns the fonts used in the presentation |
| [getSubstitutions()](#getSubstitutions--) | Gets the information about fonts that will be replaced on the presentation's rendering. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Gets the information about fonts that will be replaced during rendering of the specified slides. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Returns the fonts embedded in the presentation |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Removes the embedded font |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Adds the embedded font. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Adds the embedded font |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Replace font in presentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Replace font in presentation using information provided in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Replace font in presentation using information provided in collection of [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Retrieves the byte array representing the font data for a specified font style and font data. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determines the embedding level of a font from the given byte array and font name. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Font substitutions to use when rendering Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Returns:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Font substitutions to use when rendering Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // initialization of new instance of rules collection
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // and replacing of existing collection by the new one in FontsManager 
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
>      // Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // initialization of new instance of rules collection
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // and replacing of existing collection by the new one in FontsManager 
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
>      // Retrieve all fonts used in the presentation
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Get the byte array representing the regular style of the first font in the presentation
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
```


Determines the embedding level of a font from the given byte array and font name.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | The byte array containing the font data. |
| fontName | java.lang.String | The name of the font. |

**Returns:**
int - The embedding level of the specified font.
