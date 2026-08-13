---
title: SmartArtShape
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartArt 모양을 나타냅니다
type: docs
weight: 105
url: /ko/aspose.slides.smartart/smartartshape/
---
## SmartArtShape 클래스


[SmartArt](../smartart/) 모양을 나타냅니다

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | 자리표시자가 없으면 새 자리표시자를 추가하고 지정된 자리표시자에 속성을 설정합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | 도형 요소의 배열을 생성하고 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 방식 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 방식 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | 지정된 인덱스에서 도형의 조정값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | 도형의 조정값 컬렉션을 반환합니다. 읽기 전용 [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | 도형과 연결된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | 도형과 연결된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | 도형의 연결 지점 개수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | 도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | 도형에 적용된 픽셀 효과를 포함하는 [EffectFormat](../../aspose.slides/effectformat/) 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) 객체를 반환합니다. 이는 도형의 채우기 서식 속성을 포함합니다. 참고: 채우기 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | 도형의 높이를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | '장식으로 표시' 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | [LineFormat](../../aspose.slides/lineformat/) 객체를 반환합니다. 이는 도형의 선 서식 속성을 포함합니다. 참고: 선 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | 도형의 이름을 반환합니다. null이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오. 읽기 [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | 도형 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디에서든 도형을 안정적으로 참조할 수 있습니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)을 참조하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | 도형이 그룹화되어 있으면 상위 [GroupShape](../../aspose.slides/groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | 도형의 자리표시자를 반환합니다. 도형에 자리표시자가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | 원시 도형 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 지정된 도형이 z축을 중심으로 회전한 각도를 반환합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | 도형의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | 도형의 스타일 객체를 반환합니다. 읽기 전용 [IShapeStyle](../../aspose.slides/ishapestyle/). |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | 기하학 사전 설정 유형을 반환합니다. 값이 변경되면 모든 조정값이 기본값으로 재설정됩니다. 읽기 [Slides::ShapeType](../../aspose.slides/shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | [SmartArt](../smartart/) 도형의 텍스트를 반환합니다. 읽기 전용 [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) 객체를 반환합니다. 이는 도형의 3D 효과 속성을 포함합니다. 참고: 3D 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | 추가 기능이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자가 또는 프로그래밍 방식으로 재할당될 수 있기 때문에 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)을 참조하십시오. |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | 도형의 너비를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | 도형의 왼쪽 상단 모서리의 x좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | 도형의 왼쪽 상단 모서리의 y좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | z-순서에서 도형의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 기본 자리표시자 도형을 반환합니다 (현재 도형이 상속받는 레이아웃 및/또는 마스터 슬라이드의 도형). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | 기하학 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | 도형 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 도형 썸네일 경계 유형이 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | 도형 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | 렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | 이 도형이 자리표시자가 아님을 정의합니다. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | 도형과 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 도형과 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 쓰기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 도형 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | 도형의 높이를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | 도형이 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | '장식으로 표시' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | 도형의 이름을 설정합니다. null이 아니어야 합니다. 필요하면 빈 문자열을 사용하십시오. 쓰기 [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 원시 도형 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 지정된 도형이 z축을 중심으로 회전한 각도를 설정합니다. 양수 값은 시계 방향, 음수 값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | 기하학 사전 설정 유형을 설정합니다. 값이 변경되면 모든 조정값이 기본값으로 재설정됩니다. 쓰기 [Slides::ShapeType](../../aspose.slides/shapetype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | 도형의 너비를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | 도형의 왼쪽 상단 모서리의 x좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | 도형의 왼쪽 상단 모서리의 y좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) 객체에서 도형 기하를 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 ([ShapeType](../../aspose.slides/shapetype/))에서 [ShapeType::Custom](../../aspose.slides/shapetype/)(으)로 변경합니다. |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) 배열에서 도형 기하를 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 ([ShapeType](../../aspose.slides/shapetype/))에서 [ShapeType::Custom](../../aspose.slides/shapetype/)(으)로 변경합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/)의 내용을 SVG 파일로 저장합니다. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [GeometryShape](../../aspose.slides/geometryshape/)
* 클래스 [ISmartArtShape](../ismartartshape/)
* 네임스페이스 [Aspose::Slides::SmartArt](../)
* 라이브러리 [Aspose.Slides](../../)