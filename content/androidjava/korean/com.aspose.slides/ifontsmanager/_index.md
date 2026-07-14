---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 프레젠테이션 전체에서 글꼴을 관리합니다.
type: docs
url: /ko/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

프레젠테이션 전체에서 글꼴을 관리합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | 렌더링 시 사용할 글꼴 대체 목록 읽기/쓰기 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | 렌더링 시 사용할 글꼴 대체 목록 읽기/쓰기 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | 폰트 대체 기능을 통한 적절한 대체를 관리하기 위한 사용자의 FontFallBack 규칙 컬렉션을 나타내며 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | 폰트 대체 기능을 통한 적절한 대체를 관리하기 위한 사용자의 FontFallBack 규칙 컬렉션을 나타내며 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | 프레젠테이션에 사용된 글꼴을 반환합니다 |
| [getSubstitutions()](#getSubstitutions--) | 프레젠테이션 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 지정된 슬라이드의 렌더링 중 교체될 글꼴에 대한 정보를 가져옵니다. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | 프레젠테이션에 포함된 글꼴을 반환합니다 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 포함된 글꼴을 제거합니다 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 포함된 글꼴을 추가합니다. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 포함된 글꼴을 추가합니다 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 프레젠테이션의 글꼴을 교체합니다 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 컬렉션에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 지정된 글꼴 스타일 및 글꼴 데이터에 대한 바이트 배열을 반환합니다. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 주어진 바이트 배열과 글꼴 이름으로부터 글꼴의 임베딩 수준을 결정합니다. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


렌더링 시 사용할 글꼴 대체 목록 읽기/쓰기 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**반환:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


렌더링 시 사용할 글꼴 대체 목록 읽기/쓰기 [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


폰트 대체 기능을 통한 적절한 대체를 관리하기 위한 사용자의 FontFallBack 규칙 컬렉션을 나타내며 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
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


**반환:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


폰트 대체 기능을 통한 적절한 대체를 관리하기 위한 사용자의 FontFallBack 규칙 컬렉션을 나타내며 읽기/쓰기 [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
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
public abstract IFontData[] getFonts()
```


프레젠테이션에 사용된 글꼴을 반환합니다

**반환:**
com.aspose.slides.IFontData[] - 글꼴 배열
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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


**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 모든 글꼴 대체 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 컬렉션.
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


지정된 슬라이드의 렌더링 중 교체될 글꼴에 대한 정보를 가져옵니다.

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
| slides | int[] | 1부터 시작하는 슬라이드 인덱스 배열로, 해당 슬라이드의 글꼴 대체 정보를 검색합니다. |

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 지정된 슬라이드에 대한 모든 글꼴 대체 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) 컬렉션.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


프레젠테이션에 포함된 글꼴을 반환합니다

**반환:**
com.aspose.slides.IFontData[] - 포함된 글꼴 IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


포함된 글꼴을 제거합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 글꼴 데이터 객체 [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


포함된 글꼴을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 글꼴 데이터 객체 [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | 포함된 글꼴 규칙 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

글꼴을 복사할 때 대부분의 글꼴이 저작권이 있다는 점을 명심하십시오. 먼저 글꼴의 라이선스를 확인하고 다른 기기로 자유롭게 이전할 수 있는지 확인하십시오. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


포함된 글꼴을 추가합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | byte[] | 글꼴 데이터  byte[]  |
| embedFontRule | int | 포함된 글꼴 규칙 [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

글꼴을 추가할 때 대부분의 글꼴이 저작권이 있다는 점을 명심하십시오. 먼저 글꼴의 라이선스를 확인하고 다른 기기로 자유롭게 이전할 수 있는지 확인하십시오. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


프레젠테이션의 글꼴을 교체합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 원본 글꼴 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 대상 글꼴 |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 글꼴 대체 정보 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) 컬렉션에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | 글꼴 대체 정보 컬렉션 |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


지정된 글꼴 스타일 및 글꼴 데이터에 대한 바이트 배열을 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // 프레젠테이션에 사용된 모든 글꼴을 가져옵니다
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // 프레젠테이션에서 첫 번째 글꼴의 일반 스타일을 나타내는 바이트 배열을 가져옵니다
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 해당 글꼴에 대한 정보를 포함하는 글꼴 데이터 객체 [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | 데이터를 검색할 글꼴 스타일 [FontStyleType](../../com.aspose.slides/fontstyletype). |

**반환:**
byte[] - 지정된 글꼴 스타일에 대한 글꼴 데이터를 포함하는 바이트 배열입니다. 글꼴 데이터나 스타일을 찾을 수 없으면 null을 반환합니다.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


주어진 바이트 배열과 글꼴 이름으로부터 글꼴의 임베딩 수준을 결정합니다.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // 프레젠테이션에 사용된 모든 글꼴을 가져옵니다
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // 프레젠테이션에서 첫 번째 글꼴의 일반 스타일을 나타내는 바이트 배열을 가져옵니다
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // 글꼴의 임베딩 수준을 결정합니다
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontBytes | byte[] | 글꼴 데이터를 포함한 바이트 배열. |
| fontName | java.lang.String | 글꼴 이름. |

**반환:**
int - 지정된 글꼴의 임베딩 수준.