---
title: FileStream
second_title: Aspose.Slides for C++ API リファレンス
description: "同期および非同期の読み取りと書き込み操作をサポートするファイルストリームを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。実行時エラーやアサーション違反が発生する可能性があります。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として使用してください。"
type: docs
weight: 287
url: /ja/system.io/filestream/
---
## FileStream クラス

同期および非同期の読み取り・書き込み操作をサポートするファイルストリームを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。これにより実行時エラーやアサーション違反が発生する可能性があります。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として使用してください。

```cpp
class FileStream : public System::IO::Stream
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期の読み取り操作を開始します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期の書き込み操作を開始します。 |
| void [Close](./close/)() override | 現在の [FileStream](./) オブジェクトを閉じます。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | バイトを指定されたストリームにコピーします。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 指定されたバッファサイズを使用して、バイトを指定されたストリームにコピーします。 |
| void [Dispose](../stream/dispose/)() override | 現在のオブジェクトが使用するすべてのリソースを解放し、ストリームを閉じます。 |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 指定された非同期読み取り操作が完了するまで待機します。 |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 非同期書き込み操作を終了します。指定された非同期書き込み操作が完了するまで待機します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | [FileStream](./) クラスの新しいインスタンスを構築し、指定されたパラメータで初期化します。 |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | [FileStream](./) クラスの新しいインスタンスを構築し、指定されたパラメータで初期化します。 |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | [FileStream](./) クラスの新しいインスタンスを構築し、指定されたパラメータで初期化します。 |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | このストリームのバッファをクリアし、すべてのバッファデータを基になるファイルへ書き込みます。 |
| void [Flush](./flush/)(**bool**) | このストリームのバッファをクリアし、すべてのバッファデータを基になるファイルへ書き込みます。[Flush()](./flush/) メソッドの同義語です。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | このストリームのすべてのバッファを非同期でクリアし、バッファされたデータを基になるデバイスへ書き込み、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | このストリームのすべてのバッファを非同期でクリアし、バッファされたデータを基になるデバイスへ書き込み、キャンセル要求を監視します。 |
| **bool** [get_CanRead](./get_canread/)() const override | ストリームが読み取り可能かどうかを判定します。 |
| **bool** [get_CanSeek](./get_canseek/)() const override | ストリームがシークをサポートしているかどうかを判定します。 |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 現在のストリームがタイムアウトできるかどうかを示す値を取得します。 |
| **bool** [get_CanWrite](./get_canwrite/)() const override | ストリームが書き込み可能かどうかを判定します。 |
| **int64_t** [get_Length](./get_length/)() const override | ストリームの長さ（バイト単位）を返します。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 現在の [FileStream](./) オブジェクトがカプセル化しているファイル名を返します。 |
| **int64_t** [get_Position](./get_position/)() const override | ストリームの現在位置を返します。 |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | タイムアウトになるまでストリームが読み取りを試みる時間（ミリ秒）を示す値を取得します。 |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | タイムアウトになるまでストリームが書き込みを試みる時間（ミリ秒）を示す値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | ストリームから指定されたバイト数を読み取り、指定されたバイトスパンに書き込みます。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | 現在のストリームからバイト列を非同期で読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームからバイト列を非同期で読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。 |
| **int32_t** [ReadByte](./readbyte/)() override | ストリームから 1 バイトを読み取り、読み取ったバイトの値に相当する 32 ビット整数値を返します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 現在のオブジェクトが表すストリームの位置を設定します。 |
| void [set_Position](./set_position/)(**int64_t**) override | ストリームをフラッシュし、続いてストリームの位置を設定します。 |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 現在のストリームがタイムアウトできるかどうかを決定する値を設定します。 |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | タイムアウトになるまでストリームが読み取りを試みる時間（ミリ秒）を示す値を設定します。 |
| void [SetLength](./setlength/)(**int64_t**) override | 現在のオブジェクトが表すストリームの長さを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 指定されたバイト配列の指定されたサブレンジのバイトを書き込み、ストリームに送ります。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 指定されたバイト配列の指定されたサブレンジのバイトを書き込み、ストリームに送ります。 |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 指定されたバイト配列の指定されたサブレンジのバイトを書き込み、ストリームに送ります。 |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 指定されたバイトスパンの指定されたサブレンジのバイトを書き込み、ストリームに送ります。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | 現在のストリームへバイト列を非同期で書き込み、書き込んだバイト数だけストリーム内の現在位置を進め、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームへバイト列を非同期で書き込み、書き込んだバイト数だけストリーム内の現在位置を進め、キャンセル要求を監視します。 |
| void [WriteByte](./writebyte/)(**uint8_t**) override | 指定された符号なし 8 ビット整数値を書き込み、ストリームに送ります。 |
|  [~FileStream](./~filestream/)() | デストラクタ。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | 読み取り・書き込み操作中にバッファリングされるバイト数のデフォルト値です。 |
| static [Null](../stream/null/) | 基礎となるストレージを持たないストリームです。 |

## 参照

* クラス [Stream](../stream/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)