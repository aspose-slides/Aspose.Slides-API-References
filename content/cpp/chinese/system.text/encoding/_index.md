---
title: Encoding
second_title: Aspose.Slides for C++ API 参考
description: 编码服务。
type: docs
weight: 222
url: /zh/system.text/encoding/
---
## Encoding 类


[Encoding](./) 服务。

```cpp
class Encoding : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | 克隆编码对象。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 在两种编码之间转换字节。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 在两种编码之间转换字节。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 比较编码。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 按引用比较对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 也被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 也被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | 获取 ASCII 编码。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | 获取标准大端 Unicode 编码对象。 |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | 获取标准大端 UTF-32 编码对象。 |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | 获取邮件代理正文兼容的编码名称。 |
| virtual int [get_CodePage](./get_codepage/)() | 获取 [Windows](../../system.windows/) 代码页 ID。 |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | 获取解码器回退。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | 获取默认编码。 |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | 获取编码器回退。 |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | 获取人类可读的编码名称。 |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | 获取邮件代理头部兼容的编码名称。 |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | 检查编码是否可在浏览器中用于显示内容。 |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | 检查编码是否可在浏览器中用于保存内容。 |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | 检查编码是否可在邮件客户端中用于显示内容。 |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | 检查编码是否可在邮件客户端中用于保存内容。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | 检查编码是否为只读。 |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | 检查编码是否为单字节。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | 获取 Latin1 编码。仅供内部使用。 |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | 获取标准 Unicode 编码对象。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | 获取标准 UTF-7 编码对象。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | 获取标准 UTF-8 编码对象。 |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | 仅内部使用，由类库使用：未标记且不验证输入。 |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | 获取 IANA 兼容的编码名称。 |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | 获取 [Windows](../../system.windows/) 代码页 ID。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 获取编码字符缓冲区所需的字符数。 |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | 获取编码字符缓冲区所需的字符数。 |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 获取编码字符缓冲区所需的字符数。 |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | 获取编码字符串所需的字符数。 |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 获取编码字符缓冲区所需的字符数。 |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | 获取编码字符缓冲区所需的字符数。 |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | 获取对字符缓冲区进行编码后得到的字节。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 获取解码字节缓冲区所需的字符数。 |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 获取解码字节缓冲区所需的字符数。 |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | 获取解码字节缓冲区所需的字符数。 |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 获取解码字节缓冲区后得到的字符。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 获取解码字节缓冲区后得到的字符。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 获取解码字节缓冲区后得到的字符。 |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | 获取解码字节缓冲区后得到的字符。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | 获取转发请求到此对象的解码器。 |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | 获取转发请求到此对象的编码器。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | 按名称获取编码。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | 按代码页获取编码。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 按代码页获取编码。 |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 按名称获取编码。 |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | 获取已知编码的列表。 |
| int [GetHashCode](./gethashcode/)() const override | 为编码生成哈希值。 |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | 获取编码指定字符数所需的最大字节数。 |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | 获取解码指定字节数所需的最大字符数。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | 返回表示该编码的字节序列（例如 BOM）。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | 将字节缓冲区解码为字符串。 |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 将字节缓冲区解码为字符串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 将字节缓冲区解码为字符串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 将字节缓冲区解码为字符串。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 将字节缓冲区解码为字符串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 将字节缓冲区解码为字符串。 |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | 将字节缓冲区解码为字符串。 |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | 将字节缓冲区解码为字符串。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 所描述类型的实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允许克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 设置解码器回退。 |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | 设置编码器回退。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。允许将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | 默认代码页值。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Text](../)
* 库 [Aspose.Slides](../../)