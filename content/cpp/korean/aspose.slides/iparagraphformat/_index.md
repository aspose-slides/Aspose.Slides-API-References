---
title: IParagraphFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 클래스는 단락 서식 속성을 포함합니다. IParagraphFormatEffectiveData와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 3147
url: /ko/aspose.slides/iparagraphformat/
---
## IParagraphFormat 클래스


이 클래스는 단락 서식 속성을 포함합니다. [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

```cpp
class IParagraphFormat : public virtual System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN은 동일하다고 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN은 동일하다고 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | 상속 없이 단락의 텍스트 정렬을 반환합니다. [TextAlignment](../textalignment/)를 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | 단락의 글머리표 형식을 반환합니다. 읽기 전용 [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | 단락의 기본 부분 형식을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | 상속 없이 기본 탭 크기를 반환합니다. **float** 읽기. |
| virtual **int16_t** [get_Depth](./get_depth/)() | 단락의 깊이를 반환합니다. 값 0은 정의되지 않은 값을 의미합니다. **int16_t** 읽기. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 단락에서 동아시아 줄 바꿈이 사용되는지 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 상속 없이 단락의 글꼴 정렬을 반환합니다. [Slides::FontAlignment](../fontalignment/)를 읽으세요. |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 단락에서 행잉 구두점이 사용되는지 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| virtual **float** [get_Indent](./get_indent/)() | 상속 없이 단락의 첫 줄 들여쓰기/행잉 들여쓰기를 반환합니다. 행잉 들여쓰기는 음수 값으로 정의할 수 있습니다. **float** 읽기. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 단락에서 라틴 줄 바꿈이 사용되는지 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 상속 없이 단락의 왼쪽 여백을 반환합니다. **float** 읽기. |
| virtual **float** [get_MarginRight](./get_marginright/)() | 상속 없이 단락의 오른쪽 여백을 반환합니다. **float** 읽기. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/)를 읽으세요. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 상속 없이 단락의 마지막 줄 뒤 공백 양을 반환합니다. 양수 값은 글꼴 크기의 백분율을, 음수 값은 포인트 크기로 공백 크기를 지정합니다. **float** 읽기. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 상속 없이 단락의 첫 줄 앞 공백 양을 반환합니다. 양수 값은 글꼴 크기의 백분율을, 음수 값은 포인트 크기로 공백 크기를 지정합니다. **float** 읽기. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 단락의 기준선 사이 공백 양을 반환합니다. 양수 값은 백분율을, 음수 값은 포인트 크기를 의미합니다. 상속이 적용되지 않습니다. **float** 읽기. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 지정된 인덱스에서 단락의 탭을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | 단락의 탭들을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | 상속이 적용된 효과적인 단락 서식 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | 상속 없이 단락의 텍스트 정렬을 설정합니다. [TextAlignment](../textalignment/) 쓰기. |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | 상속 없이 기본 탭 크기를 설정합니다. **float** 쓰기. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | 단락의 깊이를 설정합니다. 값 0은 정의되지 않은 값을 의미합니다. **int16_t** 쓰기. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | 단락에서 동아시아 줄 바꿈 사용 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/) 쓰기. |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | 상속 없이 단락의 글꼴 정렬을 설정합니다. [Slides::FontAlignment](../fontalignment/) 쓰기. |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | 단락에서 행잉 구두점 사용 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/) 쓰기. |
| virtual void [set_Indent](./set_indent/)(**float**) | 상속 없이 단락의 첫 줄 들여쓰기/행잉 들여쓰기를 설정합니다. 행잉 들여쓰기는 음수 값으로 정의할 수 있습니다. **float** 쓰기. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | 단락에서 라틴 줄 바꿈 사용 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/) 쓰기. |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 상속 없이 단락의 왼쪽 여백을 설정합니다. **float** 쓰기. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 상속 없이 단락의 오른쪽 여백을 설정합니다. **float** 쓰기. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | 단락에서 오른쪽에서 왼쪽 쓰기 사용 여부를 결정합니다. 상속이 적용되지 않습니다. [NullableBool](../nullablebool/) 쓰기. |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 상속 없이 단락의 마지막 줄 뒤 공백 양을 설정합니다. 양수 값은 글꼴 크기의 백분율을, 음수 값은 포인트 크기로 공백 크기를 지정합니다. **float** 쓰기. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 상속 없이 단락의 첫 줄 앞 공백 양을 설정합니다. 양수 값은 글꼴 크기의 백분율을, 음수 값은 포인트 크기로 공백 크기를 지정합니다. **float** 쓰기. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 단락의 기준선 사이 공백 양을 설정합니다. 양수 값은 백분율을, 음수 값은 포인트 크기를 의미합니다. 상속이 적용되지 않습니다. **float** 쓰기. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(**uint32_t**)로 설정합니다(공유 대신). 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

이 클래스는 특정 단락에 정의된 단락 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으며, 대부분의 경우 "정의되지 않음" 값을 얻게 됨을 의미합니다.

상속을 포함한 실제 서식 매개변수 값을 얻으려면 [IParagraphFormat::GetEffective](./geteffective/) 메서드를 사용해야 하며, 이 메서드는 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 인스턴스를 반환합니다.

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)