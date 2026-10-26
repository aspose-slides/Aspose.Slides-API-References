---
title: SummaryZoomSection
second_title: C++용 Aspose.Slides API 참조
description: Summary Zoom 프레임 내의 Summary Zoom Section 객체를 나타냅니다.
type: docs
weight: 5331
url: /ko/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection 클래스


Represents a Summary Zoom [Section](../section/) object in a Summary Zoom frame.

```cpp
class SummaryZoomSection : public Aspose::Slides::SectionZoomFrame,
                           public Aspose::Slides::ISummaryZoomSection
```

## 메서드

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 플래스홀더가 없으면 새 플래스홀더를 추가하고 지정된 플래스홀더의 속성을 설정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 도형과 연관된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 도형과 연관된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 도형의 연결 위치 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 도형의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| [System::String](../../system/string/) [get_Description](./get_description/)() override | Summary Zoom [Section](../section/) 객체의 텍스트 설명을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) 객체를 반환하며, 이는 도형에 적용된 픽셀 효과를 포함합니다. 참고: 효과 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) 객체를 반환하며, 이는 도형의 채우기 서식 속성을 포함합니다. 참고: 채우기 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 도형의 잠금을 반환합니다. 읽기 전용 [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | 도형의 높이를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | 줌 객체의 이미지 유형을 가져옵니다. 읽기 [ZoomImageType](../zoomimagetype/). 기본값: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) 객체를 반환하며, 이는 도형의 선 서식 속성을 포함합니다. 참고: 선 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 도형의 이름을 반환합니다. null이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오. 읽기 [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 안정적으로 참조할 수 있습니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_UniqueId](../shape/get_uniqueid/)를 참고하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 도형이 그룹화된 경우 상위 [GroupShape](../groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 도형의 플레이스홀더를 반환합니다. 도형에 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 원시 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | 슬라이드쇼에서의 탐색 동작을 가져옵니다. 읽기 **bool**. 기본값: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | 지정된 도형이 z축을 중심으로 회전한 각도를 반환합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 도형의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | 줌이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져옵니다. 읽기 **bool**. 기본값: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../sectionzoomframe/get_targetsection/)() override | [Section](../section/) 줌 객체가 연결되는 섹션 객체를 가져옵니다. 읽기 [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) 객체를 반환하며, 이는 도형의 3D 효과 속성을 포함합니다. 참고: 3D 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Summary Zoom [Section](../section/) 객체의 텍스트 제목을 반환합니다. |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | 줌과 슬라이드 간 전환 지속 시간을 가져옵니다. 읽기 **float**. 기본값: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자가 또는 프로그래밍적으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)를 참고하십시오. |
| **float** [get_Width](../shape/get_width/)() override | 도형의 너비를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **float** [get_X](../shape/get_x/)() override | 도형의 좌상단 모서리의 x좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **float** [get_Y](../shape/get_y/)() override | 도형의 좌상단 모서리의 y좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | 줌 객체의 이미지를 가져옵니다. 읽기 [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-order에서 도형의 위치를 반환합니다. Shapes[0]은 z-order의 뒤쪽에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 기본 플레이스홀더 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시화를 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 도형 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 도형 썸네일 경계 유형이 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 도형 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화로, 문자열과 nullptr인 경우에 적용됩니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화로, 문자열인 경우에 적용됩니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 이 도형이 플레이스홀더가 아님을 정의합니다. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 도형과 연관된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 도형과 연관된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 쓰기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Description](./set_description/)([System::String](../../system/string/)) override | Summary Zoom [Section](../section/) 객체의 텍스트 설명을 반환합니다. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 도형 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | 도형의 높이를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 도형이 숨겨져 있는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | 줌 객체의 이미지 유형을 설정합니다. 쓰기 [ZoomImageType](../zoomimagetype/). 기본값: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 도형의 이름을 설정합니다. null이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오. 쓰기 [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 원시 도형 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | 슬라이드쇼에서의 탐색 동작을 설정합니다. 쓰기 **bool**. 기본값: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 지정된 도형이 z축을 중심으로 회전한 각도를 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | 줌이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 설정합니다. 쓰기 **bool**. 기본값: true |
| void [set_TargetSection](../sectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | [Section](../section/) 줌 객체가 연결되는 섹션 객체를 설정합니다. 쓰기 [ISection](../isection/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Summary Zoom [Section](../section/) 객체의 텍스트 제목을 반환합니다. |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | 줌과 슬라이드 간 전환 지속 시간을 설정합니다. 쓰기 **float**. 기본값: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | 도형의 너비를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_X](../shape/set_x/)(**float**) override | 도형의 좌상단 모서리의 x좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | 도형의 좌상단 모서리의 y좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 줌 객체의 이미지를 설정합니다. 쓰기 [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/)의 콘텐츠를 SVG 파일로 저장합니다. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/)의 콘텐츠를 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 관련 항목

* 클래스 [SectionZoomFrame](../sectionzoomframe/)
* 클래스 [ISummaryZoomSection](../isummaryzoomsection/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)