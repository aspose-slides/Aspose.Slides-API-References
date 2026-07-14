---
title: MasterNotesSlide
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 노트를 위한 마스터 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/masternotesslide/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)  
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

노트를 위한 마스터 슬라이드를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 마스터 노트 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getThemeManager()](#getThemeManager--) | 테마 관리자를 반환합니다. |
| [getNotesStyle()](#getNotesStyle--) | 노트 텍스트의 스타일을 반환합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 마스터 노트 슬라이드용 드로잉 가이드 컬렉션을 반환합니다. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 false를 반환합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 false를 반환합니다. 읽기/쓰기 boolean.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

마스터 노트 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**반환:**  
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

테마 관리자를 반환합니다. 읽기 전용 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**반환:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

노트 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

마스터 노트 슬라이드용 드로잉 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // 새로운 수평 드로잉 가이드를 슬라이드 중앙 아래에 추가합니다
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)