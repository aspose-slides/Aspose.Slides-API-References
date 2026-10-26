---
title: SslStream
second_title: Aspose.Slides C++ API 参考
description: 使用 SSL 协议对服务器进行身份验证并可选地对客户端进行身份验证的流。
type: docs
weight: 14
url: /zh/system.net.security/sslstream/
---
## SslStream 类

使用 SSL 协议对服务器进行身份验证并可选地对客户端进行身份验证的流。

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | 对连接的客户端侧进行身份验证。 |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | 对连接的客户端侧进行身份验证。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 启动异步读取操作。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 启动异步读取操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 启动异步写入操作。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 启动异步写入操作。 |
| void [Close](./close/)() override | 关闭流。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | 将字节复制到指定的流。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | 使用指定的缓冲区大小将字节复制到指定的流。 |
| void [Dispose](./dispose/)(**bool**) override | 释放当前对象使用的所有资源并关闭流。 |
| void [Dispose](../../system.io/stream/dispose/)() override | 释放当前对象使用的所有资源并关闭流。 |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定的异步读取操作完成。 |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的异步读取操作完成。 |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 结束异步写入操作。等待指定的异步写入操作完成。 |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 结束异步写入操作。等待指定的异步写入操作完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，但这里两个 NaN 被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，但这里两个 NaN 被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| void [Flush](./flush/)() override | 清除此流的缓冲区并将所有缓冲的数据写入底层存储。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | 异步清除此流的所有缓冲区，使任何缓冲的数据写入底层设备，并监视取消请求。 |
| **bool** [get_CanRead](./get_canread/)() const override | 判断流是否可读。 |
| **bool** [get_CanSeek](./get_canseek/)() const override | 判断流是否支持定位。 |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | 获取一个值，用于确定当前流是否可以超时。 |
| **bool** [get_CanWrite](./get_canwrite/)() const override | 判断流是否可写。 |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | 返回一个值，指示在证书验证过程中是否检查证书吊销列表。 |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | 返回加密算法。 |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | 返回所使用加密算法的强度。 |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | 返回哈希算法。 |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | 返回所使用哈希算法的强度。 |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | 返回一个值，指示身份验证是否成功通过。 |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | 返回一个值，指示使用此流发送的数据是否已加密。 |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | 返回一个值，指示服务器和客户端是否已进行身份验证。 |
| **bool** [get_IsServer](./get_isserver/)() const override | 返回一个值，指示连接的本地端是否为服务器。 |
| **bool** [get_IsSigned](./get_issigned/)() const override | 返回一个值，指示使用此流发送的数据是否已签名。 |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | 返回所使用密钥交换算法的强度。 |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | 返回当前类实例用于发送和接收数据的流。 |
| **int64_t** [get_Length](./get_length/)() const override | 返回流的字节长度。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | 返回用于验证本地点的证书。 |
| **int64_t** [get_Position](./get_position/)() const override | 返回流的当前位置。 |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | 获取一个以毫秒为单位的值，决定流在超时前尝试读取的时长。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | 返回用于验证远端点的证书。 |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | 返回 SSL 协议。 |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | 获取一个以毫秒为单位的值，决定流在超时前尝试写入的时长。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 从流中读取指定数量的字节并写入指定的字节数组。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 从流中读取指定数量的字节并写入指定的字节数组。 |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 从流中读取指定数量的字节并写入指定的字节数组。 |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 从流中读取指定数量的字节并写入指定的字节跨度。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 异步从当前流读取一系列字节，按已读取的字节数前进流的位置，并监视取消请求。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 异步从当前流读取一系列字节，按已读取的字节数前进流的位置，并监视取消请求。 |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | 从流中读取单个字节，并返回与读取字节值等价的 32 位整数值。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | 设置当前对象所代表的流的位置。 |
| void [set_Position](./set_position/)(**int64_t**) override | 设置流的位置。 |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | 设置一个值，用于确定当前流是否可以超时。 |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | 设置一个值，用于确定当前流是否可以超时。 |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | 设置一个以毫秒为单位的值，决定流在超时前尝试读取的时长。 |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | 设置一个以毫秒为单位的值，决定流在超时前尝试读取的时长。 |
| void [SetLength](./setlength/)(**int64_t**) override | 设置当前对象所代表的流的长度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | 构造一个新实例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | 构造一个新实例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | 构造一个新实例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | 构造一个新实例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | 构造一个新实例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 将指定的字节数组写入流。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 将指定字节数组的指定子范围写入流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 将指定的字节数组写入流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 将指定字节数组的指定子范围写入流。 |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 将指定字节数组的指定子范围写入流。 |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 将指定字节跨度的指定子范围写入流。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 异步将一系列字节写入当前流，按已写入的字节数前进流中的当前位置，并监视取消请求。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 异步将一系列字节写入当前流，按已写入的字节数前进流中的当前位置，并监视取消请求。 |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | 将指定的无符号 8 位整数写入流。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Null](../../system.io/stream/null/) | 没有底层存储的流。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | AsyncResultType 的类型。 |
| [StreamImplementationPtr](./streamimplementationptr/) | 实现的指针类型。 |

## 另请参见

* 类 [AuthenticatedStream](../authenticatedstream/)
* 命名空间 [System::Net::Security](../)
* 库 [Aspose.Slides](../../)