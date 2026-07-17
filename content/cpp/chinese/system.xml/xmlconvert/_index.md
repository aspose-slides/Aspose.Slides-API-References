---
title: XmlConvert
second_title: Aspose.Slides for C++ API 参考
description: 对 XML 名称进行编码和解码，并提供在运行时类型与 XML 模式定义语言 (XSD) 类型之间转换的方法。转换数据类型时，返回的值不受区域设置影响。
type: docs
weight: 157
url: /zh/system.xml/xmlconvert/
---
## XmlConvert 类

对 XML 名称进行编码和解码，并提供在运行时类型与 XML [Schema](../../system.xml.schema/) 定义语言 (XSD) 类型之间转换的方法。转换数据类型时，返回的值不受区域设置影响。

```cpp
class XmlConvert : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | 解码名称。此方法执行 XmlConvert::EncodeName(String) 和 XmlConvert::EncodeLocalName(String) 方法的逆操作。 |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | 将名称转换为有效的 XML 本地名称。 |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | 将名称转换为有效的 XML 名称。 |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | 验证名称是否符合 XML 规范。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，在此比较中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，在此比较中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持对自定义对象进行哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | 检查传入的字符是否为有效的非冒号字符类型。 |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | 如果参数中的字符是有效的公共标识符字符，则返回该字符实例；否则返回 **nullptr**。 |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | 检查传入的字符是否为有效的起始名称字符类型。 |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | 检查传入的字符是否为有效的 XML 空白字符。 |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | 检查传入的字符是否为有效的 XML 字符。 |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | 检查传入的代理对字符是否为有效的 XML 字符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前的共享引用计数值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | 将 [String](../../system/string/) 转换为等价的 [Boolean](../../system/boolean/)。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Byte](../../system/byte/)。 |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Char](../../system/char/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [DateTime](../../system/datetime/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [DateTime](../../system/datetime/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 将 [String](../../system/string/) 转换为等价的 [DateTime](../../system/datetime/)。 |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | 使用指定的 XmlDateTimeSerializationMode 将 [String](../../system/string/) 转换为 [DateTime](../../system/datetime/)。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | 将提供的 [String](../../system/string/) 转换为等价的 [DateTimeOffset](../../system/datetimeoffset/)。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将提供的 [String](../../system/string/) 转换为等价的 [DateTimeOffset](../../system/datetimeoffset/)。 |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 将提供的 [String](../../system/string/) 转换为等价的 [DateTimeOffset](../../system/datetimeoffset/)。 |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Decimal](../../system/decimal/)。 |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | 将 [String](../../system/string/) 转换为等价的 [Double](../../system/double/)。 |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Guid](../../system/guid/)。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Int16](../../system/int16/)。 |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Int32](../../system/int32/)。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [Int64](../../system/int64/)。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [SByte](../../system/sbyte/)。 |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | 将 [String](../../system/string/) 转换为等价的 [Single](../../system/single/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | 将 [Boolean](../../system/boolean/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | 将 [Char](../../system/char/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | 将 [Decimal](../../system/decimal/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | 将 [SByte](../../system/sbyte/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | 将 [Int16](../../system/int16/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | 将 [Int32](../../system/int32/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | 将 [Int64](../../system/int64/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | 将 [Byte](../../system/byte/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | 将 [UInt16](../../system/uint16/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | 将 [UInt32](../../system/uint32/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | 将 [UInt64](../../system/uint64/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | 将 [Single](../../system/single/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | 将 [Double](../../system/double/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | 将 [TimeSpan](../../system/timespan/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | 将 [DateTime](../../system/datetime/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | 将 [DateTime](../../system/datetime/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | 使用指定的 XmlDateTimeSerializationMode 将 [DateTime](../../system/datetime/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | 将提供的 [DateTimeOffset](../../system/datetimeoffset/) 转换为 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | 将提供的 [DateTimeOffset](../../system/datetimeoffset/) 转换为指定格式下的 [String](../../system/string/)。 |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | 将 [Guid](../../system/guid/) 转换为 [String](../../system/string/)。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [TimeSpan](../../system/timespan/)。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [UInt16](../../system/uint16/)。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [UInt32](../../system/uint32/)。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | 将 [String](../../system/string/) 转换为等价的 [UInt64](../../system/uint64/)。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | 验证名称是否符合 W3C 扩展标记语言（XHTML）推荐的有效名称。 |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | 验证名称是否符合 W3C 扩展标记语言（XHTML）推荐的有效 **NCName**。**NCName** 是不能包含冒号的名称。 |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | 验证字符串是否符合 W3C XML [Schema](../../system.xml.schema/) 第2部分：数据类型 推荐的有效 NMTOKEN。 |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | 如果字符串参数中的所有字符都是有效的公共标识符字符，则返回传入的字符串实例。 |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | 验证字符串是否符合 W3C XML [Schema](../../system.xml.schema/) 第2部分：数据类型 推荐的有效 token。 |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | 如果字符串参数中的所有字符都是有效的空白字符，则返回传入的字符串实例。 |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | 如果字符串参数中的所有字符和代理对字符都是有效的 XML 字符，则返回传入的字符串；否则抛出 XmlException，包含首个无效字符的信息。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)