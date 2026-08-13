---
title: AdjustableArrowCap
second_title: Aspose.Slides for C++ API 참조
description: "조정 가능한 화살표 모양 라인 캡을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 생성하거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 1
url: /ko/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap 클래스

조정 가능한 화살표 모양 라인 캡을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만 사용하여 할당해야 합니다. 이 타입의 인스턴스를 스택에 생성하거나 operator new를 사용해서 만들면 런타임 오류 및 어설션 오류가 발생하므로 절대 생성하지 마십시오. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 이 포인터를 함수 인수로 전달하십시오.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | [AdjustableArrowCap](./)의 새로운 인스턴스를 지정된 너비와 높이로 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | 현재 객체의 복사본을 반환합니다. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | [CustomLineCap](../customlinecap/) 클래스를 새로운 인스턴스로 생성하며, 지정된 속성을 가진 사용자 정의 라인 캡을 나타냅니다. |
| void [Dispose](../customlinecap/dispose/)() | 현재 객체가 획득한 모든 운영 체제 리소스를 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 심지어 NaN 자체와도 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 심지어 NaN 자체와도 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | 이 사용자 정의 캡이 생성된 기본 라인 캡을 반환합니다. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | 라인과 캡 사이의 거리를 반환합니다. |
| **bool** [get_Filled](./get_filled/)() const | 현재 객체가 나타내는 화살표가 채워졌는지 여부를 나타내는 값을 반환합니다. |
| **float** [get_Height](./get_height/)() const | 현재 객체가 나타내는 화살표의 높이를 반환합니다. |
| **float** [get_MiddleInset](./get_middleinset/)() const | 현재 객체가 나타내는 라인과 캡 사이의 거리를 설정합니다. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | 이 사용자 정의 캡의 라인 결합 방식을 결정하는 LineJoin 값을 반환합니다. |
| **float** [get_Width](./get_width/)() const | 현재 객체가 나타내는 화살표의 너비를 반환합니다. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | 이 사용자 정의 캡의 스케일을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | 현재 객체가 나타내는 사용자 정의 캡의 시작 및 끝 라인 캡을 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능을 제공합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열 및 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)를 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | 이 사용자 정의 캡의 기본 라인 캡 값을 설정합니다. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | 라인과 캡 사이의 거리를 설정합니다. |
| void [set_Filled](./set_filled/)(**bool**) | 현재 객체가 나타내는 화살표가 채워졌는지 여부를 지정하는 값을 설정합니다. |
| void [set_Height](./set_height/)(**float**) | 현재 객체가 나타내는 화살표의 높이를 설정합니다. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | 현재 객체가 나타내는 라인과 캡 사이의 거리를 설정합니다. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | 이 사용자 정의 캡의 라인 결합 방식을 결정하는 LineJoin 값을 설정합니다. |
| void [set_Width](./set_width/)(**float**) | 현재 객체가 나타내는 화살표의 너비를 설정합니다. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | 이 사용자 정의 캡의 스케일 값을 설정합니다. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | 현재 객체가 나타내는 사용자 정의 캡의 시작 및 끝 라인 캡을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터가 아닌 weak 포인터로 설정합니다. 컨테이너 내 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 관련 항목

* 클래스 [CustomLineCap](../customlinecap/)
* 네임스페이스 [System::Drawing::Drawing2D](../)
* 라이브러리 [Aspose.Slides](../../)