---
title: BulletFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 단락 글머리 기호 서식 속성을 나타냅니다.
type: docs
weight: 248
url: /ko/aspose.slides/bulletformat/
---
## BulletFormat 클래스

단락 글머리 기호 서식 속성을 나타냅니다.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | bullets가 활성화된 경우 (PowerPoint에서 단락 글머리 기호/번호 매기기를 활성화했을 때와 같이) 효과적인 단락 Indent와 MarginLeft에 대한 기본 비영(0이 아닌) 이동을 설정합니다. bullets가 비활성화된 경우 단순히 단락 Indent와 MarginLeft를 재설정합니다 (PowerPoint에서 단락 글머리 기호/번호 매기기를 비활성화했을 때와 같이). Indent 이동은 현재 글머리 기호 컨텍스트인 IBulletFormat::get(set)_Type, .NumberedBulletStyle 및 첫 번째 구간의 FontHeight를 기준으로 적용됩니다. 비영(0이 아닌) Indent 이동은 현재 단락의 효과적인 Indent와 MarginLeft에 적용되어 결과 값을 로컬 값으로 만듭니다. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 모든 값과, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 모든 값과, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| char16_t [get_Char](./get_char/)() override | 상속 없이 단락의 글머리 기호 문자를 반환합니다. **wchar_t**를 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | 상속 없이 단락의 글머리 기호 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | 상속 없이 단락의 글머리 기호 글꼴을 반환합니다. [IFontData](../ifontdata/)를 읽습니다. |
| **float** [get_Height](./get_height/)() override | 상속 없이 단락의 글머리 기호 높이를 반환합니다. 값 std::numeric_limits<float>::quiet_NaN()은 글머리 기호가 단락의 첫 번째 구간으로부터 높이를 상속함을 결정합니다. **float**를 읽습니다. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | 글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 구간으로부터 색상을 상속받는지 결정합니다. 글머리 기호가 자체 색상을 가지고 있으면 **[NullableBool::True](../nullablebool/)**, 첫 번째 구간으로부터 색상을 상속받으면 **[NullableBool::False](../nullablebool/)**. [NullableBool](../nullablebool/)를 읽습니다. |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | 글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 구간으로부터 글꼴을 상속받는지 결정합니다. 글머리 기호가 자체 글꼴을 가지고 있으면 **[NullableBool::True](../nullablebool/)**, 상속받으면 **[NullableBool::False](../nullablebool/)**. [NullableBool](../nullablebool/)를 읽습니다. |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | 상속 없이 번호가 매겨진 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환합니다. **int16_t**를 읽습니다. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | 상속 없이 번호가 매겨진 글머리 기호의 스타일을 반환합니다. [Slides::NumberedBulletStyle](../numberedbulletstyle/)를 읽습니다. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 상속 없이 단락에서 글머리 기호로 사용되는 그림을 반환합니다. 읽기 전용 [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | 상속 없이 단락의 글머리 기호 유형을 반환합니다. [BulletType](../bullettype/)를 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | 상속이 적용된 효과적인 글머리 기호 서식 데이터를 가져옵니다. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출에 해당합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자에 해당합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드에 해당합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Char](./set_char/)(char16_t) override | 상속 없이 단락의 글머리 기호 문자를 설정합니다. **wchar_t**를 씁니다. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 상속 없이 단락의 글머리 기호 글꼴을 설정합니다. [IFontData](../ifontdata/)를 씁니다. |
| void [set_Height](./set_height/)(**float**) override | 상속 없이 단락의 글머리 기호 높이를 설정합니다. 값 std::numeric_limits<float>::quiet_NaN()은 글머리 기호가 단락의 첫 번째 구간으로부터 높이를 상속함을 결정합니다. **float**를 씁니다. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | 글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 구간으로부터 색상을 상속받는지 결정합니다. 자체 색상이 있으면 **[NullableBool::True](../nullablebool/)**, 상속받으면 **[NullableBool::False](../nullablebool/)**. [NullableBool](../nullablebool/)를 씁니다. |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | 글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 구간으로부터 글꼴을 상속받는지 결정합니다. 자체 글꼴이 있으면 **[NullableBool::True](../nullablebool/)**, 상속받으면 **[NullableBool::False](../nullablebool/)**. [NullableBool](../nullablebool/)를 씁니다. |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | 상속 없이 번호가 매겨진 글머리 기호 그룹에 사용되는 첫 번째 번호를 설정합니다. **int16_t**를 씁니다. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | 상속 없이 번호가 매겨진 글머리 기호의 스타일을 설정합니다. [Slides::NumberedBulletStyle](../numberedbulletstyle/)를 씁니다. |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | 상속 없이 단락의 글머리 기호 유형을 설정합니다. [BulletType](../bullettype/)를 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드에 해당합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [PVIObject](../pviobject/)
* 클래스 [IBulletFormat](../ibulletformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)