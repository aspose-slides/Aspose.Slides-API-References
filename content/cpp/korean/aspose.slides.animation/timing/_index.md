---
title: Timing
second_title: Aspose.Slides for C++ API 참조
description: 애니메이션 타이밍을 나타냅니다.
type: docs
weight: 625
url: /ko/aspose.slides.animation/timing/
---
## Timing 클래스

애니메이션 타이밍을 나타냅니다.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 불구하고 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 불구하고 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **float** [get_Accelerate](./get_accelerate/)() override | 지속 시간 가속 동작 효과의 백분율을 설명합니다. **float**을 읽습니다. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | 전방으로 재생한 후 자동으로 역방향으로 재생할지 여부를 설명합니다. **bool**을 읽습니다. |
| **float** [get_Decelerate](./get_decelerate/)() override | 지속 시간 감속 동작 효과의 백분율을 설명합니다. **float**을 읽습니다. |
| **float** [get_Duration](./get_duration/)() override | 애니메이션 효과의 지속 시간을 설명합니다. **float**을 읽습니다. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | 효과가 반복되어야 하는 횟수를 설명합니다. **float**을 읽습니다. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | 효과가 반복되어야 하는 횟수를 설명합니다. **float**을 읽습니다. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | 이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지 지정합니다. **bool**을 읽습니다. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | 이 속성은 효과가 다음 클릭까지 반복되는지 지정합니다. **bool**을 읽습니다. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | 효과가 완료된 후 재시작되는지 지정합니다. [EffectRestartType](../effectrestarttype/)을 읽습니다. |
| **bool** [get_Rewind](./get_rewind/)() override | 이 속성은 재생이 끝났을 때 효과를 되감을지 지정합니다. **bool**을 읽습니다. |
| **float** [get_Speed](./get_speed/)() override | 타이밍을 가속(또는 감속)할 백분율을 지정합니다. **float**을 읽습니다. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | 트리거 후 지연 시간을 설명합니다. **float**을 읽습니다. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | 트리거 유형을 설명합니다. [EffectTriggerType](../effecttriggertype/)을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 형식을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 형식의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | 지속 시간 가속 동작 효과의 백분율을 설명합니다. **float**을 씁니다. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | 전방 재생 후 자동 역방향 재생 여부를 설명합니다. **bool**을 씁니다. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | 지속 시간 감속 동작 효과의 백분율을 설명합니다. **float**을 씁니다. |
| void [set_Duration](./set_duration/)(**float**) override | 애니메이션 효과의 지속 시간을 설명합니다. **float**을 씁니다. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | 효과가 반복되어야 하는 횟수를 설명합니다. **float**을 씁니다. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | 효과가 반복되어야 하는 횟수를 설명합니다. **float**을 씁니다. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | 이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지 지정합니다. **bool**을 씁니다. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | 이 속성은 효과가 다음 클릭까지 반복되는지 지정합니다. **bool**을 씁니다. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | 효과가 완료된 후 재시작되는지 지정합니다. [EffectRestartType](../effectrestarttype/)을 씁니다. |
| void [set_Rewind](./set_rewind/)(**bool**) override | 이 속성은 재생이 끝났을 때 효과를 되감을지 지정합니다. **bool**을 씁니다. |
| void [set_Speed](./set_speed/)(**float**) override | 타이밍을 가속(또는 감속)할 백분율을 지정합니다. **float**을 씁니다. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | 트리거 후 지연 시간을 설명합니다. **float**을 씁니다. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | 트리거 유형을 설명합니다. [EffectTriggerType](../effecttriggertype/)을 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 weak 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운터를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환하는 것을 가능하게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 참조 카운터를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [ITiming](../itiming/)
* 클래스 [IDOMObject](../../aspose.slides/idomobject/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* 라이브러리 [Aspose.Slides](../../)