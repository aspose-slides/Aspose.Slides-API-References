---
title: CookieContainer
second_title: Aspose.Slides for C++ API リファレンス
description: "CookieCollection クラスのインスタンスのコンテナを提供します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 40
url: /ja/system.net/cookiecontainer/
---
## CookieContainer クラス

CookieCollection クラスのインスタンスのコンテナを提供します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class CookieContainer : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | コレクションにクッキーを追加します。 |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>, **bool**) | コレクションにクッキーを追加します。 |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | 指定されたコレクションから現在のコレクションへクッキーをコピーします。 |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | 指定された URI に対してクッキーを追加します。 |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | 指定された URI 用の指定コレクションから現在のコレクションへクッキーをコピーします。 |
|  [CookieContainer](./cookiecontainer/)() | 新しいインスタンスを作成します。 |
|  [CookieContainer](./cookiecontainer/)(**int32_t**) | 新しいインスタンスを作成します。 |
|  [CookieContainer](./cookiecontainer/)(**int32_t**, **int32_t**, **int32_t**) | 新しいインスタンスを作成します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [CookieCutter](./cookiecutter/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), [String](../../system/string/), **bool**) | 指定された URI 用の指定 HTTP ヘッダーからクッキーをコピーします。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **int32_t** [get_Capacity](./get_capacity/)() | コレクションの容量を取得します。 |
| **int32_t** [get_Count](./get_count/)() | コレクションの項目数を返します。 |
| **int32_t** [get_MaxCookieSize](./get_maxcookiesize/)() | クッキーの最大サイズを取得します。 |
| **int32_t** [get_PerDomainCapacity](./get_perdomaincapacity/)() | ドメインあたりのコレクション容量を取得します。 |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 指定された URI に関連付けられたクッキーを含む HTTP ヘッダーを返します。 |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)\&) | 指定された URI に関連付けられたクッキーを含む HTTP ヘッダーを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [GetCookies](./getcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 指定された URI に関連付けられたクッキーのコレクションを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [InternalGetCookies](./internalgetcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 指定された URI に関連付けられたクッキーのコレクションを返します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| **bool** [IsLocalDomain](./islocaldomain/)([String](../../system/string/)) | 指定されたドメインがローカルホストかどうかを確認します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 参照比較で値型オブジェクトと nullptr を比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [set_Capacity](./set_capacity/)(**int32_t**) | コレクションの容量を設定します。 |
| void [set_MaxCookieSize](./set_maxcookiesize/)(**int32_t**) | クッキーの最大サイズを設定します。 |
| void [set_PerDomainCapacity](./set_perdomaincapacity/)(**int32_t**) | ドメインあたりのコレクション容量を設定します。 |
| void [SetCookies](./setcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) | 指定されたヘッダーからクッキーをコレクションにコピーし、指定された URI に関連付けます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | 最大クッキーサイズです。 |
| static [DefaultCookieLimit](./defaultcookielimit/) | コレクション項目の最大数です。 |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | ドメインあたりのコレクション項目の最大数です。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)