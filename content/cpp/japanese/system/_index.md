---
title: System
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 274
url: /ja/system/
---
## クラス

| Class | Description |
| --- | --- |
| [Activator](./activator/) | オブジェクトのタイプを作成するメソッドを含みます。 |
| [Array](./array/) | 配列データ構造を表すクラスです。このクラスのオブジェクトは [System::MakeArray()](./makearray/) と [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [ArrayBase](./arraybase/) | [System.Array](./array/) クラス（すべての配列の抽象基底クラス）のダミーです。機能は要請に応じて追加できます。 |
| [ArraySegment](./arraysegment/) | 一次元配列のセグメントを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](./smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。 |
| [Attribute](./attribute/) | カスタム属性の基底クラスです。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BitConverter](./bitconverter/) | バイト列を値型に、またはその逆に変換するメソッドを含みます。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [Boolean](./boolean/) | [System.Boolean](./boolean/) .[Net](../system.net/) 型の静的メンバーを保持するクラスです。 |
| [BoxedEnum](./boxedenum/) | ボックス化された列挙型の値を表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BoxedValue](./boxedvalue/) | ボックス化された値を表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | 値タプルのボックス化バージョンです。 |
| [BoxedValueBase](./boxedvaluebase/) | ボックス化された値を表す派生クラスのインターフェイスを定義し、基本的なメソッドを実装する基底クラスです。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Buffer](./buffer/) | 生バイト配列を操作するメソッドを含みます。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [Byte](./byte/) | 符号なし 8 ビット整数を操作するメソッドを含みます。 |
| [Char](./char/) | UTF-16 コード単位で表される文字の操作メソッドを提供します。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [Comparison](./comparison/) | 同じ型のオブジェクトを比較するメソッドへのポインタを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](./smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。 |
| [Console](./console/) | 標準出力ストリームへのデータ出力メソッドを提供します。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [ConsoleOutput](./consoleoutput/) | 標準出力ストリームを表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [DateTime](./datetime/) | 時間連続体上の特定の日時値を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](./smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。 |
| [DateTimeOffset](./datetimeoffset/) | 協定世界時 (UTC) に対する日付と時刻を含みます。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [DBNull](./dbnull/) | 存在しない値を表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Decimal](./decimal/) | 10 進数を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](./smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。 |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) クラスの実装です。共通コードを複製せずに BoxingValue の特殊化を宣言できるようにします。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数のみで割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 関数、メソッド、または関数オブジェクトへのポインタを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](./smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。 |
| [Details_AggregateException](./details_aggregateexception/) | 複数の内部例外を含む例外を表します。 |
| [Details_ApplicationException](./details_applicationexception/) | アプリケーション例外（システム例外ではなく）を表すクラスの基底クラスです。このクラスのインスタンスを手動で作成しないでください。代わりに ApplicationException クラスを使用してください。ApplicationException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_ArgumentException](./details_argumentexception/) | 引数が無効な場合に ArgumentException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArgumentException クラスを使用してください。ArgumentException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | メソッドが受け取った引数が期待範囲外の場合に ArgumentOutOfRangeException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArgumentOutOfRangeException クラスを使用してください。ArgumentOutOfRangeException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_ArithmeticException](./details_arithmeticexception/) | 算術演算やキャスト変換中にエラーが発生したときに ArithmeticException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArithmeticException クラスを使用してください。ArithmeticException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_BadImageFormatException](./details_badimageformatexception/) | 動的リンクライブラリ (DLL) または実行可能プログラムのイメージが無効な場合に BadImageFormatException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに BadImageFormatException クラスを使用してください。BadImageFormatException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | 0 での除算が試みられたときに DivideByZeroException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに DivideByZeroException クラスを使用してください。DivideByZeroException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_Exception](./details_exception/) | 例外を表します。このクラスのインスタンスを手動で作成しないでください。代わりに Exception クラスを使用してください。Exception クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | エラーコードを持つ例外用のテンプレートクラスです。 |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | ファイル名を持つ例外用のテンプレートクラスです。 |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException は互換性のためだけに存在します。 |
| [Details_FormatException](./details_formatexception/) | 引数の形式が無効な場合に FormatException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに FormatException クラスを使用してください。FormatException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | コレクションの要素に対し範囲外のインデックスでアクセスしようとしたときに IndexOutOfRangeException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに IndexOutOfRangeException クラスを使用してください。IndexOutOfRangeException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_InvalidCastException](./details_invalidcastexception/) | 無効な明示的変換が試みられたときに InvalidCastException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに InvalidCastException クラスを使用してください。InvalidCastException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | オブジェクトの状態が呼び出しと整合しないときに InvalidOperationException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに InvalidOperationException クラスを使用してください。InvalidOperationException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException は互換性のためだけに存在します。このクラスのインスタンスを手動で作成しないでください。代わりに InvalidProgramException クラスを使用してください。InvalidProgramException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | タイムゾーン情報が無効な場合に InvalidTimeZoneException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに InvalidTimeZoneException クラスを使用してください。InvalidTimeZoneException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_MemberAccessException](./details_memberaccessexception/) | 存在しないクラスのメンバーへのアクセス、またはアクセスが許可されていない場合に MemberAccessException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに MemberAccessException クラスを使用してください。MemberAccessException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_MethodAccessException](./details_methodaccessexception/) | 存在しないメソッドへのアクセス、またはアクセスが許可されていない場合に MethodAccessException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに MethodAccessException クラスを使用してください。MethodAccessException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_NotImplementedException](./details_notimplementedexception/) | 実装されておらずスタブとして機能するメソッドが呼び出されたときに NotImplementedException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに NotImplementedException クラスを使用してください。NotImplementedException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_NotSupportedException](./details_notsupportedexception/) | 呼び出されたメソッドがサポートされていない、またはストリーム上の操作がサポートされていない場合に NotSupportedException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに NotSupportedException クラスを使用してください。NotSupportedException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_NullReferenceException](./details_nullreferenceexception/) | null 参照のデリファレンスが試みられたときに NullReferenceException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに NullReferenceException クラスを使用してください。NullReferenceException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | オブジェクトが破棄された状態でメソッドが呼び出されたときに ObjectDisposedException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ObjectDisposedException クラスを使用してください。ObjectDisposedException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | スレッドが実行中の操作をキャンセルされたときに OperationCanceledException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに OperationCanceledException クラスを使用してください。OperationCanceledException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | オーバーフローが発生したときに OverflowException がスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに OverflowException クラスを使用してください。OverflowException クラスのインスタンスを [System::SmartPtr](./smartptr/) でラップしないでください。 |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | PlatformNotSupportedException は、機能が特定のプラットフォームで実行されない場合にスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに PlatformNotSupportedException クラスを使用してください。PlatformNotSupportedException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_RankException](./details_rankexception/) | RankException は、期待される次元数と異なる配列引数がメソッドに渡されたときにスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに RankException クラスを使用してください。RankException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_StackOverflowException](./details_stackoverflowexception/) | StackOverflowException は、スレッドの実行スタックがオーバーフローしたときにスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに StackOverflowException クラスを使用してください。StackOverflowException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_SystemException](./details_systemexception/) | システム（アプリケーションではなく）例外を表すクラスの基底クラスです。このクラスのインスタンスを手動で作成しないでください。代わりに SystemException クラスを使用してください。SystemException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_TimeoutException](./details_timeoutexception/) | TimeoutException は、プロセスまたは操作に割り当てられた時間が期限切れであることを示します。このクラスのインスタンスを手動で作成しないでください。代わりに TimeoutException クラスを使用してください。TimeoutException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | TimeZoneNotFoundException は、タイムゾーン情報が見つからないときにスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに TimeZoneNotFoundException クラスを使用してください。TimeZoneNotFoundException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | UnauthorizedAccessException は、I/O エラーまたはセキュリティエラーが原因でオペレーティングシステムからアクセスが拒否されたときにスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに UnauthorizedAccessException クラスを使用してください。UnauthorizedAccessException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Details_UriFormatException](./details_uriformatexception/) | UriFormatException は、URI の形式が無効なときにスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに UriFormatException クラスを使用してください。UriFormatException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [DynamicWeakPtr](./dynamicweakptr/) | スマートポインタクラスは、格納されたオブジェクトのテンプレート引数のポインタモードを追跡し、各代入後に更新します。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡すべきです。 |
| [EnumValues](./enumvalues/) | enum 型 **E** の列挙定数に関するメタ情報を提供します。 |
| [EnumValuesBase](./enumvaluesbase/) | 列挙型のメタ情報を表すクラスの基底クラスです。 |
| [EventArgs](./eventargs/) | イベントがトリガーされたときにイベント購読者に渡されるコンテキストを表すクラスの基底クラスです。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [ExceptionWrapper](./exceptionwrapper/) | Exception クラスから派生した例外のラッパーを表すテンプレートです。 |
| [FlagsAttribute](./flagsattribute/) | 列挙型をビットフィールド、すなわち集合として扱えることを示します。 |
| [Func](./func/) | 関数デリゲートです。この型はスタック上に割り当て、関数には値渡しまたは参照で渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](./smartptr/) クラスを使用しないでください。 |
| [GC](./gc/) | 実際には何も行わないスタブのように振る舞うエミュレートされたガベージコレクションを表します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。 |
| [Guid](./guid/) | Globally Unique IDentifier を表します。この型はスタック上に割り当て、関数には値渡しまたは参照で渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](./smartptr/) クラスを使用しないでください。 |
| [IAsyncResult](./iasyncresult/) | 非同期操作のステータスを表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [ICloneable](./icloneable/) | オブジェクトのクローン作成（コピー作成）を可能にするメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [IComparable](./icomparable/) | 2 つのオブジェクトを比較するメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [IConvertible](./iconvertible/) | 実装された参照型または値型の値を、同等の値を持つ共通言語ランタイム型に変換するメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [ICustomFormatter](./icustomformatter/) | 指定されたオブジェクトが表す値の文字列表現をカスタムフォーマットするメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [IDisposable](./idisposable/) | 現在のオブジェクトが所有するリソースを解放するメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [IEquatable](./iequatable/) | 2 つのオブジェクトの等価性を判定するメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [IFormatProvider](./iformatprovider/) | 書式情報を提供するメソッドを定義します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [IFormattable](./iformattable/) | 指定された書式文字列と書式プロバイダーを使用して、現在のオブジェクトの値をフォーマットするメソッドを定義します。 |
| [Index](./index/) | コレクション内のインデックスを表します。インデックスは先頭からでも末尾からでも指定できます。この型はスタック上に割り当て、関数には値渡しまたは参照で渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](./smartptr/) クラスを使用しないでください。 |
| [Int16](./int16/) | 16 ビット整数を操作するメソッドを含みます。 |
| [Int32](./int32/) | 32 ビット整数を操作するメソッドを含みます。 |
| [Int64](./int64/) | 64 ビット整数を操作するメソッドを含みます。 |
| [LockContext](./lockcontext/) | C# の lock() 文を実装するガードオブジェクトです。 |
| [MarshalByRefObject](./marshalbyrefobject/) | リモート処理が有効なアプリケーションで、アプリケーションドメイン境界を越えてオブジェクトへのアクセスを提供します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | デリゲートのコレクションを表します。この型はスタック上に割り当て、関数には値渡しまたは参照で渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](./smartptr/) クラスを使用しないでください。 |
| [Nullable](./nullable/) | 前方宣言です。 |
| [NullableUtils](./nullableutils/) | C# の [System.Nullable](./nullable/)（型引数なし）静的クラスを表します。C++ ではクラステンプレートのオーバーロードができないため、元の名前は使用できません。null を代入可能な値型をサポートします。このクラスは継承できません。 |
| [Object](./object/) | [System.Object](./object/) クラスで利用可能なメソッドを C# で使用できるようにする基底クラスです。変換された環境で使用されるすべての非自明クラスはこれを継承すべきです。 |
| [ObjectExt](./objectext/) | 非オブジェクト C++ 型（文字列、数値等）に対して呼び出される C# の [Object](./object/) メソッドをエミュレートする静的メソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。 |
| [ObjectType](./objecttype/) | オブジェクトの型取得子を実装する静的メソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。 |
| [OperatingSystem](./operatingsystem/) | 特定のオペレーティングシステムを表し、その情報を提供します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [Random](./random/) | 疑似乱数ジェネレータを表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。 |
| [Range](./range/) | 開始インデックスと終了インデックスを持つ範囲を表します。この型はスタック上に割り当て、関数には値渡しまたは参照で渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](./smartptr/) クラスを使用しないでください。 |
| [ReadOnlySpan](./readonlyspan/) | [Span](./span/) クラス内で使用するための前方宣言です。 |
| [ScopedCulture](./scopedculture/) | スコープ内で使用されるカルチャを表します。 |
| [SmartPtr](./smartptr/) | ヒープ上に割り当てられる型をラップするポインタクラスです。[Object](./object/) を継承するクラスのメモリ管理に使用します。このポインタ型は侵入型ポインタのセマンティクスに従います。参照カウンタは [Object](./object/) 自体または [Object](./object/) インスタンスに tightly 結び付けられたカウンタ構造体に格納されます。いずれの場合も、[SmartPtr](./smartptr/) インスタンスは作成方法にかかわらず単一所有グループを形成し、std::shared_ptr クラスの動作とは異なります。生ポインタを [SmartPtr](./smartptr/) に変換しても、同じオブジェクトへの共有参照を保持している他の [SmartPtr](./smartptr/) インスタンスがある限り安全です。[SmartPtr](./smartptr/) クラスのインスタンスは、共有ポインタと弱ポインタの 2 つの状態のいずれかになります。オブジェクトを存続させるには、共有参照のカウントが正である必要があります。弱ポインタと共有ポインタの両方で、対象オブジェクトへ（メソッド呼び出し、フィールドの読み書き等）アクセスできますが、弱ポインタは共有ポインタの参照カウントに参加しません。[Object](./object/) は、最後の 'shared' [SmartPtr](./smartptr/) ポインタが破棄されたときに削除されます。したがって、オブジェクト構築や破棄中など、他に共有 [SmartPtr](./smartptr/) ポインタが存在しない場合にこれが起こらないようにしてください。System::Object::ThisProtector の sentinel オブジェクト（C++ コード）または CppCTORSelfReference、CppSelfReference 属性（翻訳対象の C# コード）を使用してこの問題を修正します。同様に、[System::WeakPtr](./weakptr/) ポインタクラスや [System::SmartPtrMode::Weak](./smartptrmode/) ポインタモード（C++ コード）または CppWeakPtr 属性（翻訳対象の C# コード）を使用してループ参照を解除してください。複数のオブジェクトが 'shared' ポインタで相互に参照し合うと、決して削除されません。実行時にポインタ型（弱または共有）を切り替える必要がある場合は、[System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) メソッドまたは [System::DynamicWeakPtr](./dynamicweakptr/) クラスを使用します。[SmartPtr](./smartptr/) クラスは仮想メソッドを含みません。独自のメモリ管理戦略を作成する場合にのみ継承すべきです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡す必要があります。 |
| [SmartPtrInfo](./smartptrinfo/) | 最終型を知らずに [SmartPtr](./smartptr/) の内容をテストおよび変更するためのサービスクラスです。ガベージコレクションやループ参照検出などに使用されます。「ポインタからポインタ」と考えてください。[SmartPtr](./smartptr/) の基底型は存在しないため使用できません。その代わりにこの 'info' クラスを使用します。 |
| [Span](./span/) | 任意のメモリの連続領域を表し、C++20 の std::span に似ています。 |
| [String](./string/) | [String](./string/) クラスはライブラリ全体で使用されます。コード変換時の C# の [System.String](./string/) の代替です。最適化のため、[Object](./object/) のサブクラスとはみなされません。この型はスタック上に割り当て、関数には値渡しまたは参照で渡す必要があります。この型のオブジェクト管理に [System::SmartPtr](./smartptr/) クラスは使用しないでください。 |
| [StringComparer](./stringcomparer/) | 異なる比較モードで文字列を比較します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用すると、ランタイムエラーやアサーション失敗につながります。必ずこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [StringHashCompiletime](./stringhashcompiletime/) | c文字列からハッシュ値を生成するヘルパークラスです。 |
| [TimeSpan](./timespan/) | 時間間隔を表します。この型はスタック上に割り当て、関数には値渡しまたは参照で渡す必要があります。この型のオブジェクト管理に [System::SmartPtr](./smartptr/) クラスは使用しないでください。 |
| [TimeZone](./timezone/) | タイムゾーンを表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用すると、ランタイムエラーやアサーション失敗につながります。必ずこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [TimeZoneInfo](./timezoneinfo/) | 特定のタイムゾーンを記述する情報を表します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用すると、ランタイムエラーやアサーション失敗につながります。必ずこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [Tuple](./tuple/) | タプルデータ構造を表すクラスです。最大項目数は 8 です。 |
| [TupleFactory](./tuplefactory/) | タプルオブジェクト作成のための static メソッドを提供します。 |
| [TypeInfo](./typeinfo/) | 特定の型を表し、その情報を提供します。 |
| [Uri](./uri/) | 統一リソース識別子です。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用すると、ランタイムエラーやアサーション失敗につながります。必ずこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [UriBuilder](./uribuilder/) | ユニバーサルリソース識別子 (URI) の構築と変更のためのメソッドを提供します。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用すると、ランタイムエラーやアサーション失敗につながります。必ずこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [UriParser](./uriparser/) | 新しい URI スキームを解析するために使用されます。このクラスのオブジェクトは [System::MakeObject()](./makeobject/) 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用すると、ランタイムエラーやアサーション失敗につながります。必ずこのクラスを [System::SmartPtr](./smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [UriShim](./urishim/) | サービスクラスです。 |
| [ValueTuple](./valuetuple/) | [ValueTuple](./valuetuple/) データ構造を表すクラスです。 |
| [ValueType](./valuetype/) | [Object](./object/) 継承がパフォーマンス上の理由で切り捨てられた値型の基底クラスです。この型はスタック上に割り当て、関数には値渡しまたは参照で渡す必要があります。この型のオブジェクト管理に [System::SmartPtr](./smartptr/) クラスは使用しないでください。 |
| [Version](./version/) | バージョン番号を表します。この型はスタック上に割り当て、関数には値渡しまたは参照で渡す必要があります。この型のオブジェクト管理に [System::SmartPtr](./smartptr/) クラスは使用しないでください。 |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | [System::SmartPtr](./smartptr/) のサブクラスで、構築時に自身を弱モードに設定します。このクラスは [set_Mode()](./smartptr/set_mode/) が依然としてアクセス可能であるため、インスタンスが常に弱モードに留まることを保証しないことに注意してください。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡す必要があります。 |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | オブジェクトを参照しつつ、そのオブジェクトが削除可能である弱参照を表します。 |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | オブジェクトを参照しつつ、そのオブジェクトが削除可能である弱参照を表します。 |

## 構造体

| 構造体 | 説明 |
| --- | --- |
| [CastResult](./castresult/) | キャスト結果を推論するテンプレートマジックです。 |
| [CollectionAssertHelper](./collectionasserthelper/) | コレクション関連操作のためのヘルパー API です。 |
| [Convert](./convert/) | ある型の値を別の型の値に変換するメソッドを含む構造体です。この型はスタック上に割り当て、関数には値渡しまたは参照で渡す必要があります。この型のオブジェクト管理に [System::SmartPtr](./smartptr/) クラスは使用しないでください。 |
| [Double](./double/) | 倍精度浮動小数点数を扱うメソッドを含みます。 |
| [Enum](./enum/) | 列挙型の値に対していくつかの操作を行うメソッドを提供します。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。 |
| [EnumGetNameHelper](./enumgetnamehelper/) | 列挙定数の文字列名取得機能を提供するヘルパークラスです。 |
| [EnumParseHelper](./enumparsehelper/) | 列挙定数の文字列表現を対応する列挙値に変換する機能を提供するヘルパークラスです。 |
| [Environment](./environment/) | [Environment](./environment/) サービスです。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。 |
| [HolderInitializer](./holderinitializer/) | このクラスはオブジェクトインスタンスへの永続参照を取得するために使用されます（lvalue でも rvalue でもかまいません）。そのような参照を取得するには、'HoldIfTemporary' メソッドを使用します。このメソッドには 3 つのオーバーロードがあります。2 つは rvalue をパラメータとして受け取り、その参照を返します。残りの 1 つは lvalue をパラメータとして受け取り、ポインタのコピーを作成してそのコピーへの参照を返します。また、クラスには渡された値を無条件に保持する 'Hold' メソッドがあり（ローカルのスタック変数やその子参照の値をコピーする際に使用されます）。 |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | [HolderInitializer](./holderinitializer/) の特殊化で、T が値型の場合です。使用コンテキストでは一時オブジェクトへの参照を返すことが許可されており、インスタンスが呼び出し側によってコピーされることが保証されています。そのため、この特殊化はスタブとして使用され、何もしません。 |
| [IsBoxable](./isboxable/) | 指定された型の boxing がサポートされているかをチェックするテンプレート述語です。 |
| [IsExceptionWrapper](./isexceptionwrapper/) | 指定された型が Exception クラスまたはその派生クラスかどうかを判定するテンプレート述語です。 |
| [IsNullable](./isnullable/) | テンプレート引数 T が [Nullable](./nullable/) またはそのサブクラスであるかどうかを判定するテンプレート述語です。 |
| [IsSmartPtr](./issmartptr/) | [SmartPtr](./smartptr/) クラスの特殊化かどうかをチェックするトレイトクラスです。 |
| [IsStringByteSequence](./isstringbytesequence/) | 型が文字列文字のシーケンスかどうかをチェックするテンプレートマジックです。 |
| [IsStringLiteral](./isstringliteral/) | 型が文字列リテラルかどうかをチェックするテンプレートマジックです。 |
| [IsStringPointer](./isstringpointer/) | 型が文字列へのポインタかどうかをチェックするテンプレートマジックです。 |
| [IsWeakPtr](./isweakptr/) | 特定のクラスが [System::WeakPtr](./weakptr/) の特殊化かどうかをチェックするトレイトクラスです。インスタンスが実際に弱モードかどうかはチェックしません。 |
| [MakeConstRef](./makeconstref/) | 型が [String](./string/) または SmartPtr<> の場合に、汎用型を "const reference" に変換するトレイトです。 |
| [Math](./math/) | 数学関数を含みます。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。 |
| [MathF](./mathf/) | 単精度浮動小数点値用の数学関数を含みます。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。 |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | メソッド引数を格納するタプルを定義します。 |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | メソッド引数を格納するタプルを定義します。 |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | メソッド引数を格納するタプルを定義します。 |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | [TypeInfo](./typeinfo/) オブジェクトへのポインタを表し、MulticastDelegate クラスに関する情報を含みます。 |
| [RemoveShared](./removeshared/) | 引数型から SharedPtr/WeakPtr を除去するトレイト構造体です。 |
| [SByte](./sbyte/) | 8 ビット整数を扱うメソッドを含みます。 |
| [ScopeGuard](./scopeguard/) | クラスのインスタンスがスコープ外になると特定の関数オブジェクトを実行するサービスを提供するサービスクラスです。 |
| [Single](./single/) | 単精度浮動小数点数を扱うメソッドを含みます。 |
| [TestCompare](./testcompare/) | コレクションを比較するインターフェースを提供するサービス構造体です。 |
| [TestTools](./testtools/) | さまざまな型や関数の基本的な特性をチェックする有用なメソッド群を提供します。 |
| [TestToolsExt](./testtoolsext/) | テスト翻訳で使用される共通関数です。 |
| [TypeInfoPtr](./typeinfoptr/) | [TypeInfo](./typeinfo/) クラスのインスタンスへのポインタのラッパーです。この型はスタック上に割り当て、関数には値渡しまたは参照で渡す必要があります。この型のオブジェクト管理に [System::SmartPtr](./smartptr/) クラスは使用しないでください。 |
| [UInt16](./uint16/) | 符号なし 16 ビット整数を扱うメソッドを含みます。 |
| [UInt32](./uint32/) | 符号なし 32 ビット整数を扱うメソッドを含みます。 |
| [UInt64](./uint64/) | 符号なし 64 ビット整数を扱うメソッドを含みます。 |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | [TypeInfo](./typeinfo/) オブジェクトへのポインタを表し、[ValueTuple](./valuetuple/) クラスに関する情報を含みます。 |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | 引数型がポインタ型の場合に弱ポインタに変換するトレイト構造体です。 |

## 関数

| 関数 | 説明 |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | 指定された初期化リストの要素で新しい [Array](./array/) オブジェクトを構築し、[Array](./array/) オブジェクトを指すスマートポインタを返すファクトリ関数です。 |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | 指定された引数をコンストラクタに渡して新しい [Array](./array/) オブジェクトを構築するファクトリ関数です。 |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | 指定された引数をコンストラクタに渡して、新しい [Array](./array/) オブジェクトを構築するファクトリ関数です。 |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 指定された [Nullable](./nullable/) オブジェクトが null と等しい値を表すかどうかを判定します。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | [operator==()](./operator_equal_equal/) を適用して得られる、指定された [Nullable](./nullable/) オブジェクトが表す値と指定された値が等しいかどうかを判定します。 |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 2つのスマートポインタを等価比較します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | スマートポインタが null かどうかをチェックします。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | スマートポインタと単純な (C) ポインタとの等価比較を行います。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | スマートポインタと単純な (C) ポインタとの等価比較を行います。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | 値型オブジェクト（変換された C# 構造体など）が null かどうかをチェックします。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | 値型オブジェクト（変換された C# 構造体など）が null かどうかをチェックします。 |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) と文字列の比較。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | 文字列が null かどうかをチェックします。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 現在のオブジェクトと指定されたオブジェクトが表す URI が等しいかどうかを判定します。 |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 指定された [Nullable](./nullable/) オブジェクトが null と等しくない値を表すかどうかを判定します。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | [operator!=()](./operator_not_equal/) を適用して得られる、指定された [Nullable](./nullable/) オブジェクトが表す値と指定された値が等しくないかどうかを判定します。 |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 2つのスマートポインタを非等価比較します。 |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | スマートポインタが null でないかをチェックします。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | スマートポインタが null でないかをチェックします。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | スマートポインタと単純な (C) ポインタとの非等価比較を行います。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | スマートポインタと単純な (C) ポインタとの等価比較を行います。 |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) と文字列の比較。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | 文字列が null かどうかをチェックします。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 現在のオブジェクトと指定されたオブジェクトが表す URI が等しくないかどうかを判定します。 |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 常に false を返します。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | [operator<()](./operator_less/) を適用して得られる、指定された [Nullable](./nullable/) オブジェクトが表す値より、指定された値が小さいかどうかを判定します。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 常に false を返します。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | [operator<=()](./operator_less_equal/) を適用して得られる、指定された [Nullable](./nullable/) オブジェクトが表す値以下かどうかを判定します。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 常に false を返します。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | [operator>()](./operator_greater/) を適用して得られる、指定された [Nullable](./nullable/) オブジェクトが表す値より、指定された値が大きいかどうかを判定します。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 常に false を返します。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | [operator>=()](./operator_greater_equal/) を適用して得られる、指定された [Nullable](./nullable/) オブジェクトが表す値以上かどうかを判定します。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | 指定されたオブジェクトが表す値を指定された出力ストリームに書き込みます。 |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | 文字列を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | 値を std::ostream に出力します。主にデバッグで使用されます。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | UTF-8 エンコーディングを使用して文字列を出力ストリームに出力します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | 文字列を出力ストリームに出力します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | データをストリームに挿入します。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | UTF-8 エンコーディングを使用してデータをストリームに挿入します。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | データをストリームに挿入します。 |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | 2つの曜日間の日数を計算します。 |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | 指定された値から指定された [Decimal](./decimal/) オブジェクトが表す値を減算した結果の値を表す、[Decimal](./decimal/) クラスの新しいインスタンスを返します。 |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 右側デリゲートのすべてのコールバックを、左側デリゲートのコールバックリストの末尾から切り離します。 |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | nullable でない値と nullable な値を減算します。 |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | 指定された値と、指定された [Decimal](./decimal/) オブジェクトで表される値の合計を表す [Decimal](./decimal/) クラスの新しいインスタンスを返します。 |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 右側デリゲートのすべてのコールバックを左側デリゲートのコールバックリストの末尾に接続します。 |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | nullable でない値と nullable な値を合計します。 |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 連結。 |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 連結。 |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) 連結。 |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | 指定された値と、指定された [Decimal](./decimal/) オブジェクトで表される値の乗算結果を表す [Decimal](./decimal/) クラスの新しいインスタンスを返します。 |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | 指定された値と、指定された [Decimal](./decimal/) オブジェクトで表される値の除算結果を表す [Decimal](./decimal/) クラスの新しいインスタンスを返します。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 例外型のデフォルト構築された唯一のインスタンスへの参照を返します。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 例外でない型のデフォルト構築された唯一のインスタンスへの参照を返します。 |
| T\& [Discard](./discard/)(T\&&) | 指定された型のデフォルト構築された一時インスタンスを返します。これは '_' 引数を破棄する代わりに使用できます。 |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | 共有所有権でオブジェクトを構築します。 |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 共有所有権でオブジェクトの初期化を開始します。 |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | 配列を構築します。 |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | 直接所有権でオブジェクトを構築します。 |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | 'is' 宣言パターンの変換を実装します。 |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | 'is' 定数パターンの変換を実装します。 |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | トップレベルのマッチング関数です。パターンを値に適用します。 |
| static **bool** [IsNull](./isnull/)(const T\&) | 'is null' パターンを実装します。 |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | '<' 相対パターンの変換を実装します。 |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | '>' 相対パターンの変換を実装します。 |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) | '<=' 相対パターンの変換を実装します。 |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | '>=' 相対パターンの変換を実装します。 |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | 'var' パターンの変換を実装します。 |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | オブジェクトがタプルかどうかをチェックします（ITuple インターフェイスを実装）。位置パターン実装で使用されます。 |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | 与えられたタプルの N 番目要素を取得する関数です。ベースオブジェクト用のオーバーロードです。 |
| auto [Get](./get/)(const T\&) | 与えられたタプルの N 番目要素を取得する関数です。Deconstruct メソッドを持つオブジェクト用のオーバーロードです。 |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 与えられたタプルの N 番目要素を取得する関数です。共有ポインタ用のオーバーロードです。 |
| auto\& [Get](./get/)(T\&, const [Index](./index/)\&) | collection[index] 式の実装です。 |
| auto [Get](./get/)(T\&, const [Range](./range/)\&) | 提供された範囲で定義された、指定されたコレクションのスライスを返します。 |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | 値タプルの N 番目の要素を取得します。 |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | yield 関数から IEnumerable を作成します。 |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | yield 関数から IEnumerator を作成します。 |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | C# の try[-catch]-finally ステートメントの動作をエミュレートする単一関数です。translator のオプション finally_statement_as_lambda が true に設定された状態で C# の try[-catch]-finally ステートメントを変換する際、ステートメントはこのメソッドの呼び出しに変換されます。 |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | C# の try[-catch]-finally ステートメントの動作をエミュレートする単一関数です。translator のオプション finally_statement_as_lambda が true に設定された状態で C# の try[-catch]-finally ステートメントを変換する際、ステートメントはこのメソッドの呼び出しに変換されます。このオーバーロードは、try[-catch]-finally ステートメントの try[-catch] 部分を実装する関数オブジェクトの戻り値が bool の場合を処理します。 |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | C# の try[-catch]-finally ステートメントの動作をエミュレートする単一関数です。translator のオプション finally_statement_as_lambda が true に設定された状態で C# の try[-catch]-finally ステートメントを変換する際、ステートメントはこのメソッドの呼び出しに変換されます。このオーバーロードは、関数オブジェクトの戻り値が bool& の場合を処理します。 |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | [DynamicWeakPtr](./dynamicweakptr/) オブジェクトへの参照を作成します。関数引数を参照渡しする際にトランスレータで使用されます。 |
| T\& [Ref](./ref/)(T\&) | オブジェクトへの参照を取得するヘルパー関数です。[System::DynamicWeakPtr](./dynamicweakptr/) が代入後に参照オブジェクトを更新することを保証するために使用されます。 |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、begin()、end() メソッドを持たない Enumerable に対して、対象型引数を指定して (auto& value : IterateOver<SomeType>(enumerable)) のように使用するためのものです。 |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、begin()、end() メソッドを持たない Enumerable に対して、デフォルトの対象型引数で (auto& value : IterateOver(enumerable)) のように使用するもので、C# の foreach (var value in enumerable) に相当します。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、begin()、end() メソッドを持つ Enumerable に対して、デフォルトの対象型引数で (auto& value : IterateOver(enumerable)) のように使用するものです。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、begin()、end() メソッドを持ち、イテレータの元の value_type と同じ対象型を持つ Enumerable 用です。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、begin()、end() メソッドを持ち、対象型がイテレータの元の value_type と異なる Enumerable 用です。 |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、デフォルトの対象型を持つ Enumerable 用です。 |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | この関数プロパティは、enumerable（または iterable）オブジェクトをラップし、範囲ベースの for ループで使用できるようにします。このオーバーロードは、begin()、end() メソッドを持たない Enumerable に対して、対象型引数を指定して (auto& value : IterateOver<SomeType>(enumerable)) のように使用するものです。 |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 指定されたスカラー値のハッシュコードを返します。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 指定されたオブジェクトのハッシュコードを返します。 |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 例外である指定されたオブジェクトのハッシュコードを返します。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | スマートポインタでも例外でもない指定されたオブジェクトのハッシュコードを返します。 |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | std::thread::id 用の特殊化です。指定されたスレッドオブジェクトのハッシュコードを返します。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへのキャストを実行します。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへのキャストを実行します。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | 古い廃止予定のキャストです。将来のバージョンで削除されます。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへの dynamic_cast を実行します。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Object から Exception オブジェクトへの dynamic_cast を実行します。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | Exception オブジェクトへの dynamic_cast を実行します。 |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへの dynamic_cast を実行します。 |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | キャストによりボックス化された enum をアンボックスします。 |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | null オブジェクトへの dynamic_cast を実行します。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | ポインタでないオブジェクトへの dynamic_cast を実行します。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | Objects から Exception オブジェクトへの動的キャストを実行します。 |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | IntPtr からポインタへの動的キャストを実行します。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへの静的キャストを実行します。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | [WeakPtr](./weakptr/) オブジェクトへの静的キャストを実行します。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | Exception オブジェクトへの静的キャストを実行します。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Objects から Exception オブジェクトへの静的キャストを実行します。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへの静的キャストを実行します。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | [WeakPtr](./weakptr/) オブジェクトへの静的キャストを実行します。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | null オブジェクトへの静的キャストを実行します。 |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | 算術型の特殊化です。 |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | [String](./string/) から [String](./string/) へのキャストを処理します。 |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | 算術型の特殊化です。 |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | ポインタ以外のオブジェクトへの静的キャストを実行します。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | Exception オブジェクトへの静的キャストを実行します。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | Objects から Exception オブジェクトへの静的キャストを実行します。 |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | 非推奨キャストの終了です。 |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) オブジェクトへの実際の静的キャストを実行します。 |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | コピーコンストラクタを使用してメンバー単位のクローンを実行します。 |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | 参照レコードをクローンし、イニシャライザファンクタを適用します。 |
| T [With](./with/)(const T\&, const A\&) | 構造体レコードをコピーし、イニシャライザファンクタを適用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型を明示的キャストで結果型に変換します。ソース型と結果型が同じ場合に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型を明示的キャストで結果型に変換します。シンプルなコンストラクタ形式のキャストが必要な場合に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型を明示的キャストで結果型に変換します。例外ラッパーに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型を明示的キャストで結果型に変換します。オブジェクトを例外にキャストする際に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型と結果型がともにスマートポインタである場合に、明示的キャストでソース型を結果型に変換します（結果型に明示的な SmartPtr<...> が無い場合）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | 生ポインタをスマートポインタにキャストする際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型と結果型がともにスマートポインタであり、結果型に明示的な SmartPtr<...> がある場合に、明示的キャストでソース型を結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | オブジェクトを nullable にアンボックスする際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | nullable をボックスする際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | nullable オブジェクトをアンボックスする際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | 列挙型をボックスする際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 値型をヒープにコピーし、スマートポインタとして参照すべき場合に（インターフェイス型で制約されたジェネリックだが、そのインターフェイスを実装する構造体で特殊化された場合）、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 値型からインターフェイスを取得する際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 一般的なボックス処理の際、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型を明示的キャストで結果型に変換します。[System::String](./string/) のボックスに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ソース型を明示的キャストで結果型に変換し、インターフェイスのアンボックスに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 一般的なアンボックスに使用し、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | nullptr キャストに使用し、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 配列間のキャストに使用し、ソース型を明示的キャストで結果型に変換します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。シンプルなコンストラクタ形式のキャストが必要な場合に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。ソース型と結果型が同じ場合に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。例外ラッパーに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。オブジェクトを例外にキャストする際に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。ソース型と結果型がともにスマートポインタである場合に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。ソース型と結果型がともにスマートポインタであり、結果型に明示的な SmartPtr<...> がある場合に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。オブジェクトを nullable にアンボックスする際に使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。オブジェクトでない型へのアンボックスは無効です。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | オブジェクトでない型へのアンボックスは無効です。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。nullable オブジェクトのボックスに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。一般的なオブジェクトのボックスに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。一般的なオブジェクトのボックスに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。文字列のアンボックスに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。nullptr のキャストに使用します。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 演算子キャストを使用してソース型を結果型に変換します。配列間のキャストに使用します。 |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | '?.' 演算子の翻訳実装です。 |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | typeof() の翻訳を実装します。[String](./string/) のオーバーロードです。 |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | typeof() の翻訳を実装します。[DateTime](./datetime/) のオーバーロードです。 |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | [operator==()](./operator_equal_equal/) を適用して、二つの値の等価性を判定します。 |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | 単精度浮動小数点値に対する特殊化です。IEC 60559:1989 では、二つの NaN は常に等しくないと定義されていますが、[System.Object.Equals](./object/equals/) の契約では、オーバーライドが等価演算子の要件を満たす必要があります。そのため、System.Double.Equals と System.Single.Equals は二つの NaN を比較したときに true を返しますが、等価演算子はその場合 false を返します。これは標準が要求する動作です。 |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | 倍精度浮動小数点値に対する特殊化です。 |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 二つの値を比較します。 |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 2つの浮動小数点値を比較します。 |
| **bool** [IsNaN](./isnan/)(const T\&) | 指定された値が NaN (Not-A-Number) であるかどうかを判定します。 |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | 指定された値が無限大であるかどうかを判定します。 |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | 指定された値が正の無限大であるかどうかを判定します。 |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | 指定された値が負の無限大であるかどうかを判定します。 |
| TTo [CheckedCast](./checkedcast/)(TFrom) | 指定された値が型 **TTo** の値域に入っているかを判定し、入っている場合は **TTo** 型にキャストします。 |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | ScopedGuard クラスのインスタンスを作成するファクトリ関数です。 |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | 型変換を伴う静的セッター関数のオーバーロードです。 |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | 型変換を伴うインスタンス セッター関数のオーバーロードです。 |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# のインクリメント式を翻訳し、呼び出しに変換します。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# のインクリメント式を翻訳し、呼び出しに変換します。 |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# の後置インクリメント式を翻訳し、呼び出しに変換します。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の後置インクリメント式を翻訳し、呼び出しに変換します（非 const getter 用のオーバーロード）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の後置インクリメント式を翻訳し、呼び出しに変換します（const getter 用のオーバーロード）。 |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# の前置デクリメント式を翻訳し、呼び出しに変換します。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の前置デクリメント式を翻訳し、呼び出しに変換します（非 const getter 用のオーバーロード）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の前置デクリメント式を翻訳し、呼び出しに変換します（const getter 用のオーバーロード）。 |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# の後置デクリメント式を翻訳し、呼び出しに変換します。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の後置デクリメント式を翻訳し、呼び出しに変換します（非 const getter 用のオーバーロード）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の後置デクリメント式を翻訳し、呼び出しに変換します（const getter 用のオーバーロード）。 |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | ヒープ上にオブジェクトを作成し、それへの共有ポインタを返します。 |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | ヒープ上にオブジェクトを作成し、それへの共有ポインタを返します。 |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | 生ポインタをスマートポインタに変換します。 |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | 生ポインタをスマートポインタに変換します。const ポインタ用のオーバーロードです。たとえば、const として翻訳された C# メソッドで 'this' 変数を使用する場合に便利です。 |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | static_cast を使用してスマートポインタをキャストします。 |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | dynamic_cast を使用してスマートポインタをキャストします。 |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | const_cast を使用してスマートポインタをキャストします。 |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | スマートポインタが参照するオブジェクトを取得します。 |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 指定された enumerable オブジェクトの要素を明示的に別の型へキャストします。 |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 指定された enumerable オブジェクトの要素を明示的に別の型へキャストします。 |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 指定された配列の要素を別の型へキャストします。From が [SmartPtr](./smartptr/) オブジェクトである場合のオーバーライドです。 |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 指定された配列の要素を別の型へキャストします。From が Boxable で To が [Object](./object/)[] の場合のオーバーライドです。 |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | 指定された配列の要素を別の型へキャストします。 |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | UTF-8 エンコーディングを使用して、入力ストリームから文字列を取得します。 |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | 入力ストリームから文字列を取得します。 |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | スタック上にタプルを作成します。 |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | いくつかの値にバインドされたタプルを作成します。 |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Base-64 エンコードデータのさまざまな形式を表す値を含む列挙型です。 |
| [DateTimeKind](./datetimekind/) | 日付と時刻の種類を表す列挙値です。 |
| [DayOfWeek](./dayofweek/) | 曜日を表す列挙型です。 |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | 環境変数の位置を指定します。 |
| [MidpointRounding](./midpointrounding/) | 丸め関数の動作を指定します。 |
| [PlatformID](./platformid/) | オペレーティングシステムのプラットフォームを表します。 |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) ポインタ型：weak または shared。オブジェクトを削除するかどうか判断する際にポインタがカウントされるかを定義します。 |
| [StringSplitOptions](./stringsplitoptions/) | 文字列分割の動作を決定します。 |
| [StringComparison](./stringcomparison/) | 文字列比較のスタイルを定義します。 |
| [TypeCode](./typecode/) | オブジェクトの型を表します。 |
| [UriKind](./urikind/) | URI の種類を表します。 |
| [UriComponents](./uricomponents/) | URI の構成要素を表します。 |
| [UriFormat](./uriformat/) | URI がエスケープされる方法を指定します。 |
| [UriHostNameType](./urihostnametype/) | ホスト名のタイプを表します。 |
| [UriPartial](./uripartial/) | [Uri.GetLeftPart](./uri/getleftpart/) メソッドのための URI の部分を表します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | [System::IFormatProvider](./iformatprovider/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [DecoderFallbackPtr](./decoderfallbackptr/) | [System::Text::DecoderFallback](../system.text/decoderfallback/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncoderFallbackPtr](./encoderfallbackptr/) | [System::Text::EncoderFallback](../system.text/encoderfallback/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncoderPtr](./encoderptr/) | [System::Text::Encoder](../system.text/encoder/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [DecoderPtr](./decoderptr/) | [System::Text::Decoder](../system.text/decoder/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncodingPtr](./encodingptr/) | [System::Text::Encoding](../system.text/encoding/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [EncodingInfoPtr](./encodinginfoptr/) | [System::Text::EncodingInfo](../system.text/encodinginfo/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [StreamPtr](./streamptr/) | [System::IO::Stream](../system.io/stream/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [FileStreamPtr](./filestreamptr/) | [System::IO::FileStream](../system.io/filestream/) クラスのインスタンスを指すスマートポインタへのエイリアスです。 |
| [MemoryStreamPtr](./memorystreamptr/) | [System::IO::MemoryStream](../system.io/memorystream/) クラスのインスタンスへの共有ポインタです。 |
| [StreamReaderPtr](./streamreaderptr/) | [System::IO::StreamReader](../system.io/streamreader/) クラスのインスタンスへの共有ポインタです。 |
| [StreamWriterPtr](./streamwriterptr/) | [System::IO::StreamWriter](../system.io/streamwriter/) クラスのインスタンスへの共有ポインタです。 |
| [FileInfoPtr](./fileinfoptr/) | [System::IO::FileInfo](../system.io/fileinfo/) クラスのインスタンスへの共有ポインタです。 |
| [FileSystemInfoPtr](./filesysteminfoptr/) | [System::IO::FileSystemInfo](../system.io/filesysteminfo/) クラスのインスタンスへの共有ポインタです。 |
| [DirectoryInfoPtr](./directoryinfoptr/) | [System::IO::DirectoryInfo](../system.io/directoryinfo/) クラスのインスタンスへの共有ポインタです。 |
| [TaskPtr](./taskptr/) | [System::Threading::Tasks::Task](../system.threading.tasks/task/) クラスのインスタンスへの共有ポインタです。 |
| [RTaskPtr](./rtaskptr/) | [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) クラスのインスタンスへの共有ポインタです。 |
| [FunctionPtr](./functionptr/) | 既定の呼び出し規約を持つ関数型のエイリアスです。 |
| [Action](./action/) | 戻り値を持たないメソッドを参照するデリゲート型です。 |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | 符号なし 8 ビット整数の配列を指すスマートポインタオブジェクトのエイリアスです。 |
| [AsyncCallback](./asynccallback/) | 非同期操作が完了したときに呼び出されるメソッドを表すデリゲート型です。 |
| [BadImageFormatException](./badimageformatexception/) | 動的リンクライブラリ (DLL) または実行可能プログラムのファイルイメージが無効なときにスローされる例外です。BadImageFormatException クラスのインスタンスを [System::SmartPtr](./smartptr/) にラップしないでください。 |
| [Converter](./converter/) | **TInput** 型の単一引数を受け取り、**TOutput** 型の値を返す呼び出し可能エンティティへのポインタを表します。 |
| [Event](./event/) | イベントを表します。デリゲート呼び出しによって、購読者が関心のある出来事が通知される仕組みです。 |
| [EventArgsPtr](./eventargsptr/) | [EventArgs](./eventargs/) クラスのインスタンスへの共有ポインタです。 |
| [EventHandler](./eventhandler/) | イベントに反応し処理するメソッドを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。この型のオブジェクトを管理するために [System::SmartPtr](./smartptr/) クラスを使用しないでください。 |
| [ExceptionPtr](./exceptionptr/) | 例外ラッパーで使用される型エイリアスです。 |
| [Exception](./exception/) | Details::Exception の代わりに使用するエイリアスです。 |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | [IAsyncResult](./iasyncresult/) への共有ポインタ。 |
| [MakeConstRef_t](./makeconstref_t/) | [MakeConstRef](./makeconstref/) 修飾子のヘルパー型。 |
| [Predicate](./predicate/) | 述語へのポインタを表します - 単一の引数を受け取り、bool 値を返す呼び出し可能なエンティティです。 |
| [ArrayPtr](./arrayptr/) | 'pointer to array' 型のエイリアス。 |
| [SharedPtr](./sharedptr/) | ライブラリで広く使用されているスマートポインタのエイリアス。 |
| [StringComparerPtr](./stringcomparerptr/) | [StringComparer](./stringcomparer/) クラスのインスタンスへの共有ポインタのエイリアス。 |
| [TimeZonePtr](./timezoneptr/) | [TimeZone](./timezone/) クラスのインスタンスへの共有ポインタ。 |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | [TimeZoneInfo](./timezoneinfo/) クラスのインスタンスへの共有ポインタのエイリアス。 |