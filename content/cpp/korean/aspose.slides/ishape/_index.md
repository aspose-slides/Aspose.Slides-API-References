---
title: IShape
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 있는 모양을 나타냅니다.
type: docs
weight: 3641
url: /ko/aspose.slides/ishape/
---
## IShape 클래스

슬라이드에 있는 모양을 나타냅니다.

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 새로운 자리표시자를 추가하고, 없으면 지정된 자리표시자 속성을 설정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떠한 값과도, NaN 자체와도 같지 않지만, C# 스타일의 부동소수점 비교를 흉내 내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떠한 값과도, NaN 자체와도 같지 않지만, C# 스타일의 부동소수점 비교를 흉내 내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | 모양에 연결된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | 모양에 연결된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | 속성은 모양이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | 모양의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | 모양의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | 모양에 적용된 픽셀 효과를 포함하는 [EffectFormat](../effectformat/) 객체를 반환합니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | 모양에 대한 채우기 서식 속성을 포함하는 [FillFormat](../fillformat/) 객체를 반환합니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | 모양 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](./get_height/)() | 포인트 단위로 측정된 모양의 높이를 가져옵니다. 읽기 **float**. |
| virtual **bool** [get_Hidden](./get_hidden/)() | 모양이 숨겨져 있는지 판단합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | 'Mark as decorative' 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | 모양이 그룹화되어 있는지 판단합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | 모양이 TextHolder인지 판단합니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | 모양에 대한 선 서식 속성을 포함하는 [LineFormat](../lineformat/) 객체를 반환합니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | 모양의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | 모양의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드가 문서 어디서든 모양을 신뢰하게 참조할 수 있도록 합니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_UniqueId](./get_uniqueid/)을 참조하세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | 모양이 그룹화된 경우 상위 [GroupShape](../groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | 모양에 대한 자리표시자를 반환합니다. 읽기 전용 [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | 원시 모양 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](./get_rotation/)() | 지정된 모양이 z축을 기준으로 회전한 각도를 반환합니다. 양의 값은 시계 방향 회전을, 음의 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | 모양의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | 모양에 대한 선 서식 속성을 포함하는 [ThreeDFormat](../threedformat/) 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자에 의해 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/)을 참조하세요. |
| virtual **float** [get_Width](./get_width/)() | 포인트 단위로 측정된 모양의 너비를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_X](./get_x/)() | 포인트 단위로 측정된 모양 왼쪽 위 모서리의 x좌표를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_Y](./get_y/)() | 포인트 단위로 측정된 모양 왼쪽 위 모서리의 y좌표를 가져옵니다. 읽기 **float**. |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | z-순서에서 모양의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 모양을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 모양을 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | 기본 자리표시자 모양을 반환합니다 (현재 모양이 상속받는 레이아웃 및/또는 마스터 슬라이드에서 가져온 모양). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | 모양 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 모양 썸네일 경계 유형이 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 모양 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠급니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | 이 모양이 자리표시자가 아님을 정의합니다. |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | 모양에 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | 모양에 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 속성은 모양이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 쓰기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 모양 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](./set_height/)(**float**) | 포인트 단위로 측정된 모양의 높이를 설정합니다. 쓰기 **float**. |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | 모양이 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | 'Mark as decorative' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | 모양의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 원시 모양 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](./set_rotation/)(**float**) | 지정된 모양이 z축을 기준으로 회전한 각도를 설정합니다. 양의 값은 시계 방향 회전을, 음의 값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| virtual void [set_Width](./set_width/)(**float**) | 포인트 단위로 측정된 모양의 너비를 설정합니다. 쓰기 **float**. |
| virtual void [set_X](./set_x/)(**float**) | 포인트 단위로 측정된 모양 왼쪽 위 모서리의 x좌표를 설정합니다. 쓰기 **float**. |
| virtual void [set_Y](./set_y/)(**float**) | 포인트 단위로 측정된 모양 왼쪽 위 모서리의 y좌표를 설정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISlideComponent](../islidecomponent/)
* 클래스 [IHyperlinkContainer](../ihyperlinkcontainer/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)