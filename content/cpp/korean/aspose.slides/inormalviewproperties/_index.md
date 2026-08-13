---
title: INormalViewProperties
second_title: Aspose.Slides for C++ API 레퍼런스
description: "정규 보기 속성을 나타냅니다. 정규 보기는 슬라이드 자체, 측면 콘텐츠 영역, 하단 콘텐츠 영역의 세 가지 콘텐츠 영역으로 구성됩니다."
type: docs
weight: 2978
url: /ko/aspose.slides/inormalviewproperties/
---
## INormalViewProperties 클래스

정규 보기 속성을 나타냅니다. 정규 보기는 슬라이드 자체, 측면 콘텐츠 영역, 하단 콘텐츠 영역의 세 콘텐츠 영역으로 구성됩니다.

```cpp
class INormalViewProperties : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계로 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C#-style 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C#-style 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() | 수평 분할 막대가 표시될 상태를 지정합니다. 수평 분할 막대는 슬라이드를 슬라이드 아래의 콘텐츠 영역과 분리합니다. |
| virtual **bool** [get_PreferSingleView](./get_prefersingleview/)() | 사용자가 세 개의 콘텐츠 영역을 가진 표준 일반 보기 대신 전체 창 단일 콘텐츠 영역을 선호하는지 지정합니다. 활성화된 경우 애플리케이션은 전체 창에 하나의 콘텐츠 영역을 표시하도록 선택할 수 있습니다. **bool**를 읽습니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() | 이 요소는 영역이 최소화되지도 최대화되지도 않은 가변 복원 크기일 때 일반 보기의 측면 콘텐츠 영역 크기를 지정합니다. 읽기 전용 [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() | 이 요소는 영역이 최소화되지도 최대화되지도 않은 가변 복원 크기일 때 일반 보기의 상단 슬라이드 영역 크기를 지정합니다. 읽기 전용 [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() | 일반 보기 모드의 어느 콘텐츠 영역에서든 개요 콘텐츠를 표시할 경우 애플리케이션이 아이콘을 표시할지 여부를 지정합니다. **bool**를 읽습니다. |
| virtual **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() | 측면 영역이 충분히 작을 때 수직 분할기가 최소화 상태로 스냅되는지를 지정합니다. **bool**를 읽습니다. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() | 수직 분할 막대가 표시될 상태를 지정합니다. 수직 분할 막대는 슬라이드를 측면 콘텐츠 영역과 분리합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 락을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | 수평 분할 막대가 표시될 상태를 지정합니다. 수평 분할 막대는 슬라이드를 슬라이드 아래의 콘텐츠 영역과 분리합니다. |
| virtual void [set_PreferSingleView](./set_prefersingleview/)(**bool**) | 사용자가 세 개의 콘텐츠 영역을 가진 표준 일반 보기 대신 전체 창 단일 콘텐츠 영역을 선호하는지 지정합니다. 활성화된 경우 애플리케이션은 전체 창에 하나의 콘텐츠 영역을 표시하도록 선택할 수 있습니다. **bool**를 씁니다. |
| virtual void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) | 일반 보기 모드의 어느 콘텐츠 영역에서든 개요 콘텐츠를 표시할 경우 애플리케이션이 아이콘을 표시할지 여부를 지정합니다. **bool**를 씁니다. |
| virtual void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) | 측면 영역이 충분히 작을 때 수직 분할기가 최소화 상태로 스냅되는지를 지정합니다. **bool**를 씁니다. |
| virtual void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | 수직 분할 막대가 표시될 상태를 지정합니다. 수직 분할 막대는 슬라이드를 측면 콘텐츠 영역과 분리합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)