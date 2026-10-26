---
title: IOuterShadow
second_title: Aspose.Slides for C++ API 레퍼런스
description: 외부 그림자 효과를 나타냅니다.
type: docs
weight: 885
url: /ko/aspose.slides.effects/ioutershadow/
---
## IOuterShadow 클래스

Represents an Outer Shadow effect.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 동일하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 동일하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 반경, 포인트 단위. 기본값 – 0 pt. 읽기 전용 **double**. |
| virtual **float** [get_Direction](./get_direction/)() | 그림자 방향, 단위는 도. 기본값 – 0 ° (왼쪽에서 오른쪽). 읽기 전용 **float**. |
| virtual **double** [get_Distance](./get_distance/)() | 그림자와 객체 사이 거리, 포인트 단위. 기본값 – 0 pt. 읽기 전용 **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 사각형 정렬. 기본값 – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). 읽기 전용 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | 그림자가 도형과 함께 회전하는지 여부를 나타냅니다. 기본값 – true. 읽기 전용 **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 수평 스케일링 계수, 원래 크기의 백분율. 음수 스케일링은 뒤집기를 유발합니다. 기본값 – 100 %. 읽기 전용 **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 수직 스케일링 계수, 원래 크기의 백분율. 음수 스케일링은 뒤집기를 유발합니다. 기본값 – 100 %. 읽기 전용 **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | 그림자 색상. 기본값 – 자동 검정(테마 의존). 읽기 전용 [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 수평 기울기 각도, 도 단위. 기본값 – 0 °. 읽기 전용 **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 수직 기울기 각도, 도 단위. 기본값 – 0 °. 읽기 전용 **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 상속이 적용된 유효 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 반경, 포인트 단위. 기본값 – 0 pt. 쓰기 전용 **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | 그림자 방향, 도 단위. 기본값 – 0 ° (왼쪽에서 오른쪽). 쓰기 전용 **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | 그림자와 객체 사이 거리, 포인트 단위. 기본값 – 0 pt. 쓰기 전용 **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 사각형 정렬. 기본값 – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). 쓰기 전용 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | 그림자가 도형과 함께 회전하는지 여부를 나타냅니다. 기본값 – true. 쓰기 전용 **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 수평 스케일링 계수, 원래 크기의 백분율. 음수 스케일링은 뒤집기를 유발합니다. 기본값 – 100 %. 쓰기 전용 **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 수직 스케일링 계수, 원래 크기의 백분율. 음수 스케일링은 뒤집기를 유발합니다. 기본값 – 100 %. 쓰기 전용 **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 수평 기울기 각도, 도 단위. 기본값 – 0 °. 쓰기 전용 **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 수직 기울기 각도, 도 단위. 기본값 – 0 °. 쓰기 전용 **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IImageTransformOperation](../iimagetransformoperation/)
* 클래스 [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 네임스페이스 [Aspose::Slides::Effects](../)
* 라이브러리 [Aspose.Slides](../../)