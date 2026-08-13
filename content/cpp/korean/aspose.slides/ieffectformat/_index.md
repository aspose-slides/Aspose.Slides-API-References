---
title: IEffectFormat
second_title: Aspose.Slides for C++ API 참조
description: 도형의 효과 속성을 나타냅니다.
type: docs
weight: 2029
url: /ko/aspose.slides/ieffectformat/
---
## IEffectFormat 클래스

도형의 효과 속성을 나타냅니다.

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | 블러 효과를 비활성화합니다. |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | 채우기 오버레이 효과를 비활성화합니다. |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | 글로우 효과를 비활성화합니다. |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | 내부 그림자 효과를 비활성화합니다. |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | 외부 그림자 효과를 비활성화합니다. |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | 프리셋 그림자 효과를 비활성화합니다. |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | 반사 효과를 비활성화합니다. |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | 소프트 엣지 효과를 비활성화합니다. |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | 채우기 오버레이 효과를 활성화합니다. |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | 글로우 효과를 활성화합니다. |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | 내부 그림자 효과를 활성화합니다. |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | 외부 그림자 효과를 활성화합니다. |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | 프리셋 그림자 효과를 활성화합니다. |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | 반사 효과를 활성화합니다. |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | 소프트 엣지 효과를 활성화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN과도 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일의 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN과도 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일의 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | 블러 효과. [Effects::IBlur](../../aspose.slides.effects/iblur/) 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | 채우기 오버레이 효과. [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | 글로우 효과. [Effects::IGlow](../../aspose.slides.effects/iglow/) 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | 내부 그림자. [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) 읽기. |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | 모든 효과가 비활성화된 경우 true를 반환합니다(생성 직후 기본 [EffectFormat](../effectformat/) 객체와 같이). 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | 외부 그림자. [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | 프리셋 그림자. [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | 반사. [Effects::IReflection](../../aspose.slides.effects/ireflection/) 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | 소프트 엣지. [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) 읽기. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | 상속이 적용된 효과 서식 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 지정 객체의 해싱을 활성화합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 지정 타입 복제를 활성화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | 블러 효과. [Effects::IBlur](../../aspose.slides.effects/iblur/) 쓰기. |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | 채우기 오버레이 효과. [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) 쓰기. |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | 글로우 효과. [Effects::IGlow](../../aspose.slides.effects/iglow/) 쓰기. |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | 내부 그림자. [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) 쓰기. |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | 외부 그림자. [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) 쓰기. |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | 프리셋 그림자. [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) 쓰기. |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | 반사. [Effects::IReflection](../../aspose.slides.effects/ireflection/) 쓰기. |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | 소프트 엣지. [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) 쓰기. |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | 블러 효과를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 지정 객체를 문자열로 변환하도록 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IEffectParamSource](../ieffectparamsource/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)