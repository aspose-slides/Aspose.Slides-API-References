---
title: IColorFormat
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에서 사용되는 색상을 나타냅니다.
type: docs
weight: 1691
url: /ko/aspose.slides/icolorformat/
---
## IColorFormat 클래스

프레젠테이션에서 사용되는 색상을 나타냅니다.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## 메서드

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | 색상 형식을 "color"에서 복사합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일의 부동소수점 비교를 흉내내며, IEC 60559:1989에 따르면 NaN은 어떤 값과도(NAN 포함) 같지 않지만 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동소수점 비교를 흉내내며, IEC 60559:1989에 따르면 NaN은 어떤 값과도(NAN 포함) 같지 않지만 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual **uint8_t** [get_B](./get_b/)() | 색상의 파란색 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | 모든 색상 변환이 적용된 결과 색상을 반환합니다. RGB 색상을 설정하고 모든 색상 변환을 지웁니다. 읽기 전용 [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | 지정된 인덱스의 색상에 적용된 색상 변환 작업을 반환합니다. 읽기/쓰기 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | 색상에 적용된 색상 변환 컬렉션을 반환합니다. 읽기 전용 [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | 색상 정의 방식을 반환합니다. 읽기 전용 [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | 색상의 파란색 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | 색상의 녹색 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | 색상의 빨간색 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | 색상의 녹색 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | HSL 표기에서 색상의 색상(Hue) 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | HSL 표기에서 색상의 휘도(Luminance) 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | 색상 프리셋을 반환합니다. 읽기 전용 [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | 색상의 빨간색 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | HSL 표기에서 색상의 채도(Saturation) 구성 요소를 반환합니다. 모든 색상 변환은 무시됩니다. 읽기 전용 **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | 색상 스킴에 의해 식별된 색상을 반환합니다. 읽기 전용 [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | 시스템 색상 테이블에 의해 식별된 색상을 반환합니다. 읽기 전용 [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_B](./set_b/)(**uint8_t**) | 색상의 파란색 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | 모든 색상 변환이 적용된 결과 색상을 반환합니다. RGB 색상을 설정하고 모든 색상 변환을 지웁니다. 쓰기 전용 [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | 지정된 인덱스의 색상에 적용된 색상 변환 작업을 설정합니다. 읽기/쓰기 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | 색상 정의 방식을 설정합니다. 쓰기 전용 [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | 색상의 파란색 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | 색상의 녹색 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | 색상의 빨간색 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | 색상의 녹색 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | HSL 표기에서 색상의 색상(Hue) 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | HSL 표기에서 색상의 휘도(Luminance) 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | 색상 프리셋을 설정합니다. 쓰기 전용 [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | 색상의 빨간색 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | HSL 표기에서 색상의 채도(Saturation) 구성 요소를 설정합니다. 모든 색상 변환은 무시됩니다. 쓰기 전용 **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | 색상 스킴에 의해 식별된 색상을 설정합니다. 쓰기 전용 [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | 시스템 색상 테이블에 의해 식별된 색상을 설정합니다. 쓰기 전용 [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | 현재 색상 형식을 나타내는 [System::String](../../system/string/)를 반환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IFillParamSource](../ifillparamsource/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)