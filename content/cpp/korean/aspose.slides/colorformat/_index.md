---
title: ColorFormat
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에서 사용되는 색을 나타냅니다.
type: docs
weight: 339
url: /ko/aspose.slides/colorformat/
---
## ColorFormat 클래스

프레젠테이션에서 사용되는 색을 나타냅니다.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | "color"에서 색 형식을 복사합니다. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와의 동일성을 검사합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 불구하고 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 불구하고 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **uint8_t** [get_B](./get_b/)() override | 색의 파란색 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | 모든 색 변환을 적용한 결과 색을 반환합니다. RGB 색을 설정하고 모든 색 변환을 지웁니다. 읽기 [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | 지정된 인덱스의 색에 적용된 색 변환 연산을 반환합니다. 읽기/쓰기 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | 색에 적용된 색 변환 컬렉션을 반환합니다. 읽기 전용 [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | 색 정의 방식을 반환합니다. 읽기 [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | 색의 파란색 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **float**. |
| **float** [get_FloatG](./get_floatg/)() override | 색의 녹색 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **float**. |
| **float** [get_FloatR](./get_floatr/)() override | 색의 빨간색 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **float**. |
| **uint8_t** [get_G](./get_g/)() override | 색의 녹색 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. |
| **float** [get_Hue](./get_hue/)() override | 색의 HSL 표현에서 색조 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **float**. |
| **float** [get_Luminance](./get_luminance/)() override | 색의 HSL 표현에서 명도 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | 색 사전 설정을 반환합니다. 읽기 [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | 색의 빨간색 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | 색의 HSL 표현에서 채도 구성 요소를 반환합니다. 모든 색 변환은 무시됩니다. 읽기 **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | 색 구성표에 의해 식별된 색을 반환합니다. 읽기 [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | 시스템 색 표에 의해 식별된 색을 반환합니다. 읽기 [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_B](./set_b/)(**uint8_t**) override | 색의 파란색 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | 모든 색 변환을 적용한 결과 색을 반환합니다. RGB 색을 설정하고 모든 색 변환을 지웁니다. 쓰기 [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | 지정된 인덱스의 색에 적용된 색 변환 연산을 설정합니다. 읽기/쓰기 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | 색 정의 방식을 설정합니다. 쓰기 [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | 색의 파란색 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | 색의 녹색 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | 색의 빨간색 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | 색의 녹색 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. |
| void [set_Hue](./set_hue/)(**float**) override | HSL 표현에서 색의 색조 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | HSL 표현에서 색의 명도 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | 색 사전 설정을 설정합니다. 쓰기 [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | 색의 빨간색 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | HSL 표현에서 색의 채도 구성 요소를 설정합니다. 모든 색 변환은 무시됩니다. 쓰기 **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | 색 구성표에 의해 식별된 색을 설정합니다. 쓰기 [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | 시스템 색 표에 의해 식별된 색을 설정합니다. 쓰기 [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 포인터가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | 현재 색 형식을 나타내는 [System::String](../../system/string/)를 반환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터와 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [PVIObject](../pviobject/)
* 클래스 [IColorFormat](../icolorformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)