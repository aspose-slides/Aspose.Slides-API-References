---
title: ISmartArtShape
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartArt 다이어그램 내부의 모양을 나타냅니다
type: docs
weight: 40
url: /ko/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape 클래스

[SmartArt](../smartart/) 다이어그램 내부의 모양을 나타냅니다

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | 새 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더의 속성을 설정합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | 모양 요소들의 배열을 생성하고 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계로 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이션하여 두 NaN을 동일한 것으로 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이션하여 두 NaN을 동일한 것으로 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | 지정된 인덱스에서 모양의 조정값을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | 모양의 조정값 컬렉션을 반환합니다. 읽기 전용 [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | 모양과 연결된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | 모양과 연결된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | 프로퍼티는 모양이 흑백 디스플레이 모드에서 어떻게 렌더링되는지 지정합니다. 읽기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | 모양의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | 모양의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | 모양에 적용된 픽셀 효과를 포함하는 [EffectFormat](../../aspose.slides/effectformat/) 객체를 반환합니다. 읽기 전용 [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | 모양의 채우기 서식 속성을 포함하는 [FillFormat](../../aspose.slides/fillformat/) 객체를 반환합니다. 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | 모양 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | 포인트 단위로 측정된 모양의 높이를 가져옵니다. 읽기 **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | 모양이 숨겨져 있는지 여부를 판단합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭을 위해 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자는 읽기 전용 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버를 위해 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | ‘장식으로 표시’ 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | 모양이 그룹화되어 있는지 여부를 판단합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | 모양이 TextHolder인지 여부를 판단합니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | 모양의 선 서식 속성을 포함하는 [LineFormat](../../aspose.slides/lineformat/) 객체를 반환합니다. 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | 모양의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | 슬라이드 범위의 고유 식별자를 반환합니다. 이 식별자는 모양의 수명 동안 일정하게 유지되며 PowerPoint 또는 인터옵 코드가 문서 어디에서든 모양을 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 **uint32_t**. 참고 [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | 모양이 그룹화된 경우 상위 [GroupShape](../../aspose.slides/groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | 모양의 플레이스홀더를 반환합니다. 읽기 전용 [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 원시 모양 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 지정된 모양이 z축을 중심으로 회전한 각도를 도 단위로 반환합니다. 양수 값은 시계 방향 회전을 나타내고 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | 모양의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | 모양의 스타일 객체를 반환합니다. 읽기 전용 [IShapeStyle](../../aspose.slides/ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | 기하학 프리셋 타입을 반환합니다. 참고: 값이 변경되면 모든 조정값이 기본값으로 재설정됩니다. 읽기 [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | [SmartArt](../smartart/) 모양의 텍스트를 반환합니다. 읽기 전용 [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | 모양의 선 서식 속성을 포함하는 [ThreeDFormat](../../aspose.slides/threedformat/) 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 참고 [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | 포인트 단위로 측정된 모양의 너비를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | 포인트 단위로 측정된 모양의 왼쪽 위 모서리의 x좌표를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | 포인트 단위로 측정된 모양의 왼쪽 위 모서리의 y좌표를 가져옵니다. 읽기 **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | z-순서에서 모양의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽의 모양을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽의 모양을 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 현재 모양이 상속받은 레이아웃 및/또는 마스터 슬라이드의 기본 플레이스홀더 모양을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | 기하학 모양의 경로 복사본을 반환합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | 모양 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 모양 썸네일 경계 유형이 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | 모양 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# ‘is’ 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | 이 모양이 플레이스홀더가 아님을 정의합니다. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | 모양과 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 모양과 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | 프로퍼티는 모양이 흑백 디스플레이 모드에서 어떻게 렌더링되는지 지정합니다. 쓰기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 모양 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | 모양의 높이를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | 모양이 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 마우스 클릭을 위해 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 마우스 오버를 위해 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ‘장식으로 표시’ 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | 모양의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 원시 모양 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 지정된 모양이 z축을 중심으로 회전한 각도를 도 단위로 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | 기하학 프리셋 타입을 설정합니다. 참고: 값이 변경되면 모든 조정값이 기본값으로 재설정됩니다. 쓰기 [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | 모양의 너비를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | 모양의 왼쪽 위 모서리의 x좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | 모양의 왼쪽 위 모서리의 y좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | [IGeometryPath](../../aspose.slides/igeometrypath/) 객체에서 모양 기하학을 업데이트합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 해야 합니다. 모양 유형([ShapeType](../../aspose.slides/shapetype/))을 [ShapeType::Custom](../../aspose.slides/shapetype/)으로 변경합니다. |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | [IGeometryPath](../../aspose.slides/igeometrypath/) 배열에서 모양 기하학을 업데이트합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 해야 합니다. 모양 유형([ShapeType](../../aspose.slides/shapetype/))을 [ShapeType::Custom](../../aspose.slides/shapetype/)으로 변경합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현이며, 사용자 정의 객체를 문자열로 변환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) 내용을 SVG 파일로 저장합니다. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [IGeometryShape](../../aspose.slides/igeometryshape/)
* 네임스페이스 [Aspose::Slides::SmartArt](../)
* 라이브러리 [Aspose.Slides](../../)