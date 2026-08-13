---
title: IMasterSlide
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션의 마스터 슬라이드를 나타냅니다.
type: docs
weight: 2926
url: /ko/aspose.slides/imasterslide/
---
## IMasterSlide 클래스


프레젠테이션에서 마스터 슬라이드를 나타냅니다.

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | 현재 슬라이드를 기반으로 새 마스터 슬라이드를 만들고 외부 테마를 적용한 후, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | 이 테마 적용 가능한 객체에 대한 유효한 테마를 반환합니다. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | 두 [IBaseSlide](../ibaseslide/) 인스턴스가 같은지 여부를 결정합니다. 반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 모양, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 SlideId와 같은 고유 식별자 값이나 Date [Placeholder](../placeholder/)에 대한 현재 날짜 값과 같은 동적 콘텐츠는 고려되지 않습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | 지정된 대체 텍스트를 가진 도형의 첫 번째 등장 위치를 찾습니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | 슬라이드의 배경을 반환합니다. 읽기 전용 [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | 본문 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | 지정된 인덱스에 있는 ActiveX 컨트롤을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다. 읽기 전용 [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | 슬라이드의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | 이 마스터 슬라이드에 종속되는 슬라이드가 하나 이상 존재하면 true를 반환합니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | 마스터 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | 포함된 하이퍼링크에 대한 쉬운 접근을 제공합니다. 읽기 전용 [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | 지정된 인덱스에 있는 이 마스터 슬라이드의 하위 레이아웃 슬라이드를 반환합니다. 읽기 전용 [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | 이 마스터 슬라이드의 하위 레이아웃 슬라이드 컬렉션을 반환합니다. 읽기 전용 [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | 슬라이드의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | 다른 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| virtual **bool** [get_Preserve](./get_preserve/)() | 해당 마스터 뒤의 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: [Aspose.Slides](../)는 사용되지 않는 마스터를 스스로 제거하지 않으며, 실제로 사용되지 않는 마스터를 제거하려면 [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/)를 호출하십시오. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | 지정된 인덱스에 있는 도형을 반환합니다. 읽기 전용 [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | 슬라이드의 도형들을 반환합니다. 읽기 전용 [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체에 대해서는 이 속성이 항상 **false**를 반환합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | 슬라이드의 ID를 반환합니다. 읽기 전용 **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | 지정된 슬라이드가 슬라이드 쇼 동안 어떻게 전환되는지에 대한 정보를 포함하는 TransitionEx 객체를 반환합니다. 읽기 전용 [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | 마스터 테마 관리자를 반환합니다. 읽기 전용 [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | 애니메이션 타임라인 객체를 반환합니다. 읽기 전용 [IAnimationTimeLine](../ianimationtimeline/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | 제목 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | 이 마스터 슬라이드에 종속되는 모든 슬라이드의 배열을 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사형입니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사형입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사형입니다. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | 모든 허용 가능한 도형의 모든 단락에서 동일한 형식의 실행을 결합합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사형입니다. 사용자 정의 유형 복제를 지원합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | 슬라이드의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | 해당 마스터 뒤의 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: [Aspose.Slides](../)는 사용되지 않는 마스터를 스스로 제거하지 않으며, 실제로 사용되지 않는 마스터를 제거하려면 [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/)를 호출하십시오. 쓰기 **bool**. |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체에 대해서는 이 속성이 항상 **false**를 반환합니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사형입니다. 사용자 정의 객체를 문자열로 변환하는 것을 지원합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터와 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IBaseSlide](../ibaseslide/)
* 클래스 [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)