---
title: Slide
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 프레젠테이션에서 슬라이드를 나타냅니다.
type: docs
weight: 9960
url: /ko/aspose.slides/slide/
---
## Slide 클래스

프레젠테이션에서 슬라이드를 나타냅니다.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | 슬라이드의 배경을 반환합니다. 읽기 전용 [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | 슬라이드에 있는 ActiveX 컨트롤 컬렉션을 반환합니다. 읽기 전용 [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | 슬라이드의 사용자 지정 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | 포함된 하이퍼링크에 쉽게 접근할 수 있습니다. 읽기 전용 [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | 슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | 노트 슬라이드에 접근하고 추가 및 제거할 수 있습니다. 읽기 전용 [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation 인터페이스를 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | 슬라이드의 도형을 반환합니다. 읽기 전용 [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | 슬라이드의 ID를 반환합니다. 읽기 전용 UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | 슬라이드 번호를 반환합니다. [`Slides`](../presentation/slides) 컬렉션에서 슬라이드의 인덱스는 항상 SlideNumber - Presentation.FirstSlideNumber와 같습니다. 읽기/쓰기 Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | 지정된 슬라이드가 슬라이드 쇼 중에 어떻게 진행되는지에 대한 정보를 포함하는 Transition 객체를 반환합니다. 읽기 전용 [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | 오버라이드 테마 관리자를 반환합니다. 읽기 전용 [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | 애니메이션 타임라인 객체를 반환합니다. 읽기 전용 [`IAnimationTimeLine`](../ianimationtimeline). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | 이 슬라이드에 대한 유효한 테마를 반환합니다. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | 두 IBaseSlide 인스턴스가 같은지 여부를 결정합니다. 반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교 시 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: 날짜 플레이스홀더의 현재 날짜 값)는 고려되지 않습니다. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | 지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | 섬네일 이미지 객체를 반환합니다(실제 크기의 20%). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | 섬네일 이미지 객체를 반환합니다. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | 지정된 매개변수를 사용한 섬네일 TIFF 이미지 객체를 반환합니다. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | 지정된 크기의 섬네일 이미지 객체를 반환합니다. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | 사용자 정의 스케일링을 적용한 섬네일 이미지 객체를 반환합니다. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | 지정된 크기의 섬네일 이미지 객체를 반환합니다. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | 사용자 정의 스케일링을 적용한 섬네일 이미지 객체를 반환합니다. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | 특정 작성자가 추가한 모든 슬라이드 댓글을 반환합니다. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | 모든 허용된 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | 모든 허용된 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [Remove](../../aspose.slides/slide/remove)() | 프레젠테이션에서 슬라이드를 제거합니다. |
| [Reset](../../aspose.slides/slide/reset)() | LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 서식을 재설정합니다. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | 슬라이드 내용을 EMF 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | 슬라이드 내용을 SVG 파일로 저장합니다. |

### 참고

* 클래스 [BaseSlide](../baseslide)
* 인터페이스 [ISlide](../islide)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->