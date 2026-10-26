---
title: IOleObjectFrame
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 있는 OLE 객체를 나타냅니다.
type: docs
weight: 3095
url: /ko/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame 클래스

형상에 OLE 객체를 나타냅니다.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 새 자리 표시자를 추가하고, 없을 경우 지정된 자리 표시자에 대한 속성을 설정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 동일하지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 동일하지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | 형상에 연결된 대체 텍스트를 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | 형상에 연결된 대체 텍스트의 제목을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | 속성은 형상이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. [Slides::BlackWhiteMode](../blackwhitemode/)을(를) 읽으세요. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | 형상의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | 형상의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) 객체(형상에 적용된 픽셀 효과를 포함)를 반환합니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | OLE 임베디드 데이터에 대한 정보를 가져옵니다. 읽기 전용 [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | 임베디드 OLE 객체의 파일 이름을 반환합니다. |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | 임베디드 OLE 객체의 경로를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) 객체(형상의 채우기 서식 속성을 포함)를 반환합니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | 형상 프레임의 속성을 반환합니다. [IShapeFrame](../ishapeframe/)을(를) 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | 형상의 잠금을 반환합니다. 읽기 전용 [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | 형상의 높이를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | 형상이 숨겨져 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. [IHyperlink](../ihyperlink/)을(를) 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버에 정의된 하이퍼링크를 반환합니다. [IHyperlink](../ihyperlink/)을(를) 읽으세요. |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | 형상이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | 객체가 아이콘으로 표시되는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | 객체가 외부 파일에 연결되어 있는지 여부를 결정합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | 형상이 TextHolder인지 여부를 결정합니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) 객체(형상의 선 서식 속성을 포함)를 반환합니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | 링크된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다. 읽기 전용 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | 링크된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. [System::String](../../system/string/)을(를) 읽으세요. |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | 링크된 파일이 있으면 상대 경로를 반환하고, 없으면 빈 문자열을 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | 형상의 이름을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | 객체의 이름을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | 객체의 ProgID를 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | 형상의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디서든 형상을 안정적으로 참조할 수 있습니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_UniqueId](../ishape/get_uniqueid/)을(를) 참조하세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | 형상이 그룹화된 경우 상위 [GroupShape](../groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | 형상의 자리 표시자를 반환합니다. 읽기 전용 [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 원시 형상 프레임의 속성을 반환합니다. [IShapeFrame](../ishapeframe/)을(를) 읽으세요. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 지정된 형상이 z축을 중심으로 회전된 각도를 반환합니다(도 단위). 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | 형상의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | OleObject 이미지 채우기 속성 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | OleObject 아이콘의 제목을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) 객체(형상의 선 서식 속성을 포함)를 반환합니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자가 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)을(를) 참조하세요. |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | 링크된 임베디드 객체가 프레젠테이션을 열거나 인쇄할 때 자동으로 업데이트되는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | 형상의 너비를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | 형상의 좌상단 모서리의 x좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | 형상의 좌상단 모서리의 y좌표를 포인트 단위로 가져옵니다. 읽기 **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z-순서에서 형상의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 형상을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 형상을 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 기본 자리 표시자 형상을 반환합니다(레이아웃 및/또는 마스터 슬라이드에서 상속된 형상). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연계된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | 형상 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 형상 썸네일 경계 유형이 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 형상 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스를 복사 생성할 수 있게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스를 복사 생성할 수 있게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | 이 형상이 자리 표시자가 아님을 정의합니다. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | 형상에 연결된 대체 텍스트를 설정합니다. [System::String](../../system/string/)에 쓰기. |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 형상에 연결된 대체 텍스트의 제목을 설정합니다. [System::String](../../system/string/)에 쓰기. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 속성은 형상이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. [Slides::BlackWhiteMode](../blackwhitemode/)에 쓰기. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 형상 프레임의 속성을 설정합니다. [IShapeFrame](../ishapeframe/)에 쓰기. |
| virtual void [set_Height](../ishape/set_height/)(**float**) | 형상의 높이를 포인트 단위로 설정합니다. **float**에 쓰기. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | 형상이 숨겨져 있는지 여부를 설정합니다. **bool**에 쓰기. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. [IHyperlink](../ihyperlink/)에 쓰기. |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 오버에 정의된 하이퍼링크를 설정합니다. [IHyperlink](../ihyperlink/)에 쓰기. |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | 객체를 아이콘으로 표시할지 여부를 설정합니다. **bool**에 쓰기. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | 링크된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. [System::String](../../system/string/)에 쓰기. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | 형상의 이름을 설정합니다. [System::String](../../system/string/)에 쓰기. |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | 객체의 이름을 설정합니다. [System::String](../../system/string/)에 쓰기. |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | 객체의 ProgID를 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 원시 형상 프레임의 속성을 설정합니다. [IShapeFrame](../ishapeframe/)에 쓰기. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 지정된 형상이 z축을 중심으로 회전된 각도를 설정합니다(도). 양수는 시계 방향, 음수는 반시계 방향을 나타냅니다. **float**에 쓰기. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | OleObject 아이콘의 제목을 설정합니다. [System::String](../../system/string/)에 쓰기. |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | 링크된 임베디드 객체가 프레젠테이션을 열거나 인쇄할 때 자동으로 업데이트되는지 여부를 설정합니다. **bool**에 쓰기. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | 형상의 너비를 포인트 단위로 설정합니다. **float**에 쓰기. |
| virtual void [set_X](../ishape/set_x/)(**float**) | 형상의 좌상단 모서리의 x좌표를 포인트 단위로 설정합니다. **float**에 쓰기. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | 형상의 좌상단 모서리의 y좌표를 포인트 단위로 설정합니다. **float**에 쓰기. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | OLE 임베디드 데이터에 대한 정보를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IGraphicalObject](../igraphicalobject/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)