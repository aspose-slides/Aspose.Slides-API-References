---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides for C++ API リファレンス
description: "std::basic_istream とその派生オブジェクト用の System.IO.Stream ライクなラッパーを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。実行時エラーやアサーション障害が発生する可能性があります。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 14
url: /ja/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper クラス


[System.IO.Stream](../stream/) のようなラッパーで、std::basic_istream とその派生オブジェクトを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。実行時エラーやアサーション障害が発生する可能性があります。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | [BasicSTDIStreamWrapper](./) の新しいインスタンスを構築します。 |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | コピーコンストラクタ。削除されました。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期読み取り操作を開始します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 非同期書き込み操作を開始します。 |
| virtual void [Close](../stream/close/)() | ストリームを閉じます。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 指定されたストリームにバイトをコピーします。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 指定されたバッファサイズを使用して、指定されたストリームにバイトをコピーします。 |
| void [Dispose](../stream/dispose/)() override | 現在のオブジェクトが使用するすべてのリソースを解放し、ストリームを閉じます。 |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 指定された非同期読み取り操作が完了するまで待機します。 |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 非同期書き込み操作を終了します。指定された非同期書き込み操作が完了するまで待機します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにも関わらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにも関わらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| void [Flush](./flush/)() override | このストリームのバッファをクリアし、すべてのバッファデータを基底ストレージに書き込みます。サポートされていません！ |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | このストリームのすべてのバッファを非同期でクリアし、バッファされたデータを基底デバイスに書き込み、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | このストリームのすべてのバッファを非同期でクリアし、バッファされたデータを基底デバイスに書き込み、キャンセル要求を監視します。 |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | ストリームがシークをサポートしているかどうかを判断します。 |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 現在のストリームがタイムアウトできるかどうかを決定する値を取得します。 |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | ストリームが書き込みをサポートしているかどうかを判断します。 |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | ストリームの長さを返します。 |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | ストリームの現在の位置を返します。 |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | ミリ秒単位で、ストリームがタイムアウトする前に読み取りを試みる時間を決定する値を取得します。 |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | ミリ秒単位で、ストリームがタイムアウトする前に書き込みを試みる時間を決定する値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | コピー代入演算子。削除されました。 |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | コピー代入演算子。削除されました。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ラップモードがバイナリの場合、ストリームから指定されたバイト数を読み取り、そうでない場合は指定された文字数を読み取り **uint8_t** 型に変換します。読み取り結果を指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。 |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | ストリームから指定されたバイト数を読み取り、指定されたバイトスパンに書き込みます。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 現在のストリームからバイトのシーケンスを非同期で読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームからバイトのシーケンスを非同期で読み取り、読み取ったバイト数だけストリーム内の位置を進め、キャンセル要求を監視します。 |
| int [ReadByte](./readbyte/)() override | ラップモードがバイナリの場合、最後にデコードされた文字ストレージから単一バイトを読み取ります。そうでない場合はストリームから単一文字を読み取り、**uint8_t** 型に変換します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースの特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースの特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI 情報です。 |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 現在のオブジェクトが表すストリームの位置を設定します。 |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | ストリームの位置を設定します。 |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 現在のストリームがタイムアウトできるかどうかを決定する値を設定します。 |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | ミリ秒単位で、ストリームがタイムアウトする前に読み取りを試みる時間を決定する値を設定します。 |
| void [SetLength](./setlength/)(**int64_t**) override | 現在のオブジェクトが表すストリームの長さを設定します。サポートされていません！ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンターの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントして返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | コピーコンストラクタ。削除されました。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ラップモードがバイナリの場合、指定されたバイト配列から指定されたサブレンジのバイトを書き込みます。そうでない場合は、指定されたバイト配列から指定されたサブレンジのバイトを char_type 型に変換し、結果を書き込みます。サポートされていません！ |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 指定されたバイト配列から指定されたサブレンジのバイトを書き込みます。 |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 指定されたバイト配列から指定されたサブレンジのバイトを書き込みます。 |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 指定されたバイトスパンから指定されたサブレンジのバイトを書き込みます。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけストリーム内の現在位置を進め、キャンセル要求を監視します。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけストリーム内の現在位置を進め、キャンセル要求を監視します。 |
| void [WriteByte](./writebyte/)(**uint8_t**) override | ラップモードがバイナリの場合、指定された符号なし 8 ビット整数値を書き込みます。そうでない場合は char_type 型に変換し、結果を書き込みます。サポートされていません！ |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Null](../stream/null/) | 基底ストレージを持たないストリームです。 |

## typedef

| typedef | 説明 |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## 参照

* クラス [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)