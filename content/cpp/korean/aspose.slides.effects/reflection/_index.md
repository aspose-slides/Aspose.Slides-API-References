---
title: Reflection
second_title: Aspose.Slides C++용 API 레퍼런스
description: Reflection 효과를 나타냅니다.
type: docs
weight: 1067
url: /ko/aspose.slides.effects/reflection/
---
## Reflection 클래스

[Reflection](./) 효과를 나타냅니다.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Methods

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 [Reflection](./)가 현재 [Reflection](./)와 같은지 여부를 결정합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) 반지름. 읽기 **double**. |
| **float** [get_Direction](./get_direction/)() override | 반사의 방향. 읽기 **float**. |
| **double** [get_Distance](./get_distance/)() override | 반사 거리. 읽기 **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | 끝 알파 값(퍼센트)의 끝 위치(알파 그라디언트 램프를 따라)를 지정합니다. 읽기 **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | 끝 반사 불투명도(퍼센트). 읽기 **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | 반사를 오프셋할 방향(각도)을 지정합니다. 읽기 **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 사각형 정렬. 읽기 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | 도형이 회전될 경우 반사도 도형과 함께 회전해야 하는지 여부를 지정합니다. 읽기 **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 유발합니다(퍼센트). 읽기 **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 유발합니다(퍼센트). 읽기 **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | 수평 왜곡 각도를 지정합니다. 읽기 **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | 수직 왜곡 각도를 지정합니다. 읽기 **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | 시작 알파 값(퍼센트)의 시작 위치(알파 그라디언트 램프를 따라)를 지정합니다. 읽기 **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | 시작 반사 불투명도(퍼센트). 읽기 **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | 버전. 읽기 전용 **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | 상속이 적용된 효과적인 [Reflection](./) 효과 데이터를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 특정 유형에 대한 해시 함수 역할을 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열 및 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) 반지름. 쓰기 **double**. |
| void [set_Direction](./set_direction/)(**float**) override | 반사의 방향. 쓰기 **float**. |
| void [set_Distance](./set_distance/)(**double**) override | 반사 거리. 쓰기 **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | 끝 알파 값(퍼센트)의 끝 위치(알파 그라디언트 램프를 따라)를 지정합니다. 쓰기 **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | 끝 반사 불투명도(퍼센트). 쓰기 **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | 반사를 오프셋할 방향(각도)을 지정합니다. 쓰기 **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 사각형 정렬. 쓰기 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | 도형이 회전될 경우 반사도 도형과 함께 회전해야 하는지 여부를 지정합니다. 쓰기 **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 유발합니다(퍼센트). 쓰기 **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 유발합니다(퍼센트). 쓰기 **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | 수평 왜곡 각도를 지정합니다. 쓰기 **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | 수직 왜곡 각도를 지정합니다. 쓰기 **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | 시작 알파 값(퍼센트)의 시작 위치(알파 그라디언트 램프를 따라)를 지정합니다. 쓰기 **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | 시작 반사 불투명도(퍼센트). 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IReflection](../ireflection/)
* 클래스 [IVisualEffect](../ivisualeffect/)
* 클래스 [IPVIObject](../../aspose.slides/ipviobject/)
* 네임스페이스 [Aspose::Slides::Effects](../)
* 라이브러리 [Aspose.Slides](../../)