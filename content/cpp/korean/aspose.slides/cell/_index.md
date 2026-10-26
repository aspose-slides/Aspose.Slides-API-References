---
title: Cell
second_title: Aspose.Slides C++용 API 참조
description: 표의 셀을 나타냅니다.
type: docs
weight: 300
url: /ko/aspose.slides/cell/
---
## Cell 클래스

Represents a cell of a table.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | 셀 내부에 텍스트 상자가 가운데 정렬되어 있는지 여부를 결정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | 이 셀의 서식 속성을 포함하는 [CellFormat](../cellformat/) 객체를 반환합니다. 읽기 전용 [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | 현재 셀이 차지할 상위 테이블의 그리드 열 수를 반환합니다. 이 속성은 셀이 테이블의 다른 셀의 수직 경계를 가로질러 병합된 것처럼 보이게 합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | 셀의 첫 번째 열을 가져옵니다. 읽기 전용 [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | 셀에 의해 커버되는 첫 번째 열의 인덱스를 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | 셀의 첫 번째 행을 가져옵니다. 읽기 전용 [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | 셀에 의해 커버되는 첫 번째 행의 인덱스를 반환합니다. 읽기 전용 **int32_t**. |
| **double** [get_Height](./get_height/)() override | 셀의 높이를 반환합니다. 읽기 전용 **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | 셀은 조정된 셀과 병합되어 있으면 true, 그렇지 않으면 false를 반환합니다. 읽기 전용 **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | [TextFrame](../textframe/)의 아래쪽 여백을 반환합니다. 읽기 **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | [TextFrame](../textframe/)의 왼쪽 여백을 반환합니다. 읽기 **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | [TextFrame](../textframe/)의 오른쪽 여백을 반환합니다. 읽기 **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | [TextFrame](../textframe/)의 위쪽 여백을 반환합니다. 읽기 **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | 셀의 최소 높이를 반환합니다. 이는 셀에 포함된 모든 행의 최소 높이의 합계입니다. 읽기 전용 **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | 테이블의 왼쪽 가장자리에서 셀의 왼쪽 가장자리까지의 거리를 반환합니다. 읽기 전용 **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | 테이블의 위쪽 가장자리에서 셀의 위쪽 가장자리까지의 거리를 반환합니다. 읽기 전용 **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | 셀의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | 병합된 셀이 차지하는 행 수를 반환합니다. 이는 다른 셀의 vMerge 속성과 결합하여 수평 병합의 시작 셀을 지정하는 데 사용됩니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | 셀의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | 셀에 대한 상위 [Table](../table/) 객체를 반환합니다. 읽기 전용 [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | 텍스트 앵커 유형을 반환합니다. 읽기 [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | 셀의 텍스트 프레임을 반환합니다. 읽기 전용 [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | 수직 텍스트 유형을 반환합니다. 읽기 [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | 셀의 너비를 반환합니다. 읽기 전용 **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시 작성을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | 셀 내부에 텍스트 상자가 가운데 정렬되어 있는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | [TextFrame](../textframe/)의 아래쪽 여백을 설정합니다. 쓰기 **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | [TextFrame](../textframe/)의 왼쪽 여백을 설정합니다. 쓰기 **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | [TextFrame](../textframe/)의 오른쪽 여백을 설정합니다. 쓰기 **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | [TextFrame](../textframe/)의 위쪽 여백을 설정합니다. 쓰기 **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | 텍스트 앵커 유형을 설정합니다. 쓰기 [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | 수직 텍스트 유형을 설정합니다. 쓰기 [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운터를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | 열 인덱스로 셀을 두 개의 셀로 분할합니다. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | 높이로 셀을 분할합니다. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | 행 인덱스로 셀을 두 개의 셀로 분할합니다. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | 너비로 셀을 분할합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운터를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IDOMObject](../idomobject/)
* 클래스 [ICell](../icell/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)