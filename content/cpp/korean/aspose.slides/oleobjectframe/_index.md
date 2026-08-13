---
title: OleObjectFrame
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 있는 OLE 객체를 나타냅니다.
type: docs
weight: 4603
url: /ko/aspose.slides/oleobjectframe/
---
## OleObjectFrame 클래스


Represents an OLE object on a slide.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 플레이스홀더가 없으면 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동 소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동 소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 형상과 연결된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 형상과 연결된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 속성은 형상이 흑백 디스플레이 모드에서 렌더링되는 방식을 지정합니다. 읽기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 형상의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 형상의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 형상에 적용된 픽셀 효과를 포함하는 [EffectFormat](../effectformat/) 객체를 반환합니다. 참고: 효과 속성이 없는 특정 형상 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | OLE 포함 데이터에 대한 정보를 가져옵니다. 읽기 [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | 포함된 OLE 객체의 파일 이름을 반환합니다 |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | 포함된 OLE 객체의 경로를 반환합니다 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 형상의 채우기 서식 속성을 포함하는 [FillFormat](../fillformat/) 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 형상 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 형상 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 형상의 잠금을 반환합니다. 읽기 전용 [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | 형상의 높이를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 형상이 숨겨져 있는지 여부를 결정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘장식용으로 표시’ 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 형상이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | 객체가 아이콘으로 표시되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | 객체가 외부 파일에 연결되어 있는지 여부를 판단합니다. 읽기 전용 **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 형상이 TextHolder_PPT인지 여부를 판단합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 형상의 선 서식 속성을 포함하는 [LineFormat](../lineformat/) 객체를 반환합니다. 참고: 선 속성이 없는 특정 형상 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | 연결된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다. 읽기 전용 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | 연결된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | 연결된 파일이 있으면 상대 경로를 반환하고, 없으면 빈 문자열을 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 형상의 이름을 반환합니다. null이면 안 됩니다. 필요하면 빈 문자열을 사용하십시오. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | 객체의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | 객체의 ProgID를 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 형상의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디서든 형상을 안정적으로 참조할 수 있습니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_UniqueId](../shape/get_uniqueid/)를 참고하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 형상이 그룹화된 경우 상위 [GroupShape](../groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 형상의 플레이스홀더를 반환합니다. 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 원시 형상 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | 지정된 형상이 z축을 중심으로 회전한 각도를 반환합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 형상의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 형상의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | OleObject 이미지 채우기 속성 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | OleObject 아이콘의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 형상의 3D 효과 속성을 포함하는 [ThreeDFormat](../threedformat/) 객체를 반환합니다. 참고: 3D 속성이 없는 특정 형상 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)를 참고하십시오. |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | 프레젠테이션이 열리거나 인쇄될 때 연결된 포함 객체가 자동으로 업데이트되는지 여부를 판단합니다. 읽기 **bool**. |
| **float** [get_Width](../shape/get_width/)() override | 형상의 너비를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **float** [get_X](../shape/get_x/)() override | 형상의 좌측 상단 코너의 x 좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **float** [get_Y](../shape/get_y/)() override | 형상의 좌측 상단 코너의 y 좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-순서에서 형상의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽의 형상을, Shapes[Shapes.Count - 1]은 앞쪽의 형상을 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 기본 플레이스홀더 형상을 반환합니다(현재 형상이 상속받은 레이아웃 및/또는 마스터 슬라이드의 형상). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 형상 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 형상 썸네일 경계 유형이 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 형상 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 렌더링된 콘텐츠를 기반으로 계산된 형상의 시각적 경계를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 허용합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 허용합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 이 형상이 플레이스홀더가 아님을 정의합니다. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 형상과 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 형상과 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 속성은 형상이 흑백 디스플레이 모드에서 렌더링되는 방식을 지정합니다. 쓰기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 형상 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | 형상의 높이를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 형상이 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | '장식용으로 표시' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | 객체가 아이콘으로 표시되는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | 연결된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 쓰기 [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 형상의 이름을 설정합니다. null이면 안 됩니다. 필요하면 빈 문자열을 사용하십시오. 쓰기 [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | 객체의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | 객체의 ProgID를 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 원시 형상 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 지정된 형상이 z축을 중심으로 회전한 각도를 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | OleObject 아이콘의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | 프레젠테이션이 열리거나 인쇄될 때 연결된 포함 객체가 자동으로 업데이트되는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | 형상의 너비를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_X](../shape/set_x/)(**float**) override | 형상의 좌측 상단 코너의 x 좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | 형상의 좌측 상단 코너의 y 좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | OLE 포함 데이터에 대한 정보를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿 인수 n번째를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

The following example shows how to accessing OLE Object frames. ```cpp
// PPTX 파일을 프레젠테이션 객체로 로드합니다
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// 첫 번째 슬라이드에 접근합니다
auto slide = pres->get_Slides()->idx_get(0);
// 형상을 OleObjectFrame으로 캐스트합니다
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// OLE 객체를 읽고 디스크에 저장합니다
if (oleObjectFrame != nullptr)
{
    // 임베드된 파일 데이터를 가져옵니다
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // 임베드된 파일 확장자를 가져옵니다
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // 추출된 파일을 저장할 경로를 생성합니다
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // 추출된 데이터를 저장합니다
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## 관련 항목

* 클래스 [GraphicalObject](../graphicalobject/)
* 클래스 [IOleObjectFrame](../ioleobjectframe/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)