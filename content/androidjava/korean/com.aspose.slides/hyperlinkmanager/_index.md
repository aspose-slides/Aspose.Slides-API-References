---
title: HyperlinkManager
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 하이퍼링크 관리(추가 및 제거)를 제공합니다.
type: docs
url: /ko/com.aspose.slides/hyperlinkmanager/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

하이퍼링크 관리 제공(추가, 제거).
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | 클릭 시 외부 하이퍼링크를 설정합니다. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | 클릭 시 내부 하이퍼링크를 설정합니다. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | 클릭 시 하이퍼링크를 제거합니다. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | 마우스 오버 시 외부 하이퍼링크를 설정합니다. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | 마우스 오버 시 내부 하이퍼링크를 설정합니다. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | 마우스 오버 시 하이퍼링크를 제거합니다. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | 클릭 시 매크로 하이퍼링크를 설정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

클릭 시 외부 하이퍼링크를 설정합니다.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // PPTX를 나타내는 Presentation 클래스를 인스턴스화합니다.
>  Presentation pres = new Presentation();
>  try {
>      // 프레젠테이션의 첫 번째 슬라이드를 가져옵니다.
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 타입을 Rectangle로 설정한 AutoShape 객체를 추가합니다.
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // 모양을 AutoShape으로 캐스팅합니다.
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // AutoShape에 연결된 ITextFrame 속성에 접근합니다.
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 프레임에 텍스트를 추가합니다.
>      portion.setText("Aspose.Slides");
>      // 해당 텍스트 조각에 대한 하이퍼링크를 설정합니다.
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // PPTX 프레젠테이션을 저장합니다.
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| url | java.lang.String | 하이퍼링크 URL. |

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

클릭 시 내부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 대상 슬라이드. |

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 하이퍼링크.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

클릭 시 하이퍼링크를 제거합니다.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

마우스 오버 시 외부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| url | java.lang.String | 하이퍼링크 URL. |

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 하이퍼링크.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

마우스 오버 시 내부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 대상 슬라이드. |

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 하이퍼링크.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

마우스 오버 시 하이퍼링크를 제거합니다.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

클릭 시 매크로 하이퍼링크를 설정합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| macroName | java.lang.String | 매크로 이름 |

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - 하이퍼링크 객체 [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject