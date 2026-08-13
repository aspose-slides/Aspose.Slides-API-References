---
title: XmlConvert
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 이름을 인코딩 및 디코딩하고, 런타임 타입과 XML 스키마 정의 언어(XSD) 타입 간의 변환을 위한 메서드를 제공합니다. 데이터 타입을 변환할 때 반환되는 값은 로케일에 독립적입니다.
type: docs
weight: 157
url: /ko/system.xml/xmlconvert/
---
## XmlConvert 클래스

XML 이름을 인코딩하고 디코딩하며, 런타임 형식과 XML [Schema](../../system.xml.schema/) 정의 언어 (XSD) 형식 간 변환 메서드를 제공합니다. 형식 변환 시 반환되는 값은 로케일에 독립적입니다.

```cpp
class XmlConvert : public System::Object
```

## Methods

| 메서드 | 설명 |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | 이름을 디코딩합니다. 이 메서드는 XmlConvert::EncodeName(String) 및 XmlConvert::EncodeLocalName(String) 메서드의 역동작을 수행합니다. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | 이름을 유효한 XML 로컬 이름으로 변환합니다. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | 이름을 유효한 XML 이름으로 변환합니다. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | XML 사양에 따라 이름이 유효한지 확인합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 동일하다고 간주되는 C# 스타일 부동 소수점 비교를 구현합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 포함, 같지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 동일하다고 간주되는 C# 스타일 부동 소수점 비교를 구현합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 포함, 같지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | 입력된 문자가 유효한 콜론이 아닌 문자 유형인지 확인합니다. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | 인수의 문자가 유효한 public id 문자이면 해당 문자 인스턴스를 반환하고, 그렇지 않으면 **nullptr**를 반환합니다. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | 입력된 문자가 유효한 시작 이름 문자 유형인지 확인합니다. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | 입력된 문자가 유효한 XML 공백 문자인지 확인합니다. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | 입력된 문자가 유효한 XML 문자인지 확인합니다. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | 입력된 서러게이트 문자 쌍이 유효한 XML 문자인지 확인합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | [String](../../system/string/)를 [Boolean](../../system/boolean/) 동등형으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Byte](../../system/byte/) 동등형으로 변환합니다. |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Char](../../system/char/) 동등형으로 변환합니다. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [DateTime](../../system/datetime/) 동등형으로 변환합니다. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | [String](../../system/string/)를 [DateTime](../../system/datetime/) 동등형으로 변환합니다. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | [String](../../system/string/)를 [DateTime](../../system/datetime/) 동등형으로 변환합니다. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [String](../../system/string/)를 지정된 XmlDateTimeSerializationMode를 사용하여 [DateTime](../../system/datetime/)로 변환합니다. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | 제공된 [String](../../system/string/)를 [DateTimeOffset](../../system/datetimeoffset/) 동등형으로 변환합니다. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 제공된 [String](../../system/string/)를 [DateTimeOffset](../../system/datetimeoffset/) 동등형으로 변환합니다. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 제공된 [String](../../system/string/)를 [DateTimeOffset](../../system/datetimeoffset/) 동등형으로 변환합니다. |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Decimal](../../system/decimal/) 동등형으로 변환합니다. |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | [String](../../system/string/)를 [Double](../../system/double/) 동등형으로 변환합니다. |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Guid](../../system/guid/) 동등형으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Int16](../../system/int16/) 동등형으로 변환합니다. |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Int32](../../system/int32/) 동등형으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [Int64](../../system/int64/) 동등형으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [SByte](../../system/sbyte/) 동등형으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | [String](../../system/string/)를 [Single](../../system/single/) 동등형으로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | [Boolean](../../system/boolean/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | [Char](../../system/char/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | [SByte](../../system/sbyte/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | [Int16](../../system/int16/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | [Int32](../../system/int32/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | [Int64](../../system/int64/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | [Byte](../../system/byte/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | [UInt16](../../system/uint16/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | [UInt32](../../system/uint32/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | [UInt64](../../system/uint64/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | [Single](../../system/single/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | [Double](../../system/double/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | [TimeSpan](../../system/timespan/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | [DateTime](../../system/datetime/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [DateTime](../../system/datetime/)를 지정된 XmlDateTimeSerializationMode를 사용하여 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | 제공된 [DateTimeOffset](../../system/datetimeoffset/)를 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | 제공된 [DateTimeOffset](../../system/datetimeoffset/)를 지정된 형식의 [String](../../system/string/) 로 변환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | [Guid](../../system/guid/)를 [String](../../system/string/) 로 변환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [TimeSpan](../../system/timespan/) 동등형으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [UInt16](../../system/uint16/) 동등형으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [UInt32](../../system/uint32/) 동등형으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | [String](../../system/string/)를 [UInt64](../../system/uint64/) 동등형으로 변환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | 이름이 W3C 확장 마크업 언어 권고에 따라 유효한 이름인지 확인합니다. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | 이름이 W3C 확장 마크업 언어 권고에 따라 유효한 **NCName**인지 확인합니다. **NCName**은 콜론을 포함할 수 없는 이름입니다. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | 문자열이 W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes 권고에 따라 유효한 NMTOKEN인지 확인합니다. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | 문자열 인수의 모든 문자가 유효한 public id 문자이면 해당 문자열 인스턴스를 반환합니다. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | 문자열이 W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes 권고에 따라 유효한 토큰인지 확인합니다. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | 문자열 인수의 모든 문자가 유효한 공백 문자이면 해당 문자열 인스턴스를 반환합니다. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | 문자열 인수의 모든 문자와 서러게이트 쌍 문자가 유효한 XML 문자이면 해당 문자열을 반환하고, 그렇지 않으면 첫 번째 잘못된 문자에 대한 정보를 포함한 XmlException이 발생합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 별칭 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스의 인스턴스에 대한 shared pointer 별칭입니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)