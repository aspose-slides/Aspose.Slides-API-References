---
title: SslStream
second_title: Aspose.Slides for C++ API リファレンス
description: サーバーとオプションでクライアントを認証するために SSL プロトコルを使用するストリームです。
type: docs
weight: 14
url: /ja/system.net.security/sslstream/
---
## SslStream クラス


サーバーとオプションでクライアントを認証するために SSL プロトコルを使用するストリーム。

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | 接続のクライアント側を認証します。 |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | 接続のクライアント側を認証します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 非同期読み取り操作を開始します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期読み取り操作を開始します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 非同期書き込み操作を開始します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期書き込み操作を開始します。 |
| void [Close](./close/)() override | ストリームを閉じます。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | バイトを指定されたストリームにコピーします。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | 指定されたバッファサイズを使用して、バイトを指定されたストリームにコピーします。 |
| void [Dispose](./dispose/)(**bool**) override | 現在のオブジェクトが使用しているすべてのリソースを解放し、ストリームを閉じます。 |
| void [Dispose](../../system.io/stream/dispose/)() override | 現在のオブジェクトが使用しているすべてのリソースを解放し、ストリームを閉じます。 |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 指定された非同期読み取り操作が完了するまで待機します。 |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 指定された非同期読み取り操作が完了するまで待機します。 |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | 非同期書き込み操作を終了します。指定された非同期書き込み操作が完了するまで待機します。 |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 非同期書き込み操作を終了します。指定された非同期書き込み操作が完了するまで待機します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートし、IEC 60559:1989 では NaN はどの値とも等しくありませんが、ここでは NaN 同士を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートし、IEC 60559:1989 では NaN はどの値とも等しくありませんが、ここでは NaN 同士を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| void [Flush](./flush/)() override | このストリームのバッファをクリアし、すべてのバッファ済みデータを基盤ストレージに書き込みます。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | このストリームのすべてのバッファを非同期でクリアし、バッファされたデータを書き込み、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | このストリームのすべてのバッファを非同期でクリアし、バッファされたデータを書き込み、キャンセル要求を監視します。 |
| **bool** [get_CanRead](./get_canread/)() const override | ストリームが読み取り可能かどうかを判断します。 |
| **bool** [get_CanSeek](./get_canseek/)() const override | ストリームがシークをサポートしているかどうかを判断します。 |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | 現在のストリームがタイムアウトできるかどうかを決定する値を取得します。 |
| **bool** [get_CanWrite](./get_canwrite/)() const override | ストリームが書き込み可能かどうかを判断します。 |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | 証明書検証プロセスで証明書失効リストがチェックされるかどうかを示す値を返します。 |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | 暗号化アルゴリズムを返します。 |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | 使用された暗号化アルゴリズムの強度を返します。 |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | ハッシュアルゴリズムを返します。 |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | 使用されたハッシュアルゴリズムの強度を返します。 |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | 認証が正常に完了したかどうかを示す値を返します。 |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | このストリームを使用して送信されたデータが暗号化されているかどうかを示す値を返します。 |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | サーバーとクライアントが認証されているかどうかを示す値を返します。 |
| **bool** [get_IsServer](./get_isserver/)() const override | 接続のローカル側がサーバーかどうかを示す値を返します。 |
| **bool** [get_IsSigned](./get_issigned/)() const override | このストリームを使用して送信されたデータが署名されているかどうかを示す値を返します。 |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | 使用された鍵交換アルゴリズムの強度を返します。 |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | 現在のクラスインスタンスがデータの送受信に使用するストリームを返します。 |
| **int64_t** [get_Length](./get_length/)() const override | ストリームの長さ（バイト単位）を返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | ローカルエンドポイントの認証に使用される証明書を返します。 |
| **int64_t** [get_Position](./get_position/)() const override | ストリームの現在位置を返します。 |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | ミリ秒単位で、ストリームがタイムアウトするまでの読み取り試行時間を決定する値を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | リモートエンドポイントの認証に使用される証明書を返します。 |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | SSL プロトコルを返します。 |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | ミリ秒単位で、ストリームがタイムアウトするまでの書き込み試行時間を決定する値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | ストリームから指定されたバイト数を読み取り、指定されたバイトスパンに書き込みます。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 現在のストリームからバイトシーケンスを非同期で読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームからバイトシーケンスを非同期で読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。 |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | ストリームから 1 バイト読み取り、読み取ったバイトの値に相当する 32 ビット整数値を返します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | 現在のオブジェクトで表されるストリームの位置を設定します。 |
| void [set_Position](./set_position/)(**int64_t**) override | ストリームの位置を設定します。 |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | 現在のストリームがタイムアウトできるかどうかを決定する値を設定します。 |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | 現在のストリームがタイムアウトできるかどうかを決定する値を設定します。 |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | ミリ秒単位で、ストリームがタイムアウトするまでの読み取り試行時間を設定します。 |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | ミリ秒単位で、ストリームがタイムアウトするまでの読み取り試行時間を設定します。 |
| void [SetLength](./setlength/)(**int64_t**) override | 現在のオブジェクトで表されるストリームの長さを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | 新しいインスタンスを構築します。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | 新しいインスタンスを構築します。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | 新しいインスタンスを構築します。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | 新しいインスタンスを構築します。 |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | 新しいインスタンスを構築します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 指定されたバイト配列をストリームに書き込みます。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 指定されたバイト配列の指定されたサブレンジをストリームに書き込みます。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 指定されたバイト配列をストリームに書き込みます。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 指定されたバイト配列の指定されたサブレンジをストリームに書き込みます。 |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 指定されたバイト配列の指定されたサブレンジをストリームに書き込みます。 |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 指定されたバイトスパンの指定されたサブレンジをストリームに書き込みます。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 現在のストリームにバイトシーケンスを非同期で書き込み、書き込んだバイト数だけストリーム内の現在位置を進め、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームにバイトシーケンスを非同期で書き込み、書き込んだバイト数だけストリーム内の現在位置を進め、キャンセル要求を監視します。 |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | 指定された符号なし 8 ビット整数値をストリームに書き込みます。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Null](../../system.io/stream/null/) | 基盤ストレージを持たないストリームです。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | AsyncResultType の型です。 |
| [StreamImplementationPtr](./streamimplementationptr/) | 実装へのポインタの型です。 |

## 関連項目

* クラス [AuthenticatedStream](../authenticatedstream/)
* 名前空間 [System::Net::Security](../)
* ライブラリ [Aspose.Slides](../../)