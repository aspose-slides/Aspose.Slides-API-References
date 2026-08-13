---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for C++ API 레퍼런스
description: 마스터 노트 슬라이드 푸터, 날짜-시간, 페이지 번호 자리 표시자 및 모든 자식 자리 표시자의 동작을 보유하는 관리자를 나타냅니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.
type: docs
weight: 2900
url: /ko/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager 클래스

마스터 노트 슬라이드 푸터, 날짜-시간, 페이지 번호 자리 표시자와 모든 자식 자리 표시자의 동작을 보유하는 관리자를 나타냅니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | 날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | 푸터 자리 표시자가 존재함을 나타내는 값을 가져옵니다. Read **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | 헤더 자리 표시자가 존재함을 나타내는 값을 가져옵니다. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | 페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 활성화합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# ‘is’ 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 클론을 활성화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | 마스터 노트 슬라이드 날짜-시간 자리 표시자와 모든 자식 날짜-시간 자리 표시자에 텍스트를 설정합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | 마스터 노트 슬라이드 날짜-시간 자리 표시자와 모든 자식 날짜-시간 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | 슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | 슬라이드 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | 마스터 노트 슬라이드 푸터 자리 표시자와 모든 자식 푸터 자리 표시자에 텍스트를 설정합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | 마스터 노트 슬라이드 푸터 자리 표시자와 모든 자식 푸터 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | 슬라이드 푸터 자리 표시자에 텍스트를 설정합니다. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | 슬라이드 푸터 자리 표시자의 가시성을 변경합니다. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | 마스터 노트 슬라이드 헤더 자리 표시자와 모든 자식 헤더 자리 표시자에 텍스트를 설정합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | 마스터 노트 슬라이드 헤더 자리 표시자와 모든 자식 헤더 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | 슬라이드 헤더 자리 표시자에 텍스트를 설정합니다. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | 슬라이드 헤더 자리 표시자의 가시성을 변경합니다. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | 마스터 노트 슬라이드 페이지 번호 자리 표시자와 모든 자식 페이지 번호 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | 슬라이드 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환하는 것을 활성화합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)