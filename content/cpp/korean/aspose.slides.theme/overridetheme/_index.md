---
title: OverrideTheme
second_title: Aspose.Slides for C++ API 레퍼런스
description: 재정의 테마를 나타냅니다.
type: docs
weight: 547
url: /ko/aspose.slides.theme/overridetheme/
---
## OverrideTheme 클래스

재정의 테마를 나타냅니다.

```cpp
class OverrideTheme : public Aspose::Slides::Theme::Theme,
                      public Aspose::Slides::Theme::IOverrideTheme
```

## Methods

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() override | [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/)을 null로 설정하여 이 테마 객체와의 모든 재정의를 비활성화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](./get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](./get_colorscheme/)() override | 색 스키마를 반환합니다. 읽기 전용 [IColorScheme](../icolorscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](./get_fontscheme/)() override | 글꼴 스키마를 반환합니다. 읽기 전용 [IFontScheme](../ifontscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](./get_formatscheme/)() override | 도형 형식 스키마를 반환합니다. 읽기 전용 [IFormatScheme](../iformatscheme/). |
| **bool** [get_IsEmpty](./get_isempty/)() override | true 값은 [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/)이 null이며 이 테마 객체와의 모든 재정의가 비활성화됨을 의미합니다. 읽기 전용 **bool**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../theme/get_presentation/)() override | 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 자료 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../theme/geteffective/)() override | 상속이 적용된 효과적인 테마 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 형식을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| void [InitColorScheme](./initcolorscheme/)() override | InheritedTheme의 [ColorScheme](../colorscheme/) 재정의를 위해 새로운 객체로 [ColorScheme](../colorscheme/)를 초기화합니다. |
| void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) override | InheritedTheme의 [ColorScheme](../colorscheme/) 재정의를 위해 새로운 객체로 [ColorScheme](../colorscheme/)를 초기화합니다. |
| void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() override | InheritedTheme의 [ColorScheme](../colorscheme/) 재정의를 위해 새로운 객체로 [ColorScheme](../colorscheme/)를 초기화합니다. 그리고 이 새로운 객체의 데이터를 InheritedTheme의 [ColorScheme](../colorscheme/) 데이터로 초기화합니다. |
| void [InitFontScheme](./initfontscheme/)() override | InheritedTheme의 [FontScheme](../fontscheme/) 재정의를 위해 새로운 객체로 [FontScheme](../fontscheme/)를 초기화합니다. |
| void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) override | InheritedTheme의 [FontScheme](../fontscheme/) 재정의를 위해 새로운 객체로 [FontScheme](../fontscheme/)를 초기화합니다. |
| void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() override | InheritedTheme의 [FontScheme](../fontscheme/) 재정의를 위해 새로운 객체로 [FontScheme](../fontscheme/)를 초기화합니다. 그리고 이 새로운 객체의 데이터를 InheritedTheme의 [FontScheme](../fontscheme/) 데이터로 초기화합니다. |
| void [InitFormatScheme](./initformatscheme/)() override | InheritedTheme의 [FormatScheme](../formatscheme/) 재정의를 위해 새로운 객체로 [FormatScheme](../formatscheme/)를 초기화합니다. |
| void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) override | InheritedTheme의 [FormatScheme](../formatscheme/) 재정의를 위해 새로운 객체로 [FormatScheme](../formatscheme/)를 초기화합니다. |
| void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() override | InheritedTheme의 [FormatScheme](../formatscheme/) 재정의를 위해 새로운 객체로 [FormatScheme](../formatscheme/)를 초기화합니다. 그리고 이 새로운 객체의 데이터를 InheritedTheme의 [FormatScheme](../formatscheme/) 데이터로 초기화합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형을 복제할 수 있습니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제하는 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Theme](../theme/)
* 클래스 [IOverrideTheme](../ioverridetheme/)
* 네임스페이스 [Aspose::Slides::Theme](../)
* 라이브러리 [Aspose.Slides](../../)