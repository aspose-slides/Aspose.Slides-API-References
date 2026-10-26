---
title: IPAddress
second_title: Aspose.Slides for C++ API リファレンス
description: "IPアドレスを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 326
url: /ja/system.net/ipaddress/
---
## IPAddress クラス


IPアドレスを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class IPAddress : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN が等しいとみなされます（IEC 60559:1989 によれば NaN は任意の値、NaN を含む、に等しくない）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN が等しいとみなされます（IEC 60559:1989 によれば NaN は任意の値、NaN を含む、に等しくない）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | アドレスファミリを返します。 |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | アドレスが IPv4 であり IPv6 にマップされているかどうかを示す値を返します。 |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | アドレスが IPv6 のリンクローカルアドレスかどうかを示す値を返します。 |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | アドレスがグローバル IPv6 マルチキャストアドレスかどうかを示す値を返します。 |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | アドレスが IPv6 のサイトローカルアドレスかどうかを示す値を返します。 |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | アドレスが IPv6 Teredo アドレスかどうかを示す値を返します。 |
| **int64_t** [get_ScopeId](./get_scopeid/)() | IPv6 アドレスのスコープ識別子を取得します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | IP アドレスのバイト配列を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | 実装へのポインタを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | 指定されたホストバイトオーダーを対応するネットワークバイトオーダーに変換します。 |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | 指定されたホストバイトオーダーを対応するネットワークバイトオーダーに変換します。 |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | 指定されたホストバイトオーダーを対応するネットワークバイトオーダーに変換します。 |
| [IPAddress](./ipaddress/)(**int64_t**) | 新しいインスタンスを構築します。 |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | 新しいインスタンスを構築します。 |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 新しいインスタンスを構築します。 |
| [IPAddress](./ipaddress/)() | 新しいインスタンスを構築します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | 指定されたアドレスがループバックアドレスかどうかを示す値を返します。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | アドレスを IPv4 アドレスへマップします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | アドレスを IPv6 アドレスへマップします。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタムタイプのクローン作成を可能にします。 |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | 指定されたネットワークバイトオーダーを対応するホストバイトオーダーに変換します。 |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | 指定されたネットワークバイトオーダーを対応するホストバイトオーダーに変換します。 |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | 指定されたネットワークバイトオーダーを対応するホストバイトオーダーに変換します。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | 渡された文字列を [IPAddress](./) クラスのインスタンスに変換します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | IPv6 アドレスのスコープ識別子を設定します。 |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | 実装へのポインタを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタに設定します（共有ポインタではなく）。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することが可能です。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | 渡された文字列を [IPAddress](./) クラスのインスタンスに変換しようとします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Any](./any/) | サーバーがすべてのネットワークインターフェースをリッスンすべきかを示す IPv4 アドレスです。 |
| static [Broadcast](./broadcast/) | IPv4 のブロードキャストアドレスです。 |
| static [IPv6Any](./ipv6any/) | サーバーがすべてのネットワークインターフェースをリッスンすべきかを示す IPv6 アドレスです。 |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 のループバックアドレスです。 |
| static [IPv6None](./ipv6none/) | サーバーがいかなるネットワークインターフェースもリッスンすべきでないことを示す IPv6 アドレスです。 |
| static [Loopback](./loopback/) | IPv4 のループバックアドレスです。 |
| static [None](./none/) | サーバーがいかなるネットワークインターフェースもリッスンすべきでないことを示す IPv4 アドレスです。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [ImplPtr](./implptr/) | 実装型へのポインタです。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)