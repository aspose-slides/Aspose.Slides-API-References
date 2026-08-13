---
title: IZoomObject
second_title: C++용 Aspose.Slides API 참조
description: 슬라이드에서 Zoom 개체를 나타냅니다.
type: docs
weight: 4265
url: /ko/aspose.slides/izoomobject/
---
## IZoomObject 클래스

슬라이드에서 Zoom 개체를 나타냅니다.

```cpp
class IZoomObject : public virtual Aspose::Slides::IGraphicalObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 새 자리표시자가 없으면 새 자리표시자를 추가하고 지정된 자리표시자에 속성을 설정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | 도형에 연결된 대체 텍스트를 반환합니다. [System::String](../../system/string/)을(를) 읽으십시오. |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | 도형에 연결된 대체 텍스트의 제목을 반환합니다. [System::String](../../system/string/)을(를) 읽으십시오. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | 이 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지 지정합니다. [Slides::BlackWhiteMode](../blackwhitemode/)을(를) 읽으십시오. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | 도형의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | 도형의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) 객체를 반환합니다. 이 객체는 도형에 적용된 픽셀 효과를 포함합니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) 객체를 반환합니다. 이 객체는 도형의 채우기 서식 속성을 포함합니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | 도형 프레임의 속성을 반환합니다. [IShapeFrame](../ishapeframe/)을(를) 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | 도형의 잠금을 반환합니다. 읽기 전용 [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | 포인트 단위로 측정된 도형의 높이를 가져옵니다. 읽기 **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | 도형이 숨겨져 있는지 여부를 판단합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. [IHyperlink](../ihyperlink/)을(를) 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자. 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버에 정의된 하이퍼링크를 반환합니다. [IHyperlink](../ihyperlink/)을(를) 읽으십시오. |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() | Zoom 객체의 이미지 유형을 가져옵니다. [ZoomImageType](../zoomimagetype/)을(를) 읽으십시오. 기본값: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Mark as decorative’ 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | 도형이 그룹화되어 있는지 판단합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | 도형이 TextHolder인지 판단합니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) 객체를 반환합니다. 이 객체는 도형의 선 서식 속성을 포함합니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | 도형의 이름을 반환합니다. [System::String](../../system/string/)을(를) 읽으십시오. |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이는 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_UniqueId](../ishape/get_uniqueid/)를 참조하십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | 도형이 그룹화된 경우 상위 [GroupShape](../groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | 도형의 자리표시자를 반환합니다. 읽기 전용 [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 원시 도형 프레임의 속성을 반환합니다. [IShapeFrame](../ishapeframe/)을(를) 읽으십시오. |
| virtual **bool** [get_ReturnToParent](./get_returntoparent/)() | 슬라이드쇼에서 네비게이션 동작을 가져옵니다. 읽기 **bool**. 기본값: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 지정된 도형이 z축을 중심으로 회전된 각도를 반환합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | 도형의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](./get_showbackground/)() | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져옵니다. 읽기 **bool**. 기본값: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) 객체를 반환합니다. 이 객체는 도형의 선 서식 속성을 포함합니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](./get_transitionduration/)() | Zoom과 슬라이드 간 전환 지속 시간을 가져옵니다. 읽기 **float**. 기본값: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자가 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)를 참조하십시오. |
| virtual **float** [get_Width](../ishape/get_width/)() | 포인트 단위로 측정된 도형의 너비를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | 도형 왼쪽 상단 모서리의 x좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | 도형 왼쪽 상단 모서리의 y좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() | Zoom 객체의 이미지를 가져옵니다. [IPPImage](../ippimage/)을(를) 읽으십시오. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z-순서에서 도형의 위치를 반환합니다. Shapes[0]은 z-순서의 뒤쪽에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 기본 자리표시자 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | 도형 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 도형 썸네일 경계 유형이 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 도형 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | 이 도형이 자리표시자가 아님을 정의합니다. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | 도형에 연결된 대체 텍스트를 설정합니다. [System::String](../../system/string/)을(를) 쓰십시오. |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 도형에 연결된 대체 텍스트의 제목을 설정합니다. [System::String](../../system/string/)을(를) 쓰십시오. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 도형이 흑백 표시 모드에서 어떻게 렌더링되는지 지정합니다. [Slides::BlackWhiteMode](../blackwhitemode/)을(를) 쓰십시오. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 도형 프레임의 속성을 설정합니다. [IShapeFrame](../ishapeframe/)을(를) 쓰십시오. |
| virtual void [set_Height](../ishape/set_height/)(**float**) | 포인트 단위로 도형의 높이를 설정합니다. **float**을(를) 쓰십시오. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | 도형이 숨겨져 있는지 여부를 설정합니다. **bool**을(를) 쓰십시오. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. [IHyperlink](../ihyperlink/)을(를) 쓰십시오. |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 오버에 정의된 하이퍼링크를 설정합니다. [IHyperlink](../ihyperlink/)을(를) 쓰십시오. |
| virtual void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Zoom 객체의 이미지 유형을 설정합니다. [ZoomImageType](../zoomimagetype/)을(를) 쓰십시오. 기본값: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Mark as decorative’ 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | 도형의 이름을 설정합니다. [System::String](../../system/string/)을(를) 쓰십시오. |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 원시 도형 프레임의 속성을 설정합니다. [IShapeFrame](../ishapeframe/)을(를) 쓰십시오. |
| virtual void [set_ReturnToParent](./set_returntoparent/)(**bool**) | 슬라이드쇼에서 네비게이션 동작을 설정합니다. **bool**을(를) 쓰십시오. 기본값: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 지정된 도형을 z축을 중심으로 회전시킨 각도를 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. **float**을(를) 쓰십시오. |
| virtual void [set_ShowBackground](./set_showbackground/)(**bool**) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 설정합니다. **bool**을(를) 쓰십시오. 기본값: true |
| virtual void [set_TransitionDuration](./set_transitionduration/)(**float**) | Zoom과 슬라이드 간 전환 지속 시간을 설정합니다. **float**을(를) 쓰십시오. 기본값: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | 포인트 단위로 도형의 너비를 설정합니다. **float**을(를) 쓰십시오. |
| virtual void [set_X](../ishape/set_x/)(**float**) | 도형 왼쪽 상단 모서리의 x좌표를 포인트 단위로 설정합니다. **float**을(를) 쓰십시오. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | 도형 왼쪽 상단 모서리의 y좌표를 포인트 단위로 설정합니다. **float**을(를) 쓰십시오. |
| virtual void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Zoom 객체의 이미지를 설정합니다. [IPPImage](../ippimage/)을(를) 쓰십시오. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿 인수 n번째를 weak 포인터(공유 포인터가 아닌)로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IGraphicalObject](../igraphicalobject/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)