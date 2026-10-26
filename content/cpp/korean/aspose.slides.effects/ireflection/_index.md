---
title: IReflection
second_title: Aspose.Slides for C++ API 레퍼런스
description: 반사 효과를 나타냅니다.
type: docs
weight: 937
url: /ko/aspose.slides.effects/ireflection/
---
## IReflection 클래스


반사 효과를 나타냅니다.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 반경. 읽기 **double**. |
| virtual **float** [get_Direction](./get_direction/)() | 반사의 방향. 읽기 **float**. |
| virtual **double** [get_Distance](./get_distance/)() | 반사 거리. 읽기 **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | 끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. 읽기 **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | 끝 반사 불투명도. (퍼센트) 읽기 **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | 반사를 오프셋할 방향을 지정합니다. (각도) 읽기 **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 사각형 정렬. 읽기 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | 모양이 회전될 경우 반사가 모양과 함께 회전해야 하는지를 지정합니다. 읽기 **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 읽기 **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 읽기 **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 수평 스큐 각도를 지정합니다. 읽기 **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 수직 스큐 각도를 지정합니다. 읽기 **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | 시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. 읽기 **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | 시작 반사 불투명도. (퍼센트) 읽기 **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 상속이 적용된 유효 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 반경. 쓰기 **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | 반사의 방향. 쓰기 **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | 반사 거리. 쓰기 **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | 끝 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 끝 위치를 지정합니다. 쓰기 **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | 끝 반사 불투명도. (퍼센트) 쓰기 **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | 반사를 오프셋할 방향을 지정합니다. (각도) 쓰기 **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 사각형 정렬. [RectangleAlignment](../../aspose.slides/rectanglealignment/) 쓰기. |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | 모양이 회전될 경우 반사가 모양과 함께 회전해야 하는지를 지정합니다. 쓰기 **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 수평 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 쓰기 **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 수직 스케일링 계수를 지정합니다. 음수 스케일링은 뒤집기를 초래합니다. (퍼센트) 쓰기 **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 수평 스큐 각도를 지정합니다. 쓰기 **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 수직 스큐 각도를 지정합니다. 쓰기 **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | 시작 알파 값(퍼센트)의 알파 그라디언트 램프를 따라 시작 위치를 지정합니다. 쓰기 **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | 시작 반사 불투명도. (퍼센트) 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IImageTransformOperation](../iimagetransformoperation/)
* 클래스 [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 네임스페이스 [Aspose::Slides::Effects](../)
* 라이브러리 [Aspose.Slides](../../)