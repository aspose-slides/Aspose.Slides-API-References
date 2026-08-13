---
title: ICell
second_title: Aspose.Slides for C++ API 레퍼런스
description: 테이블의 셀을 나타냅니다.
type: docs
weight: 1639
url: /ko/aspose.slides/icell/
---
## ICell 클래스

테이블의 셀을 나타냅니다.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일의 부동소수점 비교를 에뮬레이트합니다. 두 NaN을 동일하게 간주하지만 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않으며 NaN도 포함됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동소수점 비교를 에뮬레이트합니다. 두 NaN을 동일하게 간주하지만 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않으며 NaN도 포함됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | 셀 내부에 텍스트 박스가 가운데 정렬되어 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | [CellFormat](../cellformat/) 객체를 반환하며, 이 객체는 이 셀에 대한 형식 속성을 포함합니다. 읽기 전용 [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | 부모 테이블의 그리드에서 현재 셀이 차지해야 하는 열 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | 셀의 첫 번째 열을 가져옵니다. 읽기 전용 [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | 셀에 의해 차지되는 첫 번째 열의 인덱스를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | 셀의 첫 번째 행을 가져옵니다. 읽기 전용 [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | 셀에 의해 차지되는 첫 번째 행의 인덱스를 반환합니다. 읽기 전용 **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | 셀의 높이를 반환합니다. 읽기 전용 **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | 셀을 다른 조정된 셀과 병합했으면 true, 그렇지 않으면 false를 반환합니다. 읽기 전용 **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/)의 하단 여백을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/)의 왼쪽 여백을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/)의 오른쪽 여백을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/)의 상단 여백을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | 셀의 최소 높이를 반환합니다. 이는 셀이 차지하는 모든 행의 최소 높이의 합계입니다. 읽기 전용 **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | 테이블의 왼쪽 측면에서 셀의 왼쪽 측면까지의 거리를 반환합니다. 읽기 전용 **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | 테이블의 상단 측면에서 셀의 상단 측면까지의 거리를 반환합니다. 읽기 전용 **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | 병합된 셀이 차지하는 행 수를 반환합니다. 이는 다른 셀의 vMerge 속성과 함께 사용되어 수평 병합의 시작 셀을 지정합니다. 읽기 전용 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | 셀에 대한 상위 [Table](../table/) 객체를 반환합니다. 읽기 전용 [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | 텍스트 앵커 유형을 반환합니다. 읽기 [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | 셀의 텍스트 프레임을 반환합니다. 읽기 전용 [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 수직 텍스트 유형을 반환합니다. 읽기 [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | 셀의 너비를 반환합니다. 읽기 전용 **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연계된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | 셀 내부에 텍스트 박스가 가운데 정렬되어 있는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/)의 하단 여백을 설정합니다. 쓰기 **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/)의 왼쪽 여백을 설정합니다. 쓰기 **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/)의 오른쪽 여백을 설정합니다. 쓰기 **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/)의 상단 여백을 설정합니다. 쓰기 **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | 텍스트 앵커 유형을 설정합니다. 쓰기 [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 수직 텍스트 유형을 설정합니다. 쓰기 [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 weak 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | 열 인덱스로 셀을 두 개로 분할합니다. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | 높이로 셀을 분할합니다. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | 행 인덱스로 셀을 두 개로 분할합니다. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | 너비로 셀을 분할합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISlideComponent](../islidecomponent/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)