---
title: Effect
second_title: Aspose.Slides for C++ API 레퍼런스
description: 애니메이션 효과를 나타냅니다.
type: docs
weight: 118
url: /ko/aspose.slides.animation/effect/
---
## Effect 클래스

애니메이션 효과를 나타냅니다.

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN도 같지 않지만, 두 NaN을 같은 것으로 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN도 같지 않지만, 두 NaN을 같은 것으로 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | 효과에 대한 사후 애니메이션 색상을 정의합니다. 읽기 [IColorFormat](../../aspose.slides/icolorformat/). |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | 효과에 대한 사후 애니메이션 유형을 정의합니다. 읽기 [AfterAnimationType](../afteranimationtype/). |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | 효과에 대한 텍스트 애니메이션 유형을 정의합니다. 도형 텍스트는 글자별, 단어별 또는 전체를 한 번에 애니메이션 할 수 있습니다. 읽기 [AnimateTextType](../animatetexttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | 지정된 인덱스의 애니메이션 동작을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | 효과에 대한 동작 컬렉션을 반환합니다. 읽기 [IBehaviorCollection](../ibehaviorcollection/). |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | 애니메이션 텍스트 부분(단어 또는 글자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 비율을 지정하고, 음수 값은 초 단위의 지연을 지정합니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | 지정된 인덱스의 시퀀스 영향을 반환합니다. |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | 효과의 클래스를 정의합니다. 읽기 [EffectPresetClassType](../effectpresetclasstype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | 효과에 대한 시퀀스를 반환합니다. 읽기 전용 [ISequence](../isequence/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | 효과에 대한 임베디드 사운드를 정의합니다. 읽기 [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. 읽기 **bool**. |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | 효과의 하위 유형을 정의합니다. 읽기 [EffectSubtype](../effectsubtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | 효과의 대상 도형을 반환합니다. 읽기 전용 [IShape](../../aspose.slides/ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) 읽기 전용 [ITextAnimation](../itextanimation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | 효과의 타이밍 값을 정의합니다. 읽기 [ITiming](../itiming/). |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | 효과의 유형을 정의합니다. 읽기 [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사를 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사를 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | 효과에 대한 사후 애니메이션 색상을 정의합니다. 쓰기 [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | 효과에 대한 사후 애니메이션 유형을 정의합니다. 쓰기 [AfterAnimationType](../afteranimationtype/). |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | 효과에 대한 텍스트 애니메이션 유형을 정의합니다. 도형 텍스트는 글자별, 단어별 또는 전체를 한 번에 애니메이션 할 수 있습니다. 쓰기 [AnimateTextType](../animatetexttype/). |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | 지정된 인덱스의 애니메이션 동작을 설정합니다. |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | 효과에 대한 동작 컬렉션을 반환합니다. 쓰기 [IBehaviorCollection](../ibehaviorcollection/). |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | 애니메이션 텍스트 부분(단어 또는 글자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 비율을 지정하고, 음수 값은 초 단위의 지연을 지정합니다. 쓰기 **float**. |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | 효과의 클래스를 정의합니다. 쓰기 [EffectPresetClassType](../effectpresetclasstype/). |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | 효과에 대한 임베디드 사운드를 정의합니다. 쓰기 [IAudio](../../aspose.slides/iaudio/). |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. 쓰기 **bool**. |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | 효과의 하위 유형을 정의합니다. 쓰기 [EffectSubtype](../effectsubtype/). |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | 효과의 타이밍 값을 정의합니다. 쓰기 [ITiming](../itiming/). |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | 효과의 유형을 정의합니다. 쓰기 [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IEffect](../ieffect/)
* 클래스 [IDOMObject](../../aspose.slides/idomobject/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* Library [Aspose.Slides](../../)