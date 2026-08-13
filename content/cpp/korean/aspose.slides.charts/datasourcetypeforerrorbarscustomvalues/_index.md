---
title: DataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ChartDataPoint::get_ErrorBarsCustomValues 속성 목록의 값 유형을 지정합니다"
type: docs
weight: 404
url: /ko/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues 클래스

[ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/) 속성 목록의 값 유형을 지정합니다

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 NaN을 포함한 모든 값과 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 NaN을 포함한 모든 값과 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | 데이터 포인트 XMinus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPoint.ErrorBarsCustomValues.XMinus.Data 속성의 값 유형을 지정합니다. 읽기 [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | 데이터 포인트 XPlus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPoint.ErrorBarsCustomValues.XPlus.Data 속성의 값 유형을 지정합니다. 읽기 [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | 데이터 포인트 YMinus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data 속성의 값 유형을 지정합니다. 읽기 [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | 데이터 포인트 YPlus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data 속성의 값 유형을 지정합니다. 읽기 [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | 데이터 포인트 XMinus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPoint.ErrorBarsCustomValues.XMinus.Data 속성의 값 유형을 지정합니다. 쓰기 [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | 데이터 포인트 XPlus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPoint.ErrorBarsCustomValues.XPlus.Data 속성의 값 유형을 지정합니다. 쓰기 [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | 데이터 포인트 YMinus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data 속성의 값 유형을 지정합니다. 쓰기 [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | 데이터 포인트 YPlus 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다(오류 막대 사용자 정의 값). 다시 말해 ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data 속성의 값 유형을 지정합니다. 쓰기 [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)