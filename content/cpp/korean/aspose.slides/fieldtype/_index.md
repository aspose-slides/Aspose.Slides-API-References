---
title: FieldType
second_title: Aspose.Slides for C++ API 참조
description: 필드 유형을 나타냅니다. 이 값은 필드 부분이 업데이트될 때 어떤 텍스트가 설정될지를 결정합니다.
type: docs
weight: 872
url: /ko/aspose.slides/fieldtype/
---
## FieldType 클래스

필드의 유형을 나타냅니다. 이 값은 필드 부분이 업데이트될 때 어떤 텍스트가 설정될지를 결정합니다.

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 이 필드가 다른 필드와 같은지 확인합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 포함, 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 포함, 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
|  [FieldType](./fieldtype/)([System::String](../../system/string/)) | [FieldType](./) 클래스의 새 인스턴스를 초기화합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | 렌더링 애플리케이션의 기본 날짜 시간 형식으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | 첫 번째 사전 정의 형식(MM/DD/YYYY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | 두 번째 사전 정의 형식(hh:mm, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | 세 번째 사전 정의 형식(hh:mm:ss, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | 네 번째 사전 정의 형식(hh:mm AM/PM, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | 다섯 번째 사전 정의 형식(hh:mm:ss AM/PM, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | 두 번째 사전 정의 형식(Day, Month DD, YYYY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | 세 번째 사전 정의 형식(DD Month YYYY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | 네 번째 사전 정의 형식(Month DD, YYYY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | 다섯 번째 사전 정의 형식(DD-Mon-YY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | 여섯 번째 사전 정의 형식(Month YY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | 일곱 번째 사전 정의 형식(Mon-YY, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | 여덟 번째 사전 정의 형식(MM/DD/YYYY hh:mm AM/PM, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | 아홉 번째 사전 정의 형식(MM/DD/YYYY hh:mm:ss AM/PM, 영어)으로 현재 날짜와 시간을 반환합니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | [Slide](../slide/)의 페이지 하단입니다. 읽기 전용 [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | [Slide](../slide/)의 페이지 상단입니다. 읽기 전용 [FieldType](./). |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | 이 [FieldType](./) 객체의 내부 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | 현재 슬라이드 번호를 반환합니다. 읽기 전용 [FieldType](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 이 객체의 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스를 복사 구성할 수 있게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스를 복사 구성할 수 있게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | 이 [FieldType](./) 객체의 내부 이름을 반환합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터로 설정합니다(공유 대신). 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제 구현입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 관련 항목

* Class [IFieldType](../ifieldtype/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)