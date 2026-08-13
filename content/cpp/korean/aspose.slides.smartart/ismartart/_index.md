---
title: ISmartArt
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartArt 다이어그램을 나타냅니다.
type: docs
weight: 1
url: /ko/aspose.slides.smartart/ismartart/
---
## ISmartArt 클래스

[SmartArt](../smartart/) 다이어그램을 나타냅니다.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | 새 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | 모든 노드의 컬렉션을 [SmartArt](../smartart/) 객체에서 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | 도형에 연결된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | 도형에 연결된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | [SmartArt](../smartart/) 객체의 색상 스타일을 반환하거나 설정합니다. 읽기 [SmartArtColorType](../smartartcolortype/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | 도형의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | 도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | [EffectFormat](../../aspose.slides/effectformat/) 객체를 반환합니다(도형에 적용된 픽셀 효과를 포함). 읽기 전용 [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | [FillFormat](../../aspose.slides/fillformat/) 객체를 반환합니다(도형의 채우기 서식 속성을 포함). 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | 도형의 잠금을 반환합니다. 읽기 전용 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | 도형의 높이를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | 도형이 숨겨져 있는지 여부를 확인합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자. 읽기 전용 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | '장식으로 표시' 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | 도형이 그룹화되어 있는지 여부를 확인합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | [SmartArt](../smartart/) 다이어그램이 (왼쪽에서 오른쪽) LTR 또는 (오른쪽에서 왼쪽) RTL 상태인지 반환하거나 설정합니다(다이어그램이 반전을 지원하는 경우). 읽기 **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | 도형이 TextHolder인지 여부를 확인합니다. 읽기 전용 **bool**. |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | [SmartArt](../smartart/) 객체의 레이아웃을 반환하거나 설정합니다. 읽기 [SmartArtLayoutType](../smartartlayouttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | [LineFormat](../../aspose.slides/lineformat/) 객체를 반환합니다(도형의 선 서식 속성을 포함). 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | 도형의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | [SmartArt](../smartart/) 객체의 루트 노드 컬렉션에서 지정된 인덱스의 노드를 반환합니다. 읽기 전용 [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | [SmartArt](../smartart/) 객체의 모든 노드 컬렉션에서 지정된 인덱스의 노드를 반환합니다. 읽기 전용 [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | [SmartArt](../smartart/) 객체의 루트 노드 컬렉션을 반환합니다. 읽기 전용 [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | 도형 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있습니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)를 참조하십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | 도형이 그룹화된 경우 상위 [GroupShape](../../aspose.slides/groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | 도형의 플레이스홀더를 반환합니다. 읽기 전용 [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | [SmartArt](../smartart/) 객체의 빠른 스타일을 반환하거나 설정합니다. 읽기 [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 원시 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 지정된 도형이 z축을 중심으로 회전된 각도를 반환합니다. 양수 값은 시계 방향 회전, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | 도형의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | [ThreeDFormat](../../aspose.slides/threedformat/) 객체를 반환합니다(도형의 선 서식 속성을 포함). 읽기 전용 [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | 내부 프레젠테이션 범위 식별자를 반환합니다(애드인이나 기타 코드에서 사용 목적). 이 값은 사용자가 또는 프로그래밍으로 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)를 참조하십시오. |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | 도형의 너비를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | 도형의 왼쪽 위 모서리의 x 좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | 도형의 왼쪽 위 모서리의 y 좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | 도형의 z-순서 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 기본 플레이스홀더 도형을 반환합니다(레이아웃 및/또는 마스터 슬라이드에서 현재 도형이 상속받은 도형). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | 도형 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 도형 썸네일 경계 유형이 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | 도형 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | 이 도형이 플레이스홀더가 아님을 정의합니다. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | 도형에 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 도형에 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 쓰기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | [SmartArt](../smartart/) 객체의 색상 스타일을 반환하거나 설정합니다. 쓰기 [SmartArtColorType](../smartartcolortype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 도형 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | 도형의 높이를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | 도형이 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | '장식으로 표시' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | [SmartArt](../smartart/) 다이어그램이 (왼쪽에서 오른쪽) LTR 또는 (오른쪽에서 왼쪽) RTL 상태인지 반환하거나 설정합니다(다이어그램이 반전을 지원하는 경우). 쓰기 **bool**. |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | [SmartArt](../smartart/) 객체의 레이아웃을 반환하거나 설정합니다. 쓰기 [SmartArtLayoutType](../smartartlayouttype/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | 도형의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | [SmartArt](../smartart/) 객체의 빠른 스타일을 반환하거나 설정합니다. 쓰기 [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 원시 도형 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 지정된 도형이 z축을 중심으로 회전된 각도를 설정합니다. 양수 값은 시계 방향 회전, 음수 값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | 도형의 너비를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | 도형의 왼쪽 위 모서리의 x 좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | 도형의 왼쪽 위 모서리의 y 좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 강한 포인터 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* 네임스페이스 [Aspose::Slides::SmartArt](../)
* 라이브러리 [Aspose.Slides](../../)