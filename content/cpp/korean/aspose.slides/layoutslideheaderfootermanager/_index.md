---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드 푸터, 날짜-시간, 페이지 번호 자리 표시자 및 모든 하위 자리 표시자의 동작을 관리하는 매니저를 나타냅니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다.
type: docs
weight: 4317
url: /ko/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager 클래스


Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | 날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다. Read**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | 푸터 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | 페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경계 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | 레이아웃 슬라이드 날짜-시간 자리 표시자 및 모든 하위 날짜-시간 자리 표시자에 텍스트를 설정합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | 레이아웃 슬라이드 날짜-시간 자리 표시자 및 모든 하위 날짜-시간 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | 슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | 슬라이드 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | 레이아웃 슬라이드 푸터 자리 표시자 및 모든 하위 푸터 자리 표시자에 텍스트를 설정합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | 레이아웃 슬라이드 푸터 자리 표시자 및 모든 하위 푸터 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 마스터 슬라이드를 사용하고 의존합니다. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | 슬라이드 푸터 자리 표시자에 텍스트를 설정합니다. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | 슬라이드 푸터 자리 표시자의 가시성을 변경합니다. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | 레이아웃 슬라이드 페이지 번호 자리 표시자 및 모든 하위 페이지 번호 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | 슬라이드 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경계 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* 클래스 [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)