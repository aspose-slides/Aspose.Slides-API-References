---
title: AuthenticatedStream
second_title: Aspose.Slides for C++ API リファレンス
description: "ストリームを介して資格情報を渡すためのメソッドを含みます。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 1
url: /ja/system.net.security/authenticatedstream/
---
## AuthenticatedStream クラス

このクラスはストリームを介して資格情報を渡すためのメソッドを含みます。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期読み取り操作を開始します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期書き込み操作を開始します。 |
| virtual void [Close](../../system.io/stream/close/)() | ストリームを閉じます。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | 指定されたストリームへバイトをコピーします。 |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | 指定されたバッファサイズを使用して、指定されたストリームへバイトをコピーします。 |
| void [Dispose](../../system.io/stream/dispose/)() override | 現在のオブジェクトが使用するすべてのリソースを解放し、ストリームを閉じます。 |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 指定された非同期読み取り操作が完了するまで待機します。 |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 非同期書き込み操作を終了します。指定された非同期書き込み操作が完了するまで待機します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN は任意の値（NaN を含む）と等しくないと規定されているにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN は任意の値（NaN を含む）と等しくないと規定されているにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual void [Flush](../../system.io/stream/flush/)() | このストリームのバッファをクリアし、バッファされたすべてのデータを基盤ストレージへ書き込みます。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | このストリームのすべてのバッファを非同期的にクリアし、バッファされたデータが基盤デバイスへ書き込まれるようにし、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | このストリームのすべてのバッファを非同期的にクリアし、バッファされたデータが基盤デバイスへ書き込まれるようにし、キャンセル要求を監視します。 |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | ストリームが読み取り可能かどうかを判定します。 |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | ストリームがシークをサポートしているかどうかを判定します。 |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | 現在のストリームがタイムアウトできるかどうかを決定する値を取得します。 |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | ストリームが書き込み可能かどうかを判定します。 |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | 認証が正常に渡されたかどうかを示す値を返します。 |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | このストリームを使用して送信されたデータが暗号化されているかどうかを示す値を返します。 |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | サーバーとクライアントが認証されたかどうかを示す値を返します。 |
| virtual **bool** [get_IsServer](./get_isserver/)() const | 接続のローカル側がサーバーであるかどうかを示す値を返します。 |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | このストリームを使用して送信されたデータが署名されているかどうかを示す値を返します。 |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | 現在のクラスインスタンスがデータの送受信に使用するストリームを返します。 |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | ストリームの長さ（バイト単位）を返します。 |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | ストリームの現在の位置を返します。 |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | ストリームがタイムアウトするまでに読み取りを試みる時間（ミリ秒）を取得します。 |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | ストリームがタイムアウトするまでに書き込みを試みる時間（ミリ秒）を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | ストリームから指定されたバイト数を読み取り、指定されたバイトスパンに書き込みます。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 現在のストリームからバイトシーケンスを非同期的に読み取り、読み取ったバイト数分ストリーム内の位置を進め、キャンセル要求を監視します。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームからバイトシーケンスを非同期的に読み取り、読み取ったバイト数分ストリーム内の位置を進め、キャンセル要求を監視します。 |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | ストリームから単一バイトを読み取り、読み取ったバイトの値に相当する 32 ビット整数値を返します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | 現在のオブジェクトが表すストリームの位置を設定します。 |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | ストリームの位置を設定します。 |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | 現在のストリームがタイムアウトできるかどうかを決定する値を設定します。 |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | ミリ秒単位で、ストリームがタイムアウトするまでに読み取りを試みる時間を設定します。 |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | 現在のオブジェクトが表すストリームの長さを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 指定されたバイト配列の対象サブレンジをストリームへ書き込みます。 |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 指定されたバイト配列の対象サブレンジをストリームへ書き込みます。 |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 指定されたバイト配列の対象サブレンジをストリームへ書き込みます。 |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 指定されたバイトスパンの対象サブレンジをストリームへ書き込みます。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 現在のストリームへバイトシーケンスを非同期的に書き込み、書き込まれたバイト数分ストリーム内の位置を進め、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームへバイトシーケンスを非同期的に書き込み、書き込まれたバイト数分ストリーム内の位置を進め、キャンセル要求を監視します。 |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | 指定された符号なし 8 ビット整数値をストリームへ書き込みます。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | 基盤ストレージを持たないストリームです。 |

## 参照

* クラス [Stream](../../system.io/stream/)
* 名前空間 [System::Net::Security](../)
* ライブラリ [Aspose.Slides](../../)