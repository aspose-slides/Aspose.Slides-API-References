---
title: IBulletFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 단락 글머리 기호 서식 특성을 나타냅니다.
type: docs
weight: 1561
url: /ko/aspose.slides/ibulletformat/
---
## IBulletFormat 클래스

단락 글머리 기호 서식 특성을 나타냅니다.

```cpp
class IBulletFormat : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | 글머리 기호가 활성화된 경우(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 활성화하면) 효과적인 단락 Indent 및 MarginLeft에 대한 기본 비영(zero가 아닌) 이동을 설정합니다. 글머리 기호가 비활성화된 경우에는 단락 Indent 및 MarginLeft를 단순히 재설정합니다(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 비활성화하면). Indent 이동은 현재 글머리 기호 컨텍스트 — IBulletFormat::get(set)_Type, .NumberedBulletStyle 및 첫 부분의 FontHeight — 에 따라 적용됩니다. 비영인 Indent 이동은 현재 단락의 효과적인 Indent 및 MarginLeft에 적용되어 결과 값을 로컬 값으로 만들게 합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따라 어떤 값과도(심지어 NaN과도) 같지 않음에도 불구하고 C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따라 어떤 값과도(심지어 NaN과도) 같지 않음에도 불구하고 C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual char16_t [get_Char](./get_char/)() | 단락의 글머리 기호 문자를 상속 없이 반환합니다. 읽기 **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | 단락의 글머리 기호 색상 형식을 상속 없이 반환합니다. 읽기 전용 [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | 단락의 글머리 기호 글꼴을 상속 없이 반환합니다. 읽기 [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | 단락의 글머리 기호 높이를 상속 없이 반환합니다. 값 std::numeric_limits<float>::quiet_NaN()은 글머리 기호가 단락 첫 부분의 높이를 상속한다는 것을 나타냅니다. 읽기 **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | 글머리 기호가 자체 색상을 가지는지 또는 단락 첫 부분에서 색상을 상속받는지 결정합니다. 글머리 기호가 자체 색상을 가지면 **[NullableBool::True](../nullablebool/)**, 단락 첫 부분에서 색상을 상속받으면 **[NullableBool::False](../nullablebool/)**를 반환합니다. 읽기 [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | 글머리 기호가 자체 글꼴을 가지는지 또는 단락 첫 부분에서 글꼴을 상속받는지 결정합니다. 글머리 기호가 자체 글꼴을 가지면 **[NullableBool::True](../nullablebool/)**, 단락 첫 부분에서 글꼴을 상속받으면 **[NullableBool::False](../nullablebool/)**를 반환합니다. 읽기 [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | 상속 없이 번호 매긴 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환합니다. 읽기 **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | 상속 없이 번호 매긴 글머리 기호의 스타일을 반환합니다. 읽기 [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 상속 없이 단락에서 글머리 기호로 사용되는 그림을 반환합니다. 읽기 전용 [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | 상속 없이 단락의 글머리 기호 유형을 반환합니다. 읽기 [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | 상속이 적용된 효과적인 글머리 기호 서식 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문과 같은 잠금 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며 새 객체를 초기화하고 서브클래스의 복제 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않으며 새 객체를 초기화하고 서브클래스의 복제 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Char](./set_char/)(char16_t) | 상속 없이 단락의 글머리 기호 문자를 설정합니다. 쓰기 **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 상속 없이 단락의 글머리 기호 글꼴을 설정합니다. 쓰기 [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | 상속 없이 단락의 글머리 기호 높이를 설정합니다. 값 std::numeric_limits<float>::quiet_NaN()은 글머리 기호가 단락 첫 부분의 높이를 상속한다는 것을 나타냅니다. 쓰기 **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | 글머리 기호가 자체 색상을 가지는지 또는 단락 첫 부분에서 색상을 상속받는지 결정합니다. 자체 색상을 가지면 **[NullableBool::True](../nullablebool/)**, 단락 첫 부분에서 색상을 상속받으면 **[NullableBool::False](../nullablebool/)**를 설정합니다. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | 글머리 기호가 자체 글꼴을 가지는지 또는 단락 첫 부분에서 글꼴을 상속받는지 결정합니다. 자체 글꼴을 가지면 **[NullableBool::True](../nullablebool/)**, 단락 첫 부분에서 글꼴을 상속받으면 **[NullableBool::False](../nullablebool/)**를 설정합니다. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | 상속 없이 번호 매긴 글머리 기호 그룹에 사용되는 첫 번째 번호를 설정합니다. 쓰기 **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | 상속 없이 번호 매긴 글머리 기호의 스타일을 설정합니다. 쓰기 [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | 상속 없이 단락의 글머리 기호 유형을 설정합니다. 쓰기 [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터로 설정합니다(공유 포인터가 아닌). 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문과 같은 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)