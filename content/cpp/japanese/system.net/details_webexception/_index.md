---
title: Details_WebException
second_title: Aspose.Slides for C++ API リファレンス
description: "エラーが発生したときに WebRequest によってスローされる例外を表します。このクラスのインスタンスは手動で作成しないでください。代わりに WebException クラスを使用してください。WebException クラスのインスタンスを System::SmartPtr にラップしないでください。"
type: docs
weight: 92
url: /ja/system.net/details_webexception/
---
## Details_WebException クラス

エラーが発生したときに [WebRequest](../webrequest/) がスローする例外を表します。 このクラスのインスタンスは手動で作成しないでください。 代わりに WebException クラスを使用してください。 WebException クラスのインスタンスを [System::SmartPtr](../../system/smartptr/) にラップしないでください。

```cpp
class Details_WebException : public System::Details_InvalidOperationException
```

## メソッド

| Method | Description |
| --- | --- |
| static [Exception](../../system/exception/) [CreateCompatibleException](./createcompatibleexception/)([Exception](../../system/exception/)) | 実装されていません。 |
|  [Details_WebException](./details_webexception/)() | 新しいインスタンスを構築します。 |
|  [Details_WebException](./details_webexception/)([String](../../system/string/)) | 新しいインスタンスを構築します。 |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/)) | 新しいインスタンスを構築します。 |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [WebExceptionStatus](../webexceptionstatus/)) | 新しいインスタンスを構築します。 |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/), [WebExceptionStatus](../webexceptionstatus/), [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\>) | 新しいインスタンスを構築します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | カスタム例外データを含む辞書を返します。 |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 現在のオブジェクトが表す例外に関連付けられた HRESULT コードである 32 ビット整数値を返します。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | 内部例外を表すオブジェクトへの参照を返します。 |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | エラーの説明を含む文字列を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [get_Response](./get_response/)() | 現在の例外に関連付けられた Web 応答を返します。 |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | スタックトレースを含む文字列を返します。 |
| [WebExceptionStatus](../webexceptionstatus/) [get_Status](./get_status/)() | ステータスコードを返します。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | 最も内部の例外を表す Exception オブジェクトのコピーを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | 特定の例外に割り当てられるコード化された数値である HRESULT を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | 現在のオブジェクトの文字列表現を返します。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual const char * [what](../../system/details_exception/what/)() const | [what()](../../system/details_exception/what/) メソッドを実装します。このメソッドは [ExceptionWrapper](../../system/exceptionwrapper/) クラスから呼び出されます。このクラスは std::exception から継承されていないにもかかわらず、派生クラスは protected/private メンバーを使用してロジックを実装できます。このメソッドの実装を [ExceptionWrapper](../../system/exceptionwrapper/) に移動すると、そのロジックが壊れる可能性があります。 |
| virtual  [~Details_WebException](./~details_webexception/)() | 現在のインスタンスを破棄します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)