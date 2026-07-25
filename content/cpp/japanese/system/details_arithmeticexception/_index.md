---
title: Details_ArithmeticException
second_title: Aspose.Slides for C++ API リファレンス
description: "ArithmeticException は、算術演算やキャスト変換の実行中にエラーが発生した場合にスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArithmeticException クラスを使用してください。ArithmeticException クラスのインスタンスを System::SmartPtr にラップしないでください。"
type: docs
weight: 365
url: /ja/system/details_arithmeticexception/
---
## Details_ArithmeticException クラス


ArithmeticException は、算術演算やキャスト変換の実行中にエラーが発生したときにスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArithmeticException クラスを使用してください。ArithmeticException クラスのインスタンスを [System::SmartPtr](../smartptr/) にラップしないでください。

```cpp
class Details_ArithmeticException : public System::Details_SystemException
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | カスタム例外データを含む辞書を返します。 |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 現在のオブジェクトが表す例外に関連付けられた HRESULT コードである 32 ビット整数値を返します。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | 内部例外を表すオブジェクトへの参照を返します。 |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | エラーの説明を含む文字列を返します。 |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | スタックトレースを含む文字列を返します。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | 最内層例外を表す Exception オブジェクトのコピーを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# の [Object.GetHashCode()](../object/gethashcode/) メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../object/gettype/) 呼び出しに相当します。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) 監視オブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | 特定の例外に割り当てられるコード化された数値である HRESULT を設定します。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | 現在のオブジェクトの文字列表現を返します。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) 監視オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) メソッドを実装します。このメソッドは [ExceptionWrapper](../exceptionwrapper/) クラスから呼び出されます。このクラスは std::exception から継承されていないにもかかわらず、派生クラスは保護/非公開メンバーを使用してロジックを実装できます。このメソッドの実装を [ExceptionWrapper](../exceptionwrapper/) に移動すると、そのロジックが壊れる可能性があります。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## See Also

* クラス [Details_SystemException](../details_systemexception/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)