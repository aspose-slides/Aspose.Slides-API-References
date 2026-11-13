---
title: FontsManager
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션 전체에서 글꼴을 관리합니다.
type: docs
url: /ko/com.aspose.slides/fontsmanager/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)  
```
public class FontsManager implements IFontsManager
```

프레젠테이션 전체에서 글꼴을 관리합니다.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // 프레젠테이션 로드
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 대체될 원본 글꼴 로드
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
>      // 프레젠테이션 저장
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 렌더링 시 사용할 글꼴 대체. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 렌더링 시 사용할 글꼴 대체. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 사용자의 FontFallBack 규칙 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 사용자의 FontFallBack 규칙 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | 프레젠테이션에서 사용된 글꼴을 반환합니다. |
| [getSubstitutions()](#getSubstitutions--) | 프레젠테이션 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 지정된 슬라이드 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | 동일한 글꼴 이름 및 스타일을 가진 임베디드 글꼴보다 등록된 글꼴을 우선 사용할지 지정합니다. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | 동일한 글꼴 이름 및 스타일을 가진 임베디드 글꼴보다 등록된 글꼴을 우선 사용할지 지정합니다. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 프레젠테이션에 임베디드된 글꼴을 반환합니다. |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 임베디드 글꼴을 제거합니다. |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 임베디드 글꼴을 추가합니다. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 임베디드 글꼴을 추가합니다. |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 프레젠테이션에서 글꼴을 교체합니다. |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule)에서 제공된 정보를 사용하여 프레젠테이션에서 글꼴을 교체합니다. |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) 컬렉션에서 제공된 정보를 사용하여 프레젠테이션에서 글꼴을 교체합니다. |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 지정된 글꼴 스타일 및 글꼴 데이터에 대한 바이트 배열을 가져옵니다. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 주어진 바이트 배열 및 글꼴 이름으로부터 글꼴의 임베딩 수준을 결정합니다. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

렌더링 시 사용할 글꼴 대체. 읽기/쓰기 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**반환값:**  
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

렌더링 시 사용할 글꼴 대체. 읽기/쓰기 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

사용자의 FontFallBack 규칙 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager에서 비어 있거나 미리 초기화된 규칙 컬렉션을 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 또는
>      // 새로운 규칙 컬렉션 인스턴스 초기화
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // FontsManager에서 기존 컬렉션을 새로운 컬렉션으로 교체
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
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

사용자의 FontFallBack 규칙 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager에서 비어 있거나 미리 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // 컬렉션에 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // 또는
>      // 규칙 컬렉션 새 인스턴스 초기화
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


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

프레젠테이션에서 사용된 글꼴을 반환합니다.

**반환값:**  
com.aspose.slides.IFontData[] - 글꼴 배열

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

프레젠테이션 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 모든 글꼴 대체 컬렉션 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

지정된 슬라이드 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| slides | int[] | 글꼴 대체 정보를 가져올 슬라이드 인덱스 배열(1부터 시작). |

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 지정된 슬라이드에 대한 모든 글꼴 대체 컬렉션 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

동일한 글꼴 이름 및 스타일을 가진 임베디드 글꼴보다 등록된 글꼴을 우선 사용할지 지정합니다. 활성화하면 내보내기 중에 일치하는 임베디드 글꼴이 일시적으로 해당 등록된 글꼴로 교체됩니다.

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

**기본값은 **false**입니다.**

**반환값:**  
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

동일한 글꼴 이름 및 스타일을 가진 임베디드 글꼴보다 등록된 글꼴을 우선 사용할지 지정합니다. 활성화하면 내보내기 중에 일치하는 임베디드 글꼴이 일시적으로 해당 등록된 글꼴로 교체됩니다.

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

**기본값은 **false**입니다.**

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

프레젠테이션에 임베디드된 글꼴을 반환합니다.

**반환값:**  
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

임베디드 글꼴을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

임베디드 글꼴을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

임베디드 글꼴을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

프레젠테이션에서 글꼴을 교체합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 원본 글꼴 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 대상 글꼴 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule)에서 제공된 정보를 사용하여 프레젠테이션에서 글꼴을 교체합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 글꼴 대체 정보 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) 컬렉션에서 제공된 정보를 사용하여 프레젠테이션에서 글꼴을 교체합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 글꼴 대체 규칙 컬렉션 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

지정된 글꼴 스타일 및 글꼴 데이터에 대한 바이트 배열을 가져옵니다.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 프레젠테이션에서 사용된 모든 글꼴을 가져옵니다
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 프레젠테이션의 첫 번째 글꼴의 일반 스타일을 나타내는 바이트 배열을 가져옵니다
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 글꼴에 대한 정보를 포함하는 글꼴 데이터 객체 [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | 데이터를 조회할 글꼴 스타일 [FontStyleType](../../com.aspose.slides/fontstyletype). |

**반환값:**  
byte[] - 지정된 글꼴 스타일에 대한 글꼴 데이터를 포함하는 바이트 배열. 글꼴 데이터나 스타일을 찾을 수 없으면 null을 반환합니다.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

주어진 바이트 배열 및 글꼴 이름으로부터 글꼴의 임베딩 수준을 결정합니다.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 프레젠테이션에서 사용된 모든 글꼴을 가져옵니다
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 프레젠테이션의 첫 번째 글꼴의 일반 스타일을 나타내는 바이트 배열을 가져옵니다
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // 글꼴의 임베딩 수준을 결정합니다
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontBytes | byte[] | 글꼴 데이터를 포함하는 바이트 배열. |
| fontName | java.lang.String | 글꼴 이름. |

**반환값:**  
int - 지정된 글꼴의 임베딩 수준.