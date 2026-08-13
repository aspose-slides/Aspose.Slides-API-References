---
title: ChartData
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트 플롯에 사용되는 데이터를 나타냅니다.
type: docs
weight: 118
url: /ko/aspose.slides.charts/chartdata/
---
## ChartData 클래스

차트 플롯에 사용되는 데이터를 나타냅니다.

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | 주 기본 카테고리를 가져옵니다(또는 [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/)가 false로 설정된 경우 기본 및 보조 카테고리 모두 가져옵니다). 읽기 전용 [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | 지정된 인덱스의 기본 카테고리를 반환합니다. [get_UseSecondaryCategories](./get_usesecondarycategories/)가 false인 경우 모든 카테고리 중에서 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | 차트 시리즈 또는 카테고리에 사용되는 셀을 생성하는 셀 공장을 가져옵니다. 읽기 전용 [IChartDataWorkbook](../ichartdataworkbook/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | 지정된 인덱스의 시리즈를 반환합니다. |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | 외부 데이터 소스인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 null을 반환합니다. |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | 내장 워크북의 유형을 가져옵니다. [ChartData::get_DataSourceType](./get_datasourcetype/)가 [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/)인 경우 [WorkbookType::NotDefined](../workbooktype/)을 반환합니다. 읽기 전용 [WorkbookType](../workbooktype/). |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | 차트의 데이터 소스를 나타냅니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/)가 true인 경우 보조 카테고리를 가져옵니다. 읽기 전용 [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | 지정된 인덱스의 보조 카테고리를 반환합니다. [get_UseSecondaryCategories](./get_usesecondarycategories/)가 false인 경우 [ChartData::get_SecondaryCategories](./get_secondarycategories/)은 null입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | 시리즈를 가져옵니다. 읽기 전용 [IChartSeriesCollection](../ichartseriescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | 지정된 인덱스의 시리즈 그룹을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | 시리즈 그룹을 가져옵니다. 읽기 전용 [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | false로 설정하면 [ChartData::get_SecondaryCategories](./get_secondarycategories/)가 null을 반환하고 [ChartData::get_Categories](./get_categories/)의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true로 설정하면 [ChartData::get_SecondaryCategories](./get_secondarycategories/)의 데이터가 보조 시리즈에, [ChartData::get_Categories](./get_categories/)의 데이터가 기본 시리즈에 사용됩니다. 읽기 **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | 차트 데이터 범위를 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | 내부에 포함된 [Excel](../../aspose.slides.excel/) 워크북을 메모리 스트림에 기록합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소합니다. |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | false로 설정하면 [ChartData::get_SecondaryCategories](./get_secondarycategories/)가 null을 반환하고 [ChartData::get_Categories](./get_categories/)의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true로 설정하면 [ChartData::get_SecondaryCategories](./get_secondarycategories/)의 데이터가 보조 시리즈에, [ChartData::get_Categories](./get_categories/)의 데이터가 기본 시리즈에 사용됩니다. 쓰기 **bool**. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | 외부 워크북을 차트의 데이터 소스로 설정합니다. [Chart](../chart/) 데이터는 대상 워크북에서 업데이트됩니다. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | 외부 워크북을 차트의 데이터 소스로 설정합니다. |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | 차트 데이터 범위를 설정합니다. 새 데이터 범위에 따라 시리즈와 카테고리가 업데이트됩니다. 데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [SwitchRowColumn](./switchrowcolumn/)() override | 축을 따라 데이터를 교환합니다. X축에 차트된 데이터가 Y축으로 이동하고 그 반대도 마찬가지입니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | 내부에 포함된 [Excel](../../aspose.slides.excel/) 워크북을 사용자 지정 값으로 초기화합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [DomObject](../../aspose.slides/domobject/)
* 클래스 [IChartData](../ichartdata/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)