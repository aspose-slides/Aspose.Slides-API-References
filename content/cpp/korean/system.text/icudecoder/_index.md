---
title: ICUDecoder
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ICU를 사용하여 디코딩하는 디코더입니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 단언 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 274
url: /ko/system.text/icudecoder/
---
## ICUDecoder 클래스

[Decoder](../decoder/)는 ICU를 사용하여 디코딩합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 만들거나 operator new를 사용하여 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 단언 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class ICUDecoder : public System::Text::Decoder
```

## 메서드

| Method | Description |
| --- | --- |
| virtual void [Convert](./convert/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, **bool**, int\&, int\&, **bool**\&) | 바이트를 문자로 변환합니다. |
| virtual void [Convert](./convert/)(const **uint8_t** *, int, char_t *, int, **bool**, int\&, int\&, **bool**\&) | 바이트를 문자로 변환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동등하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 동등하지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동등하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 동등하지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_Fallback](../decoder/get_fallback/)() const | 오류 처리 대체값을 가져옵니다. |
| [DecoderFallbackBufferPtr](../../system/decoderfallbackbufferptr/) [get_FallbackBuffer](../decoder/get_fallbackbuffer/)() const | 대체 버퍼를 가져옵니다. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, **bool**) | 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int, **bool**) | 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 버퍼 디코딩 결과로 얻은 문자를 반환합니다. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, **bool**) | 버퍼 디코딩 결과로 얻은 문자를 반환합니다. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int, **bool**) | 버퍼 디코딩 결과로 얻은 문자를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
|  [ICUDecoder](./icudecoder/)([ICUEncoding](../icuencoding/) *) | 생성자. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며, 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며, 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [Reset](./reset/)() | 내부 변수를 초기 상태로 설정합니다. |
| void [set_Fallback](../decoder/set_fallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 오류 처리 대체값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~ICUDecoder](./~icudecoder/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입정의

| Typedef | Description |
| --- | --- |
| [Base](./base/) | 기본 형식. |

## 참고

* 클래스 [Decoder](../decoder/)
* 네임스페이스 [System::Text](../)
* 라이브러리 [Aspose.Slides](../../)