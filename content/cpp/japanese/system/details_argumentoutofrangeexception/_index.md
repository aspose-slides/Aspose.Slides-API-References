---
title: Details_ArgumentOutOfRangeException
second_title: Aspose.Slides for C++ API リファレンス
description: "ArgumentOutOfRangeException は、呼び出されたメソッドに渡された引数がその引数に対して期待される値の範囲外である場合にスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArgumentOutOfRangeException クラスを使用してください。ArgumentOutOfRangeException クラスのインスタンスを System::SmartPtr にラップしないでください。"
type: docs
weight: 352
url: /ja/system/details_argumentoutofrangeexception/
---
## Details_ArgumentOutOfRangeException クラス

ArgumentOutOfRangeException は、呼び出されたメソッドに対して渡された引数が期待される範囲外である場合にスローされます。このクラスのインスタンスを手動で作成しないでください。代わりに ArgumentOutOfRangeException クラスを使用してください。ArgumentOutOfRangeException クラスのインスタンスを [System::SmartPtr](../smartptr/) にラップしないでください。

```cpp
class Details_ArgumentOutOfRangeException : public System::Details_ArgumentException
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | カスタム例外データを含む辞書を返します。 |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 現在のオブジェクトが表す例外に関連付けられた HRESULT コードである 32 ビット整数値を返します。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | 内部例外を表すオブジェクトへの参照を返します。 |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | エラー説明を含む文字列を返します。 |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | スタックトレースを含む文字列を返します。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | 最も内部の例外を表す Exception オブジェクトのコピーを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../object/gettype/) 呼び出しのアナログです。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# の lock() ステートメントのロック処理を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | 特定の例外に割り当てられた数値コードである HRESULT を設定します。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントして返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | 現在のオブジェクトの文字列表現を返します。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) メソッドを実装します。このメソッドは [ExceptionWrapper](../exceptionwrapper/) クラスによって呼び出されます。std::exception から派生していないクラスでも protected/private メンバーを使用してロジックを実装できます。このメソッド実装を [ExceptionWrapper](../exceptionwrapper/) に移動するとロジックが壊れる可能性があります。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Details_ArgumentException](../details_argumentexception/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)