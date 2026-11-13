---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /ko/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

프레젠테이션 전체에 걸쳐 글꼴을 관리합니다.
## 메서드

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 렌더링 시 사용할 글꼴 대체 목록 Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 렌더링 시 사용할 글꼴 대체 목록 Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | fallback 기능을 사용한 적절한 대체를 위해 글꼴 컬렉션을 관리하는 FontFallBack 규칙 사용자의 컬렉션을 나타냅니다 Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | fallback 기능을 사용한 적절한 대체를 위해 글꼴 컬렉션을 관리하는 FontFallBack 규칙 사용자의 컬렉션을 나타냅니다 Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | 프레젠테이션에서 사용된 글꼴을 반환합니다 |
| [getSubstitutions()](#getSubstitutions--) | 프레젠테이션 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 지정된 슬라이드 렌더링 중 교체될 글꼴에 대한 정보를 가져옵니다. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 프레젠테이션에 포함된 글꼴을 반환합니다 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 포함된 글꼴을 제거합니다 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 포함된 글꼴을 추가합니다. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 포함된 글꼴을 추가합니다 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 프레젠테이션에서 글꼴을 교체합니다 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | 프레젠테이션에서 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)에 제공된 정보를 사용하여 글꼴을 교체합니다 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | 프레젠테이션에서 [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 컬렉션에 제공된 정보를 사용하여 글꼴을 교체합니다 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 지정된 글꼴 스타일 및 글꼴 데이터에 대한 바이트 배열을 가져옵니다. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 주어진 바이트 배열과 글꼴 이름으로부터 글꼴의 임베딩 수준을 결정합니다. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | 같은 글꼴 이름과 스타일을 가진 포함된 글꼴보다 등록된 글꼴을 우선 사용할지 지정합니다. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | 같은 글꼴 이름과 스타일을 가진 포함된 글꼴보다 등록된 글꼴을 우선 사용할지 지정합니다. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Font substitutions to use when rendering Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**반환값:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Font substitutions to use when rendering Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**매개변수:**
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
>      // FontsManager에서 비어 있거나 사전에 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 또는
>      // 규칙 컬렉션의 새 인스턴스 초기화
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // FontsManager에서 기존 컬렉션을 새 컬렉션으로 교체
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
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
>      // FontsManager에서 비어 있거나 사전에 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 또는 
>      // 규칙 컬렉션의 새 인스턴스 초기화
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 그리고 FontsManager에서 기존 컬렉션을 새 컬렉션으로 교체 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```


Returns the fonts used in the presentation

**반환값:**
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


**반환값:**
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


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| slides | int[] | An array of slide indexes for which to retrieve font substitution information, starting from 1. |

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A collection of all font substitutions ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) for the specified slides.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Returns the fonts embedded in the presentation

**반환값:**
com.aspose.slides.IFontData[] - Embedded fonts IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


Removes the embedded font

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font data object [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Adds the embedded font.

**매개변수:**
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

**매개변수:**
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

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


Replace font in presentation using information provided in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Font substitution info |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


Replace font in presentation using information provided in collection of [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**매개변수:**
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
>      // 프레젠테이션에서 사용된 모든 글꼴을 가져옵니다
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 프레젠테이션에서 첫 번째 글꼴의 Regular 스타일을 나타내는 바이트 배열을 가져옵니다
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | The font data object containing the information about the font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | The style of the font for which the data is to be retrieved [FontStyleType](../../com.aspose.slides/fontstyletype). |

**반환값:**
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
>      // 프레젠테이션에서 사용된 모든 글꼴을 가져옵니다
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 프레젠테이션에서 첫 번째 글꼴의 Regular 스타일을 나타내는 바이트 배열을 가져옵니다
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // 글꼴의 임베딩 수준을 결정합니다
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | The byte array containing the font data. |
| fontName | java.lang.String | The name of the font. |

**반환값:**
int - The embedding level of the specified font.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```


Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style. When enabled, matching embedded fonts are temporarily replaced with corresponding registered fonts during export.

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

Default is  **false** .

**반환값:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```


Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style. When enabled, matching embedded fonts are temporarily replaced with corresponding registered fonts during export.

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

Default is  **false** .

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |