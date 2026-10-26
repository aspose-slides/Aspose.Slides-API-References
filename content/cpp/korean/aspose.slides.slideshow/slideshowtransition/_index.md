---
title: SlideShowTransition
second_title: Aspose.Slides for C++ API 참조
description: 슬라이드 쇼 전환을 나타냅니다.
type: docs
weight: 404
url: /ko/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition 클래스

슬라이드 쇼 전환을 나타냅니다.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## 메서드

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 두 [SlideShowTransition](./) 인스턴스가 동일한지 판단합니다. 읽기/쓰기 **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | 이 속성은 슬라이드 쇼가 일정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다. 읽기 **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | 전환이 시작될 시간(밀리초)을 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않으면 자동 진행이 발생하지 않는 것으로 간주됩니다. 읽기 **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | 마우스 클릭으로 슬라이드가 진행될지 여부를 지정합니다. 이 속성이 지정되지 않으면 true가 기본값으로 가정됩니다. 읽기 **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져옵니다. 읽기 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | 내장 오디오 데이터를 반환합니다. 읽기 [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | 이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true로 설정되면 생성 애플리케이션은 내장 사운드 목록에서 이 사운드에 지정된 name 속성을 확인하도록 알리고, 필요에 따라 사용자 지정 이름이나 UI를 표시할 수 있습니다. 읽기 **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | 이 속성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 루프될지 여부를 지정합니다. 읽기 **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. 읽기 [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | 전환 사운드의 사람 친화적인 이름을 지정합니다. 사운드 이름을 가져오거나 설정하려면 [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/)에 할당해야 합니다. 읽기 [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. 읽기 [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | 전환 유형입니다. 읽기 [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) 전환 값을 표시합니다. 읽기 전용 [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 특정 유형에 대한 해시 함수 역할을 하며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용할 수 있습니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | 이 속성은 슬라이드 쇼가 일정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다. 쓰기 **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | 전환이 시작될 시간(밀리초)을 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않으면 자동 진행이 발생하지 않는 것으로 가정됩니다. 쓰기 **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | 마우스 클릭으로 슬라이드가 진행될지 여부를 지정합니다. 이 속성이 지정되지 않으면 true가 기본값으로 가정됩니다. 쓰기 **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 설정합니다. 쓰기 **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | 내장 오디오 데이터를 설정합니다. 쓰기 [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | 이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true로 설정되면 생성 애플리케이션은 내장 사운드 목록에서 이 사운드에 지정된 name 속성을 확인하도록 알리고 필요에 따라 사용자 지정 이름이나 UI를 표시할 수 있습니다. 쓰기 **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | 이 속성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 루프될지 여부를 지정합니다. 쓰기 **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. 쓰기 [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | 전환 사운드의 사람 친화적인 이름을 지정합니다. 사운드 이름을 가져오거나 설정하려면 [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/)에 할당해야 합니다. 쓰기 [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. 쓰기 [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | 전환 유형입니다. 쓰기 [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [DomObject](../../aspose.slides/domobject/)
* 클래스 [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* 네임스페이스 [Aspose::Slides::SlideShow](../)
* 라이브러리 [Aspose.Slides](../../)