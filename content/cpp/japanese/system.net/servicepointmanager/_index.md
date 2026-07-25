---
title: ServicePointManager
second_title: "Aspose.Slides for C++ API リファレンス"
description: "ServicePoint クラスのインスタンスのライフサイクル段階（作成、維持、削除）を管理します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。実行時エラーやアサーション違反が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 430
url: /ja/system.net/servicepointmanager/
---
## ServicePointManager クラス


Manages the lifecycle stages (creating, maintaining, and deleting) of the [ServicePoint](../servicepoint/) クラス instances. Objects of this クラス should only be allocated using [System::MakeObject()](../../system/makeobject/) 関数. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this クラス into [System::SmartPtr](../../system/smartptr/) ポインタ and use this ポインタ to pass it to functions as argument.

```cpp
class ServicePointManager : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部でのみ使用されます。 |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | 証明書ポリシーを取得します。 |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | 証明書が証明機関の失効リストに対してチェックされる必要があるかどうかを示す値を取得します。 |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | ServicePoint クラスインスタンスが許可される同時接続数の最大値を取得します。 |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | DNS 解決が有効と見なされるミリ秒単位のタイムアウトを取得します。 |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | DNS 解決が適用可能な IP アドレス間でローテートするかどうかを示す値を取得します。 |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | 現在のインスタンスで使用されている暗号化ポリシーを返します。 |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | ServicePoint クラスインスタンスが 100-Continue 動作を使用するかどうかを示す値を取得します。 |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | ServicePoint クラスインスタンスの最大アイドル時間を取得します。 |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | 現在のインスタンスが管理できる ServicePoint クラスインスタンスの最大数を取得します。 |
| static **bool** [get_ReusePort](./get_reuseport/)() | 出力接続ソケットが 'SO_REUSE_UNICASTPORT' オプションを使用するかどうかを示す値を取得します。 |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | 現在のインスタンスが管理する ServicePoint クラスインスタンスで使用されるセキュリティプロトコルタイプを取得します。 |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | サーバー証明書を検証するために使用されるコールバックを取得します。 |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | ServicePoint クラスインスタンスが Nagle アルゴリズムを使用するかどうかを示す値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 対象型で記述された型のインスタンスをオブジェクトが表すかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロック機構を実装します。直接呼び出すか [LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | 証明書ポリシーを設定します。 |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | 証明書が証明機関の失効リストに対してチェックされる必要があるかどうかを示す値を設定します。 |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | ServicePoint クラスインスタンスが許可される同時接続数の最大値を設定します。 |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | DNS 解決が有効と見なされるミリ秒単位のタイムアウトを設定します。 |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | DNS 解決が適用可能な IP アドレス間でローテートするかどうかを示す値を設定します。 |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | ServicePoint クラスインスタンスが 100-Continue 動作を使用するかどうかを示す値を設定します。 |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | ServicePoint クラスインスタンスの最大アイドル時間を設定します。 |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | 現在のインスタンスが管理できる ServicePoint クラスインスタンスの最大数を設定します。 |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | 出力接続ソケットが 'SO_REUSE_UNICASTPORT' オプションを使用するかどうかを示す値を設定します。 |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | 現在のインスタンスが管理する ServicePoint クラスインスタンスで使用されるセキュリティプロトコルタイプを設定します。 |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | サーバー証明書を検証するために使用されるコールバックを設定します。 |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | ServicePoint クラスインスタンスが Nagle アルゴリズムを使用するかどうかを示す値を設定します。 |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' オプションが有効かどうかを示す値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントして返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか [LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | デフォルトの非永続接続数。 |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | デフォルトの永続接続数。 |
## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)