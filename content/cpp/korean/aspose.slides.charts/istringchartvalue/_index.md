---
title: IStringChartValue
second_title: Aspose.Slides for C++ API 레퍼런스
description: "pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다: 1) 차트와 연결된 워크북의 셀/셀들에; 2) 리터럴 값으로."
type: docs
weight: 1197
url: /ko/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue 클래스

pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다: 1) 차트와 연결된 워크북의 셀/셀들에 저장; 2) 리터럴 값으로 저장.

```cpp
class IStringChartValue : public Aspose::Slides::Charts::IMultipleCellChartValue
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C#-style 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C#-style 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](../imultiplecellchartvalue/get_ascell/)(**int32_t**) | 지정된 인덱스에 해당하는 차트 셀을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\> [get_AsCells](../imultiplecellchartvalue/get_ascells/)() | 차트 셀 컬렉션을 반환합니다. 읽기 [IChartCellCollection](../ichartcellcollection/). |
| virtual [System::String](../../system/string/) [get_AsLiteralString](./get_asliteralstring/)() | DataSourceType 속성이 [DataSourceType::StringLiterals](../datasourcetype/)인 경우 리터럴 문자열을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](../ibasechartvalue/get_data/)() |  |
| virtual [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../ibasechartvalue/get_datasourcetype/)() | AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 즉, Data 속성의 값 유형을 지정합니다. 이 속성은 읽기 전용입니다. 이 속성의 값을 변경하려면 ChartDataPointCollection.DataSourceTypeFor<...> 속성 중 하나를 사용할 수 있습니다. 읽기 [DataSourceType](../datasourcetype/). |
| virtual [System::String](../../system/string/) [GetCellsAddressInWorkbook](./getcellsaddressinworkbook/)() | DataSourceType 속성이 [DataSourceType::Worksheet](../datasourcetype/)인 경우 이 메서드는 문자열 데이터를 나타내는 워크북 셀의 주소를 반환합니다. 그렇지 않으면 빈 문자열을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)에 대한 문자열 및 nullptr 경우의 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)에 대한 문자열 경우의 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_AsCells](../imultiplecellchartvalue/set_ascells/)([System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\>) | 차트 셀 컬렉션을 설정합니다. 쓰기 [IChartCellCollection](../ichartcellcollection/). |
| virtual void [set_AsLiteralString](./set_asliteralstring/)([System::String](../../system/string/)) | DataSourceType 속성이 [DataSourceType::StringLiterals](../datasourcetype/)인 경우 리터럴 문자열을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Data](../ibasechartvalue/set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) |  |
| virtual void [set_DataSourceType](../ibasechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) | AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 즉, Data 속성의 값 유형을 지정합니다. 이 속성은 읽기 전용입니다. 이 속성의 값을 변경하려면 ChartDataPointCollection.DataSourceTypeFor<...> 속성 중 하나를 사용할 수 있습니다. 쓰기 [DataSourceType](../datasourcetype/). |
| virtual void [SetFromOneCell](./setfromonecell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | 지정된 셀에서 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 포인터 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 구문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IMultipleCellChartValue](../imultiplecellchartvalue/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)