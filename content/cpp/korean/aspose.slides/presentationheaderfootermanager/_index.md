---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션의 모든 바닥글, 날짜-시간 및 페이지 번호 자리표시자의 동작을 관리하는 관리자를 나타냅니다.
type: docs
weight: 4863
url: /ko/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager 클래스

프레젠테이션의 모든 바닥글, 날짜-시간 및 페이지 번호 자리 표시자의 동작을 보유하는 관리자를 나타냅니다.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 동등하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 동등하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | 마스터 슬라이드, 레이아웃 슬라이드, 슬라이드, 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | 마스터 슬라이드, 레이아웃 슬라이드, 슬라이드, 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | 마스터 슬라이드, 레이아웃 슬라이드, 슬라이드, 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 바닥글 자리 표시자에 텍스트를 설정합니다. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | 마스터 슬라이드, 레이아웃 슬라이드, 슬라이드, 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 바닥글 자리 표시자의 가시성을 변경합니다. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 머리글 자리 표시자에 텍스트를 설정합니다. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 머리글 자리 표시자의 가시성을 변경합니다. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | 마스터 슬라이드, 레이아웃 슬라이드, 슬라이드, 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있게 합니다. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | 모든 제목 슬라이드와 첫 레이아웃 슬라이드에 대한 바닥글, 날짜-시간 및 페이지 번호 자리 표시자의 가시성을 변경합니다. 제목 슬라이드 \\u2013 첫 레이아웃 슬라이드를 기반으로 하는 슬라이드(첫 레이아웃 유형에 관계없이). |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [BaseHeaderFooterManager](../baseheaderfootermanager/)
* 클래스 [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)