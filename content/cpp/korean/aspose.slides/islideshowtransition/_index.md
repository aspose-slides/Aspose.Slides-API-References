---
title: ISlideShowTransition
second_title: Aspose.Slides for C++ API 참조
description: 슬라이드 쇼 전환을 나타냅니다.
type: docs
weight: 3810
url: /ko/aspose.slides/islideshowtransition/
---
## ISlideShowTransition 클래스

Represents slide show transition.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 개체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 개체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 개체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않음에도 불구하고 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않음에도 불구하고 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | 이 특성은 슬라이드 쇼가 일정 시간 후 다음 슬라이드로 이동할지 여부를 지정합니다. 읽기 **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | 전환이 시작되어야 하는 시간을 밀리초 단위로 지정합니다. 이 설정은 advClick 특성과 함께 사용할 수 있습니다. 이 특성이 지정되지 않으면 자동 진행이 발생하지 않는 것으로 간주됩니다. 읽기 **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | 마우스 클릭이 슬라이드를 진행시킬지 여부를 지정합니다. 이 특성이 지정되지 않으면 true 값이 가정됩니다. 읽기 **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져옵니다. 읽기 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | 내장된 오디오 데이터를 반환합니다. 읽기 [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | 이 사운드가 내장 사운드인지 여부를 지정합니다. 이 특성이 true로 설정되면, 생성 애플리케이션은 내장 사운드 목록에서 이 사운드에 지정된 name 특성을 확인하도록 알리고 필요에 따라 사용자 지정 이름이나 UI를 표시할 수 있습니다. 읽기 **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | 이 특성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 루프되는지 여부를 지정합니다. 읽기 **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. 읽기 [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | 전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. 사운드 이름을 가져오거나 설정하려면 [ISlideShowTransition::set_Sound](./set_sound/)을 할당해야 합니다. 읽기 [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용될 전환 속도를 지정합니다. 읽기 [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | 전환 유형입니다. 읽기 [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) 쇼 전환 값을 반환합니다. 읽기 전용 [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | 이 특성은 슬라이드 쇼가 일정 시간 후 다음 슬라이드로 이동할지 여부를 지정합니다. 쓰기 **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | 전환이 시작되어야 하는 시간을 밀리초 단위로 지정합니다. 이 설정은 advClick 특성과 함께 사용할 수 있습니다. 이 특성이 지정되지 않으면 자동 진행이 발생하지 않는 것으로 간주됩니다. 쓰기 **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | 마우스 클릭이 슬라이드를 진행시킬지 여부를 지정합니다. 이 특성이 지정되지 않으면 true 값이 가정됩니다. 쓰기 **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 설정합니다. 쓰기 **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | 내장 오디오 데이터를 설정합니다. 쓰기 [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | 이 사운드가 내장 사운드인지 여부를 지정합니다. 이 특성이 true로 설정되면, 생성 애플리케이션은 내장 사운드 목록에서 이 사운드에 지정된 name 특성을 확인하도록 알리고 필요에 따라 사용자 지정 이름이나 UI를 표시할 수 있습니다. 쓰기 **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | 이 특성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 루프되는지 여부를 지정합니다. 쓰기 **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. 쓰기 [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | 전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. 사운드 이름을 가져오거나 설정하려면 [ISlideShowTransition::set_Sound](./set_sound/)를 할당해야 합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용될 전환 속도를 지정합니다. 쓰기 [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | 전환 유형입니다. 쓰기 [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)