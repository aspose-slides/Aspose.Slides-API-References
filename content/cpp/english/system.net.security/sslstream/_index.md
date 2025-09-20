---
title: SslStream
second_title: Aspose.Slides for C++ API Reference
description: A stream that uses the SSL protocol to authenticate the server and optionally the client.
type: docs
weight: 14
url: /system.net.security/sslstream/
---
## SslStream class


A stream that uses the SSL protocol to authenticate the server and optionally the client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Authenticates the client-side of the connection. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Authenticates the client-side of the connection. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initiates an asynchronous read operation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initiates an asynchronous read operation. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initiates an asynchronous write operation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initiates an asynchronous write operation. |
| void [Close](./close/)() override | Closes the stream. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copies bytes to the specified stream. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copies bytes to the specified stream, using the specified buffer size. |
| void [Dispose](./dispose/)(**bool**) override | Releases all resources used by the current object and closes the stream. |
| void [Dispose](../../system.io/stream/dispose/)() override | Releases all resources used by the current object and closes the stream. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Waits until the specified asynchronous read operation completes. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Waits until the specified asynchronous read operation completes. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Ends an asynchronous write operation. Waits until the specified asynchronous write operation completes. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ends an asynchronous write operation. Waits until the specified asynchronous write operation completes. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| void [Flush](./flush/)() override | Clears this stream's buffers and writes all buffered data to the underlying storage. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| **bool** [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Gets a value that determines whether the current stream can time out. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Returns a value that indicates if the certificate revocation list is checked during the certificate validation process. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Returns the encryption algorithm. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Returns the strength of the used encryption algorithm. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Returns the hash algorithm. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Returns the strength of the used hash algorithm. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Returns a value that indicates if authentication is successfully passed. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Returns a value that indicates if the data sent using this stream is encrypted. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Returns a value that indicates if a server and a client are authenticated. |
| **bool** [get_IsServer](./get_isserver/)() const override | Returns a value that indicates if the local side of the connection is the server. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Returns a value that indicates if the data sent using this stream is signed. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Returns the strength of the used key exchange algorithm. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Returns the stream that is used by the current class instances for sending and receiving data. |
| **int64_t** [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Returns the certificate that is used to authenticate the local endpoint. |
| **int64_t** [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Gets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Returns the certificate that is used to authenticate the remote endpoint. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Returns the SSL protocol. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Gets a value, in milliseconds, that determines how long the stream will attempt to write before timing out. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Reads a single byte from the stream and returns a 32-bit integer value equivalent to the value of the read byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Sets the position of the stream represented by the current object. |
| void [set_Position](./set_position/)(**int64_t**) override | Sets the stream's position. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Sets a value that determines whether the current stream can time out. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Sets a value that determines whether the current stream can time out. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Sets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Sets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| void [SetLength](./setlength/)(**int64_t**) override | Sets the length of the stream represented by the current object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Constructs a new instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Constructs a new instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Constructs a new instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Constructs a new instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Constructs a new instance. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Writes the specified byte array to the stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Writes the specified byte array to the stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Writes the specified subrange of bytes from the specified byte array to the stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Writes the specified unsigned 8-bit integer value to the stream. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Type of AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Type of pointer to the implementation. |
## See Also

* Class [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.Slides](../../)