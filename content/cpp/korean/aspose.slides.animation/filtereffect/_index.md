---
title: FilterEffect
second_title: Aspose.Slides for C++ API 레퍼런스
description: 동작의 필터 효과를 나타냅니다.
type: docs
weight: 131
url: /ko/aspose.slides.animation/filtereffect/
---
## FilterEffect 클래스

동작의 필터 효과를 나타냅니다.

```cpp
class FilterEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IFilterEffect
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
|  [FilterEffect](./filtereffect/)() | 기본 생성자. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | 애니메이션 동작이 누적되는지 여부를 나타냅니다. [NullableBool](../../aspose.slides/nullablebool/)를 읽으십시오. |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. [BehaviorAdditiveType](../behavioradditivetype/)를 읽으십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | 동작의 속성을 나타냅니다. 읽기 전용 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [FilterEffectRevealType](../filtereffectrevealtype/) [get_Reveal](./get_reveal/)() override | 동작이 포함된 효과가 표시(입력/출력)되어야 함을 나타냅니다. [FilterEffectRevealType](../filtereffectrevealtype/)를 읽으십시오. |
| [FilterEffectSubtype](../filtereffectsubtype/) [get_Subtype](./get_subtype/)() override | 필터 효과의 하위 유형을 나타냅니다. [FilterEffectSubtype](../filtereffectsubtype/)를 읽으십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | 효과 동작의 타이밍 속성을 나타냅니다. [ITiming](../itiming/)를 읽으십시오. |
| [FilterEffectType](../filtereffecttype/) [get_Type](./get_type/)() override | 필터 효과의 유형을 나타냅니다. [FilterEffectType](../filtereffecttype/)를 읽으십시오. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스를 복사 구성할 수 있게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스를 복사 구성할 수 있게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | 애니메이션 동작이 누적되는지 여부를 나타냅니다. [NullableBool](../../aspose.slides/nullablebool/)에 기록합니다. |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. [BehaviorAdditiveType](../behavioradditivetype/)에 기록합니다. |
| void [set_Reveal](./set_reveal/)([FilterEffectRevealType](../filtereffectrevealtype/)) override | 동작이 포함된 효과가 표시(입력/출력)되어야 함을 나타냅니다. [FilterEffectRevealType](../filtereffectrevealtype/)에 기록합니다. |
| void [set_Subtype](./set_subtype/)([FilterEffectSubtype](../filtereffectsubtype/)) override | 필터 효과의 하위 유형을 나타냅니다. [FilterEffectSubtype](../filtereffectsubtype/)에 기록합니다. |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | 효과 동작의 타이밍 속성을 나타냅니다. [ITiming](../itiming/)에 기록합니다. |
| void [set_Type](./set_type/)([FilterEffectType](../filtereffecttype/)) override | 필터 효과의 유형을 나타합니다. [FilterEffectType](../filtereffecttype/)에 기록합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현한 잠금 해제입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Behavior](../behavior/)
* 클래스 [IFilterEffect](../ifiltereffect/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* 라이브러리 [Aspose.Slides](../../)