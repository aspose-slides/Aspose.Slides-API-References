---
title: ITiming
second_title: Aspose.Slides for C++ API 참조
description: 애니메이션 타이밍을 나타냅니다.
type: docs
weight: 443
url: /ko/aspose.slides.animation/itiming/
---
## ITiming 클래스

애니메이션 타이밍을 나타냅니다.

```cpp
class ITiming : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부용입니다. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | 가속 행동 효과의 지속 시간 백분율을 나타냅니다. **float**을 읽습니다. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | 앞 방향으로 재생한 후 애니메이션을 자동으로 역방향으로 재생할지 여부를 나타냅니다. **bool**을 읽습니다. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | 감속 행동 효과의 지속 시간 백분율을 나타냅니다. **float**을 읽습니다. |
| virtual **float** [get_Duration](./get_duration/)() | 애니메이션 효과의 지속 시간을 나타냅니다. **float**을 읽습니다. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | 효과가 반복되어야 하는 횟수를 나타냅니다. **float**을 읽습니다. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | 효과가 반복되어야 하는 횟수를 나타냅니다. **float**을 읽습니다. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | 이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지 여부를 지정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | 이 속성은 효과가 다음 클릭까지 반복되는지 여부를 지정합니다. **bool**을 읽습니다. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | 효과가 완료된 후 재시작할지 여부를 지정합니다. [EffectRestartType](../effectrestarttype/)을(를) 읽습니다. |
| virtual **bool** [get_Rewind](./get_rewind/)() | 이 속성은 재생이 끝났을 때 효과를 뒤로 감을지 여부를 지정합니다. **bool**을 읽습니다. |
| virtual **float** [get_Speed](./get_speed/)() | 타이밍을 가속(또는 감속)할 비율을 백분율로 지정합니다. **float**을 읽습니다. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | 트리거 후 지연 시간을 나타냅니다. **float**을 읽습니다. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | 트리거 유형을 설명합니다. [EffectTriggerType](../effecttriggertype/)을(를) 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | 가속 행동 효과의 지속 시간 백분율을 나타냅니다. **float**을 씁니다. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | 앞 방향으로 재생한 후 애니메이션을 자동으로 역방향으로 재생할지 여부를 나타냅니다. **bool**을 씁니다. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | 감속 행동 효과의 지속 시간 백분율을 나타냅니다. **float**을 씁니다. |
| virtual void [set_Duration](./set_duration/)(**float**) | 애니메이션 효과의 지속 시간을 나타냅니다. **float**을 씁니다. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | 효과가 반복되어야 하는 횟수를 나타냅니다. **float**을 씁니다. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | 효과가 반복되어야 하는 횟수를 나타냅니다. **float**을 씁니다. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | 이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지 여부를 지정합니다. **bool**을 씁니다. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | 이 속성은 효과가 다음 클릭까지 반복되는지 여부를 지정합니다. **bool**을 씁니다. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | 효과가 완료된 후 재시작할지 여부를 지정합니다. [EffectRestartType](../effectrestarttype/)을(를) 씁니다. |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | 이 속성은 재생이 끝났을 때 효과를 뒤로 감을지 여부를 지정합니다. **bool**을 씁니다. |
| virtual void [set_Speed](./set_speed/)(**float**) | 타이밍을 가속(또는 감속)할 비율을 백분율로 지정합니다. **float**을 씁니다. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | 트리거 후 지연 시간을 나타냅니다. **float**을 씁니다. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | 트리거 유형을 설명합니다. [EffectTriggerType](../effecttriggertype/)을(를) 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* 라이브러리 [Aspose.Slides](../../)