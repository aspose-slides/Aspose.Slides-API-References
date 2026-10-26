---
title: PortionFormat
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 이 클래스는 텍스트 구간 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/portionformat/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**All Implemented Interfaces:**  
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)  
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

이 클래스는 텍스트 구간 서식 속성을 포함합니다. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //프레젠테이션 파일을 나타내는 프레젠테이션 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides는 이러한 특수 식별자를 사용합니다 (PowerPoint에서 사용되는 것과 유사합니다):
>      // +mn-lt - 본문 폰트 라틴어 (소 라틴 폰트)
>      // +mj-lt -Heading 폰트 라틴어 (메이저 라틴 폰트)
>      // +mn-ea - 본문 폰트 동아시아 (소 동아시아 폰트)
>      // +mj-ea - 본문 폰트 동아시아 (소 동아시아 폰트)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

이 클래스는 특정 구간에 정의된 텍스트 구간 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으며, 대부분의 경우 “undefined”(정의되지 않음)이라는 값을 얻게 됩니다.

상속된 값을 포함한 실제 서식 매개변수 값을 얻으려면 [getEffective](../../com.aspose.slides/portionformat\#getEffective) 메서드를 사용해야 하며, 이는 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 인스턴스를 반환합니다.

## Constructors

| Constructor | Description |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | 새로운 [PortionFormat](../../com.aspose.slides/portionformat) 클래스 인스턴스를 초기화합니다. |

## Methods

| Method | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 북마크 식별자를 반환하거나 설정합니다. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 북마크 식별자를 반환하거나 설정합니다. |
| [getSmartTagClean()](#getSmartTagClean--) | 스마트 태그를 정리해야 하는지 여부를 결정합니다. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 스마트 태그를 정리해야 하는지 여부를 결정합니다. |
| [getHyperlinkClick()](#getHyperlinkClick--) | 마우스 클릭을 위해 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 마우스 클릭을 위해 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 마우스 오버를 위해 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 마우스 오버를 위해 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [getHyperlinkManager()](#getHyperlinkManager--) | 하이퍼링크 관리자. |
| [getEffective()](#getEffective--) | 상속이 적용된 실제 구간 서식 데이터를 가져옵니다. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

새로운 [PortionFormat](../../com.aspose.slides/portionformat) 클래스 인스턴스를 초기화합니다.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

북마크 식별자를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

북마크 식별자를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

마우스 클릭을 위해 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

마우스 클릭을 위해 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

마우스 오버를 위해 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

마우스 오버를 위해 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

하이퍼링크 관리자. 읽기 전용 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**반환:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

상속이 적용된 실제 구간 서식 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - 하나의 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).