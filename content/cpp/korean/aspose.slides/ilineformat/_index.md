---
title: ILineFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 라인의 형식을 나타냅니다.
type: docs
weight: 2757
url: /ko/aspose.slides/ilineformat/
---
## ILineFormat 클래스

라인의 형식을 나타냅니다.

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | 두 [LineFormat](../lineformat/) 인스턴스가 같은지 여부를 결정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 흉내냅니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 흉내냅니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | 라인 정렬을 반환합니다. 읽기 [LineAlignment](../linealignment/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | 라인 시작 부분의 화살촉 길이를 반환합니다. 읽기 [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | 라인 시작 부분의 화살촉 스타일을 반환합니다. 읽기 [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | 라인 시작 부분의 화살촉 너비를 반환합니다. 읽기 [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | 라인 캡 스타일을 반환합니다. 읽기 [LineCapStyle](../linecapstyle/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | 사용자 지정 대시 패턴을 반환합니다. 읽기 **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | 라인 대시 스타일을 반환합니다. 읽기 [LineDashStyle](../linedashstyle/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | 라인 끝 부분의 화살촉 길이를 반환합니다. 읽기 [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | 라인 끝 부분의 화살촉 스타일을 반환합니다. 읽기 [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | 라인 끝 부분의 화살촉 너비를 반환합니다. 읽기 [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | 라인의 채우기 형식을 반환합니다. 읽기 전용 [ILineFillFormat](../ilinefillformat/). |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | 라인 형식이 정의되지 않은 경우 true를 반환합니다(방금 생성된 기본값). 읽기 전용 **bool**. |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | 라인 조인 스타일을 반환합니다. 읽기 [LineJoinStyle](../linejoinstyle/). |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | 라인의 마이터 제한값을 반환합니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | 라인 스케치 형식을 반환합니다. 읽기 전용 [ISketchFormat](../isketchformat/). |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | 라인 스타일을 반환합니다. 읽기 [LineStyle](../linestyle/). |
| virtual **double** [get_Width](./get_width/)() | 라인의 너비를 반환합니다. 읽기 **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | 상속이 적용된 실제 라인 서식 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | 라인 정렬을 설정합니다. 쓰기 [LineAlignment](../linealignment/). |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | 라인 시작 부분의 화살촉 길이를 설정합니다. 쓰기 [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | 라인 시작 부분의 화살촉 스타일을 설정합니다. 쓰기 [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | 라인 시작 부분의 화살촉 너비를 설정합니다. 쓰기 [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | 라인 캡 스타일을 설정합니다. 쓰기 [LineCapStyle](../linecapstyle/). |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | 사용자 지정 대시 패턴을 설정합니다. 쓰기 **float**[]. |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | 라인 대시 스타일을 설정합니다. 쓰기 [LineDashStyle](../linedashstyle/). |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | 라인 끝 부분의 화살촉 길이를 설정합니다. 쓰기 [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | 라인 끝 부분의 화살촉 스타일을 설정합니다. 쓰기 [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | 라인 끝 부분의 화살촉 너비를 설정합니다. 쓰기 [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | 라인 조인 스타일을 설정합니다. 쓰기 [LineJoinStyle](../linejoinstyle/). |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | 라인의 마이터 제한값을 설정합니다. 쓰기 **float**. |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | 라인 스타일을 설정합니다. 쓰기 [LineStyle](../linestyle/). |
| virtual void [set_Width](./set_width/)(**double**) | 라인의 너비를 설정합니다. 쓰기 **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿의 n번째 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [ILineParamSource](../ilineparamsource/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)