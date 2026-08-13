---
title: IChart
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 있는 그래픽 차트를 나타냅니다.
type: docs
weight: 573
url: /ko/aspose.slides.charts/ichart/
---
## IChart 클래스

슬라이드에 있는 그래픽 차트를 나타냅니다.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | 새 플레이스홀더가 없으면 추가하고 지정된 플레이스홀더에 속성을 설정합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | 이 테마 적용 가능 객체에 대한 실제 테마를 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | 모양과 연결된 대체 텍스트를 반환합니다. [System::String](../../system/string/)을(를) 읽어보세요. |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | 모양과 연결된 대체 텍스트의 제목을 반환합니다. [System::String](../../system/string/)을(를) 읽어보세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | 차트 축에 대한 접근을 제공합니다. 읽기 전용 [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | 3D 차트의 배경면 형식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | 속성은 모양이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)을(를) 읽어보세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | 차트와 연결되거나 포함된 데이터에 대한 정보를 반환합니다. 읽기 전용 [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | 차트의 데이터 테이블을 반환합니다. 읽기 전용 [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | 차트 제목을 반환합니다. 읽기 전용 [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | 모양의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | 모양의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | 차트에서 빈 셀을 플롯하는 방법을 반환합니다. [DisplayBlanksAsType](../displayblanksastype/)을(를) 읽어보세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | [EffectFormat](../../aspose.slides/effectformat/) 객체를 반환합니다(이 객체는 모양에 적용된 픽셀 효과를 포함합니다). 읽기 전용 [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | [FillFormat](../../aspose.slides/fillformat/) 객체를 반환합니다(이 객체는 모양의 채우기 서식 속성을 포함합니다). 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | 3D 차트의 바닥 형식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | 모양 프레임의 속성을 반환합니다. [IShapeFrame](../../aspose.slides/ishapeframe/)을(를) 읽어보세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | 모양의 잠금을 반환합니다. 읽기 전용 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | 차트에 데이터 테이블이 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | 차트에 범례가 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | 차트 영역에 둥근 모서리를 지정합니다. 읽기 **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | 차트에 표시 가능한 제목이 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | 포인트 단위로 측정된 모양의 높이를 가져옵니다. 읽기 **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | 모양이 숨겨져 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. [IHyperlink](../../aspose.slides/ihyperlink/)을(를) 읽어보세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자. 읽기 전용 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버에 정의된 하이퍼링크를 반환합니다. [IHyperlink](../../aspose.slides/ihyperlink/)을(를) 읽어보세요. |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | ‘장식용으로 표시’ 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | 모양이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | 모양이 TextHolder인지 여부를 결정합니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | 차트에 대한 범례를 반환합니다. 읽기 전용 [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | [LineFormat](../../aspose.slides/lineformat/) 객체를 반환합니다(이 객체는 모양의 선 서식 속성을 포함합니다). 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | 모양의 이름을 반환합니다. [System::String](../../system/string/)을(를) 읽어보세요. |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | 모양의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드가 문서 어디서든 모양을 안정적으로 참조할 수 있게 합니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)을(를) 참고하십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | 모양이 그룹화된 경우 부모 [GroupShape](../../aspose.slides/groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | 모양에 대한 플레이스홀더를 반환합니다. 읽기 전용 [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | 차트의 플롯 영역을 나타냅니다. 읽기 전용 [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | 보이는 셀만 플롯할지 여부를 결정합니다. 보이 및 숨김 셀 모두 플롯하려면 false로 설정합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 원시 모양 프레임의 속성을 반환합니다. [IShapeFrame](../../aspose.slides/ishapeframe/)을(를) 읽어보세요. |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 지정된 모양이 z축을 기준으로 회전된 각도를 반환합니다. 양수값은 시계 방향 회전을, 음수값은 반시계 방향 회전을 나타냅니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | 차트의 3D 회전을 반환합니다. 읽기 전용 [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | 모양의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | 차트의 최대값을 초과하는 데이터 레이블을 표시하도록 지정합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | 3D 차트의 측면벽 형식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | 차트 스타일을 반환합니다. [StyleType](../styletype/)을(를) 읽어보세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | 오버라이드 테마 관리자를 반환합니다. 읽기 전용 [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | [ThreeDFormat](../../aspose.slides/threedformat/) 객체를 반환합니다(이 객체는 모양의 선 서식 속성을 포함합니다). 읽기 전용 [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | 차트 유형을 반환합니다. [ChartType](../charttype/)을(를) 읽어보세요. |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | 추가 기능이나 기타 코드에서 사용하도록 설계된 프레젠테이션 범위 내부 식별자를 반환합니다. 이 값은 사용자에 의해 또는 프로그래밍적으로 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)을(를) 참고하십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | 차트 위에 그려지는 모양을 지정합니다. 읽기 전용 [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | 포인트 단위로 측정된 모양의 너비를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | 포인트 단위로 측정된 모양의 왼쪽 위 모서리의 x좌표를 가져옵니다. 읽기 **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | 포인트 단위로 측정된 모양의 왼쪽 위 모서리의 y좌표를 가져옵니다. 읽기 **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | z-순서에서 모양의 위치를 반환합니다. Shapes[0]은 z-순서에서 가장 뒤에 있는 모양을 반환하고, Shapes[Shapes.Count - 1]은 가장 앞에 있는 모양을 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 기본 플레이스홀더 모양을 반환합니다(현재 모양이 상속받는 레이아웃 및/또는 마스터 슬라이드의 모양). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 활성화합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | 모양 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 모양 썸네일 경계 유형이 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | 모양 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 활성화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스를 복사 생성할 수 있게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스를 복사 생성할 수 있게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | 이 모양이 플레이스홀더가 아님을 정의합니다. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | 모양과 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 모양과 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | 속성은 모양이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 쓰기 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | 차트에서 빈 셀을 플롯하는 방법을 설정합니다. 쓰기 [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 모양 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | 차트에 데이터 테이블이 있는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | 차트에 범례가 있는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | 차트 영역에 둥근 모서리를 지정합니다. 쓰기 **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | 차트에 표시 가능한 제목이 있는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | 포인트 단위로 측정된 모양의 높이를 설정합니다. 쓰기 **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | 모양이 숨겨져 있는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ‘장식용으로 표시’ 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | 모양의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | 보이는 셀만 플롯할지 여부를 결정합니다. 보이고 숨겨진 셀 모두 플롯하려면 false로 설정합니다. 쓰기 **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 원시 모양 프레임의 속성을 설정합니다. 쓰기 [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 지정된 모양이 z축을 기준으로 회전된 각도를 설정합니다. 양수값은 시계 방향 회전을, 음수값은 반시계 방향 회전을 나타냅니다. 쓰기 **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | 차트의 최대값을 초과하는 데이터 레이블을 표시하도록 지정합니다. 쓰기 **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | 차트 스타일을 설정합니다. 쓰기 [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | 차트 유형을 설정합니다. 쓰기 [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | 포인트 단위로 측정된 모양의 너비를 설정합니다. 쓰기 **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | 포인트 단위로 측정된 모양의 왼쪽 위 모서리의 x좌표를 설정합니다. 쓰기 **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | 포인트 단위로 측정된 모양의 왼쪽 위 모서리의 y좌표를 설정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n번째' 템플릿 인수를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | 차트 요소의 실제 값을 계산합니다. 실제 값에는 [IActualLayout](../iactuallayout/) 인터페이스([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/))를 구현하는 요소들의 위치와 실제 축 값([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/))이 포함됩니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/)의 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 관련 항목

* 클래스 [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* 클래스 [IFormattedTextContainer](../iformattedtextcontainer/)
* 클래스 [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)