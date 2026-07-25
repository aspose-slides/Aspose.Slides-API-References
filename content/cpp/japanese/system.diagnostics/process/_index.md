---
title: Process
second_title: Aspose.Slides for C++ API リファレンス
description: "プロセス情報と操作をカプセル化します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション違反が発生します。このクラスは必ず System::SmartPtr ポインタでラップし、そのポインタを引数として関数に渡して使用してください。"
type: docs
weight: 27
url: /ja/system.diagnostics/process/
---
## Process クラス

Encapsulates process information and manipulation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Process : public System::Object
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **bool** [get_EnableRaisingEvents](./get_enableraisingevents/)() const | プロセスが終了したときに event Exited を発生させるかどうかを取得します。 |
| int [get_ExitCode](./get_exitcode/)() const | プロセスの終了コードを取得します。 |
| **int64_t** [get_PrivateMemorySize64](./get_privatememorysize64/)() const | プロセスのプライベートメモリセットサイズを取得します。 |
| [String](../../system/string/) [get_ProcessName](./get_processname/)() const | プロセス名を取得します。 |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardError](./get_standarderror/)() const | プロセスのエラー出力を読むためのリーダーを提供します。実装されていません。 |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardOutput](./get_standardoutput/)() const | プロセスの標準出力を読むためのリーダーを提供します。実装されていません。 |
| [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\> [get_StartInfo](./get_startinfo/)() const | プロセス開始情報を取得します。 |
| **int64_t** [get_WorkingSet64](./get_workingset64/)() const | プロセスのメモリ作業セットサイズを取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [GetCurrentProcess](./getcurrentprocess/)() | 現在のプロセスに関する情報を取得します。[Windows](../../system.windows/) のみです。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [String](../../system/string/) [GetOutputText](./getoutputtext/)() const | プロセスの出力テキストを取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合に対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定した値だけ共有参照カウントを減少させます。 |
| void [set_EnableRaisingEvents](./set_enableraisingevents/)(**bool**) | プロセスが終了したときに event Exited を発生させるかどうかを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱ポインタに設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、戻り値として返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| **bool** [Start](./start/)() | 事前定義されたパラメータでプロセスを開始します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたパスと引数でプロセスを開始します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\>\&) | 指定されたパスと引数でプロセスを開始します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| **bool** [WaitForExit](./waitforexit/)(int) | プロセスが終了するのを待ちます。実装されていません。 |
| void [WaitForExit](./waitforexit/)() | プロセスが終了するまで待機し、完了するまで戻りません。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
| virtual  [~Process](./~process/)() | デストラクタです。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Diagnostics](../)
* ライブラリ [Aspose.Slides](../../)