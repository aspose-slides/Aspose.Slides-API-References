---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: 하이퍼링크 관리를 제공하며 추가 및 제거를 지원합니다.
type: docs
url: /ko/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

하이퍼링크 관리를 제공(추가, 제거)합니다.
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
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


클릭 시 외부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| url | java.lang.String | 하이퍼링크 URL. |

**반환값:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 객체 [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


클릭 시 내부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 대상 슬라이드. |

**반환값:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


클릭 시 하이퍼링크를 제거합니다.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


마우스 오버 시 외부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| url | java.lang.String | 하이퍼링크 URL. |

**반환값:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


마우스 오버 시 내부 하이퍼링크를 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | 대상 슬라이드. |

**반환값:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


마우스 오버 시 하이퍼링크를 제거합니다.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
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
| macroName | java.lang.String | 매크로의 이름 |

**반환값:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink 객체 [IHyperlink](../../com.aspose.slides/ihyperlink)