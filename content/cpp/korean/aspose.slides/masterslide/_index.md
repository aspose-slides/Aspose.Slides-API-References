---
title: MasterSlide
second_title: Aspose.Slides용 C++ API 레퍼런스
description: 프레젠테이션에서 마스터 슬라이드를 나타냅니다.
type: docs
weight: 4473
url: /ko/aspose.slides/masterslide/
---
## MasterSlide 클래스


프레젠테이션에서 마스터 슬라이드를 나타냅니다.

```cpp
class MasterSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::IMasterSlide
```

## 메서드

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) override | 현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 뒤, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | 이 슬라이드에 적용되는 테마를 반환합니다. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | 두 [IBaseSlide](../ibaseslide/) 인스턴스가 동일한지 여부를 결정합니다. 반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 형태, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드가 동일하다고 간주합니다. 비교에서는 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: 날짜 [Placeholder](../placeholder/)의 현재 날짜 값)는 고려되지 않습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | 지정된 대체 텍스트를 가진 도형을 처음으로 찾습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | 슬라이드 배경을 반환합니다. 읽기 전용 [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() override | 본문 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | 지정된 인덱스에 있는 ActiveX 컨트롤을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | 슬라이드에 있는 ActiveX 컨트롤 컬렉션을 반환합니다. 읽기 전용 [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | 슬라이드의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | 마스터 슬라이드에 종속된 슬라이드가 최소 하나 존재하면 true를 반환합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | 마스터 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | 포함된 하이퍼링크에 쉬운 접근을 제공합니다. 읽기 전용 [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | 지정된 인덱스에 있는 이 마스터 슬라이드의 자식 레이아웃 슬라이드를 반환합니다. 읽기 전용 [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | 이 마스터 슬라이드의 자식 레이아웃 슬라이드 컬렉션을 반환합니다. 읽기 전용 [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | 마스터 슬라이드의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() override | 다른 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | [IPresentation](../ipresentation/) 인터페이스를 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| **bool** [get_Preserve](./get_preserve/)() override | 해당 마스터에 뒤따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: [Aspose.Slides](../)는 사용되지 않는 마스터를 스스로 제거하지 않으며, 실제로 사용되지 않는 마스터를 제거하려면 [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/)을 호출하십시오. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | 지정된 인덱스에 있는 도형을 반환합니다. 읽기 전용 [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | 슬라이드의 도형들을 반환합니다. 읽기 전용 [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | 마스터 슬라이드의 도형이 슬라이드에 표시될지 여부를 지정합니다. 마스터 슬라이드 자체에 대해서는 이 속성이 항상 **false**를 반환합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | 슬라이드의 ID를 반환합니다. 읽기 전용 **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | 지정된 슬라이드가 슬라이드 쇼 중에 어떻게 전환되는지에 대한 정보를 포함하는 Transition 객체를 반환합니다. 읽기 전용 [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](./get_thememanager/)() override | 테마 관리자를 반환합니다. 읽기 전용 [Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | 애니메이션 타임라인 객체를 반환합니다. 읽기 전용 [IAnimationTimeLine](../ianimationtimeline/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() override | 제목 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | 이 마스터 슬라이드에 종속된 모든 슬라이드의 배열을 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | 모든 허용 가능한 도형의 모든 단락에서 동일한 서식의 실행을 병합합니다. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | 모든 허용 가능한 도형의 모든 단락에서 동일한 서식의 실행을 병합합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | 마스터 슬라이드의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_Preserve](./set_preserve/)(**bool**) override | 해당 마스터에 뒤따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: [Aspose.Slides](../)는 사용되지 않는 마스터를 스스로 제거하지 않으며, 실제로 사용되지 않는 마스터를 제거하려면 [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/)를 호출하십시오. 쓰기 **bool**. |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | 마스터 슬라이드의 도형이 슬라이드에 표시될지 여부를 지정합니다. 마스터 슬라이드 자체에 대해서는 이 속성이 항상 **false**를 반환합니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 포인터 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환하는 것을 가능하게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [BaseSlide](../baseslide/)
* 클래스 [IMasterSlide](../imasterslide/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)