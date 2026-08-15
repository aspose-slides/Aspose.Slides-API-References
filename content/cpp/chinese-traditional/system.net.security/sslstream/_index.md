---
title: SslStream
second_title: Aspose.Slides for C++ API 參考
description: 使用 SSL 協議驗證伺服器，並可選擇性驗證客戶端的資料流。
type: docs
weight: 14
url: /zh-hant/system.net.security/sslstream/
---
## SslStream 類別


A stream that uses the SSL protocol to authenticate the server and optionally the client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | 驗證連線的客戶端。 |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | 驗證連線的客戶端。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 啟動非同步讀取操作。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步讀取操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 啟動非同步寫入操作。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步寫入操作。 |
| void [Close](./close/)() override | 關閉此資料流。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | 將位元組複製到指定的資料流。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | 使用指定的緩衝區大小，將位元組複製到指定的資料流。 |
| void [Dispose](./dispose/)(**bool**) override | 釋放目前物件使用的所有資源並關閉資料流。 |
| void [Dispose](../../system.io/stream/dispose/)() override | 釋放目前物件使用的所有資源並關閉資料流。 |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 等待指定的非同步讀取操作完成。 |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的非同步讀取操作完成。 |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 結束非同步寫入操作。等待指定的非同步寫入操作完成。 |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 結束非同步寫入操作。等待指定的非同步寫入操作完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）均不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）均不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flush](./flush/)() override | 清除此資料流的緩衝區，並將所有緩衝的資料寫入底層儲存。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步清除此資料流的所有緩衝區，將緩衝資料寫入底層裝置，並監控取消請求。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | 非同步清除此資料流的所有緩衝區，將緩衝資料寫入底層裝置，並監控取消請求。 |
| **bool** [get_CanRead](./get_canread/)() const override | 判斷資料流是否可讀。 |
| **bool** [get_CanSeek](./get_canseek/)() const override | 判斷資料流是否支援定位。 |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | 取得決定目前資料流是否可逾時的值。 |
| **bool** [get_CanWrite](./get_canwrite/)() const override | 判斷資料流是否可寫入。 |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | 傳回在憑證驗證過程中是否檢查憑證撤銷清單的值。 |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | 傳回加密演算法。 |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | 傳回使用之加密演算法的強度。 |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | 傳回雜湊演算法。 |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | 傳回使用之雜湊演算法的強度。 |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | 傳回驗證是否成功通過的值。 |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | 傳回使用此資料流傳送的資料是否已加密的值。 |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | 傳回伺服器與客戶端是否已驗證的值。 |
| **bool** [get_IsServer](./get_isserver/)() const override | 傳回連線本端是否為伺服器的值。 |
| **bool** [get_IsSigned](./get_issigned/)() const override | 傳回使用此資料流傳送的資料是否已簽署的值。 |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | 傳回使用之金鑰交換演算法的強度。 |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | 傳回目前類別實例用於傳送與接收資料的資料流。 |
| **int64_t** [get_Length](./get_length/)() const override | 傳回資料流的長度（位元組）。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | 傳回用於驗證本端點的憑證。 |
| **int64_t** [get_Position](./get_position/)() const override | 傳回資料流的目前位置。 |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | 取得以毫秒為單位，決定資料流在逾時前嘗試讀取的時間長度。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | 傳回用於驗證遠端端點的憑證。 |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | 傳回 SSL 通訊協定。 |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | 取得以毫秒為單位，決定資料流在逾時前嘗試寫入的時間長度。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類似功能。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。類似 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似功能。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從資料流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從資料流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 從資料流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 從資料流讀取指定數量的位元組，並寫入指定的位元組 span。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步從目前資料流讀取一序列位元組，根據讀取的位元組數量前移資料流位置，並監控取消請求。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步從目前資料流讀取一序列位元組，根據讀取的位元組數量前移資料流位置，並監控取消請求。 |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | 從資料流讀取單一位元組，並回傳與該位元組值相等的 32 位整數。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，處理字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，處理字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | 設定目前物件所代表的資料流位置。 |
| void [set_Position](./set_position/)(**int64_t**) override | 設定資料流的位置。 |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | 設定決定目前資料流是否可逾時的值。 |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | 設定決定目前資料流是否可逾時的值。 |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | 設定以毫秒為單位，決定資料流在逾時前嘗試讀取的時間長度。 |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | 設定以毫秒為單位，決定資料流在逾時前嘗試讀取的時間長度。 |
| void [SetLength](./setlength/)(**int64_t**) override | 設定目前物件所代表的資料流長度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | 建構新實例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | 建構新實例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | 建構新實例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | 建構新實例。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | 建構新實例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類似功能。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 將指定的位元組陣列寫入資料流。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列的特定子範圍寫入資料流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 將指定的位元組陣列寫入資料流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列的特定子範圍寫入資料流。 |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 將指定位元組陣列的特定子範圍寫入資料流。 |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 將指定位元組 span 的特定子範圍寫入資料流。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步將一序列位元組寫入目前資料流，根據寫入的位元組數量前移此資料流的目前位置，並監控取消請求。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步將一序列位元組寫入目前資料流，根據寫入的位元組數量前移此資料流的目前位置，並監控取消請求。 |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | 將指定的無號 8 位元整數寫入資料流。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Null](../../system.io/stream/null/) | 沒有底層儲存的資料流。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | AsyncResultType 的型別。 |
| [StreamImplementationPtr](./streamimplementationptr/) | 實作的指標型別。 |

## 另請參閱

* 類別 [AuthenticatedStream](../authenticatedstream/)
* 命名空間 [System::Net::Security](../)
* 程式庫 [Aspose.Slides](../../)