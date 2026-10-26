---
title: ParagraphFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 클래스는 단락 서식 속성을 포함합니다. IParagraphFormatEffectiveData와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 4668
url: /ko/aspose.slides/paragraphformat/
---
## ParagraphFormat 클래스

This class contains the paragraph formatting properties. Unlike [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), all properties of this class are writeable.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | 상속 없이 단락의 텍스트 정렬을 반환합니다. [TextAlignment](../textalignment/)를 읽으세요. |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | 상속 없이 기본 탭 크기를 반환합니다. **float**를 읽으세요. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | 단락에서 동아시아 줄바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | 상속 없이 단락의 글꼴 정렬을 반환합니다. [Slides::FontAlignment](../fontalignment/)를 읽으세요. |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | 단락에서 걸리는 구두점이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| **float** [get_Indent](./get_indent/)() override | 상속 없이 단락의 첫 줄 들여쓰기/걸린 들여쓰기 값을 반환합니다. 걸린 들여쓰기는 음수 값으로 정의될 수 있습니다. **float**를 읽으세요. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | 단락에서 라틴 줄바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| **float** [get_MarginLeft](./get_marginleft/)() override | 상속 없이 단락의 왼쪽 여백을 반환합니다. **float**를 읽으세요. |
| **float** [get_MarginRight](./get_marginright/)() override | 상속 없이 단락의 오른쪽 여백을 반환합니다. **float**를 읽으세요. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | 상속 없이 단락의 마지막 줄 뒤 공간 양을 반환합니다. 양수 값은 공백이 글꼴 크기의 백분율임을 지정하고, 음수 값은 포인트 단위로 크기를 지정합니다. **float**를 읽으세요. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | 상속 없이 단락의 첫 줄 앞 공간 양을 반환합니다. 양수 값은 공백이 글꼴 크기의 백분율임을 지정하고, 음수 값은 포인트 단위로 크기를 지정합니다. **float**를 읽으세요. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | 단락의 기본 줄 사이 공간 양을 반환합니다. 양수 값은 백분율을 의미하고, 음수 값은 포인트 단위 크기를 의미합니다. 상속이 적용되지 않습니다. **float**를 읽으세요. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | 지정된 인덱스의 단락 탭을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [Aspose::Slides::ITab](../itab/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | 단락의 탭들을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | 상속이 적용된 효과적인 단락 서식 데이터를 가져옵니다. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 기능입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 기능입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 복사 할당 연산자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
|  [ParagraphFormat](./paragraphformat/)() | [ParagraphFormat](./) 클래스의 새 인스턴스를 초기화합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | 상속 없이 단락의 텍스트 정렬을 설정합니다. [TextAlignment](../textalignment/)를 씁니다. |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | 상속 없이 기본 탭 크기를 설정합니다. **float**를 씁니다. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | 단락에서 동아시아 줄바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 씁니다. |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | 상속 없이 단락의 글꼴 정렬을 설정합니다. [Slides::FontAlignment](../fontalignment/)를 씁니다. |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | 단락에서 걸리는 구두점이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 씁니다. |
| void [set_Indent](./set_indent/)(**float**) override | 상속 없이 단락의 첫 줄 들여쓰기/걸린 들여쓰기를 설정합니다. 걸린 들여쓰기는 음수 값으로 정의될 수 있습니다. **float**를 씁니다. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | 단락에서 라틴 줄바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 씁니다. |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | 상속 없이 단락의 왼쪽 여백을 설정합니다. **float**를 씁니다. |
| void [set_MarginRight](./set_marginright/)(**float**) override | 상속 없이 단락의 오른쪽 여백을 설정합니다. **float**를 씁니다. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 씁니다. |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | 상속 없이 단락의 마지막 줄 뒤 공간 양을 설정합니다. 양수 값은 공백이 글꼴 크기의 백분율임을 지정하고, 음수 값은 포인트 단위로 크기를 지정합니다. **float**를 씁니다. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | 상속 없이 단락의 첫 줄 앞 공간 양을 설정합니다. 양수 값은 공백이 글꼴 크기의 백분율임을 지정하고, 음수 값은 포인트 단위로 크기를 지정합니다. **float**를 씁니다. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | 단락의 기본 줄 사이 공간 양을 설정합니다. 양수 값은 백분율을 의미하고, 음수 값은 포인트 단위 크기를 의미합니다. 상속이 적용되지 않습니다. **float**를 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 비고

This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [ParagraphFormat::GetEffective](./geteffective/) method which returns a [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) instance.

## 참고

* 클래스 [PVIObject](../pviobject/)
* 클래스 [IParagraphFormat](../iparagraphformat/)
* 클래스 [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)