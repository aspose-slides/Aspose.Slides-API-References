---
title: "System::Text"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 976
url: /zh/system.text/
---
## 类

| 类 | 描述 |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/) | 表示 ASCII 编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Decoder](./decoder/) | 封装将字节序列解码为字符序列的过程。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DecoderExceptionFallback](./decoderexceptionfallback/) | 提供抛出异常的回退策略。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DecoderExceptionFallbackBuffer](./decoderexceptionfallbackbuffer/) | [Buffer](../system/buffer/) 用于异常抛出的解码回退策略。实际上不存储任何内容，而是直接抛出。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DecoderFallback](./decoderfallback/) | 提供回退 API 以处理解码错误。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DecoderFallbackBuffer](./decoderfallbackbuffer/) | 提供回退实现的缓冲区。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DecoderReplacementFallback](./decoderreplacementfallback/) | 提供将错误符号替换为存根的回退策略。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DecoderReplacementFallbackBuffer](./decoderreplacementfallbackbuffer/) | [Buffer](../system/buffer/) 用于替换解码回退策略。 |
| [Details_DecoderFallbackException](./details_decoderfallbackexception/) | 在解码失败时由 [DecoderExceptionFallback](./decoderexceptionfallback/) 抛出的异常。切勿手动创建此类实例。请改用 DecoderFallbackException 类。切勿将 DecoderFallbackException 类的实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [Details_EncoderFallbackException](./details_encoderfallbackexception/) | 在编码失败时由 [EncoderExceptionFallback](./encoderexceptionfallback/) 抛出的异常。切勿手动创建此类实例。请改用 EncoderFallbackException 类。切勿将 EncoderFallbackException 类的实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [Encoder](./encoder/) | 封装将字符序列编码为字节序列的过程。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncoderExceptionFallback](./encoderexceptionfallback/) | 提供抛出异常的回退策略。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncoderExceptionFallbackBuffer](./encoderexceptionfallbackbuffer/) | [Buffer](../system/buffer/) 用于异常抛出的编码回退策略。实际上不存储任何内容，而是直接抛出。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncoderFallback](./encoderfallback/) | 提供回退 API 以处理编码错误。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncoderFallbackBuffer](./encoderfallbackbuffer/) | 提供回退实现的缓冲区。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncoderReplacementFallback](./encoderreplacementfallback/) | 提供将错误符号替换为存根的回退策略。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncoderReplacementFallbackBuffer](./encoderreplacementfallbackbuffer/) | [Buffer](../system/buffer/) 用于替换编码回退策略。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Encoding](./encoding/) | [Encoding](./encoding/) 服务。 |
| [EncodingDecoder](./encodingdecoder/) | [Decoder](./decoder/) 使用编码对象进行解码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncodingEncoder](./encodingencoder/) | [Encoder](./encoder/) 使用编码对象进行编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [EncodingInfo](./encodinginfo/) | 关于编码的简要信息。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICUDecoder](./icudecoder/) | [Decoder](./decoder/) 使用 ICU 进行解码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICUEncoder](./icuencoder/) | [Encoder](./encoder/) 使用 ICU 进行编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICUEncoding](./icuencoding/) | 基于 ICU 的编码实现。供内部使用。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Latin1Encoding](./latin1encoding/) | Latin1 编码支持。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StringBuilder](./stringbuilder/) | [Buffer](../system/buffer/) 用于逐段累积字符串。此类型既可以在栈上作为值类型分配，也可以使用 [System::MakeObject()](../system/makeobject/) 函数在堆上分配。对象分配后，切勿混用这两种情况：禁止将 [SmartPtr](../system/smartptr/) 指针指向栈分配的对象。 |
| [UnicodeEncoding](./unicodeencoding/) | Unicode 编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UTF32Encoding](./utf32encoding/) | UTF-32 编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UTF7Encoding](./utf7encoding/) | UTF-7 编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UTF8Encoding](./utf8encoding/) | UTF-8 编码。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [NormalizationForm](./normalizationform/) | 定义如何规范化 Unicode 字符串。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [DecoderFallbackException](./decoderfallbackexception/) |  |
| [EncoderFallbackException](./encoderfallbackexception/) |  |
| [ICUEncodingPtr](./icuencodingptr/) | ICU 编码指针。 |