---
title: ServicePoint
second_title: Aspose.Slides for C++ API リファレンス
description: "HTTP 接続の管理を提供します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーションエラーが発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 417
url: /ja/system.net/servicepoint/
---
## ServicePoint クラス

HTTP 接続の管理を提供します。  
このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。  
スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーションエラーが発生します。  
常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
class ServicePoint : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | 指定された接続グループに属する接続を閉じて削除します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN は任意の値（NaN を含む）と等しくないと規定されていますが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN は任意の値（NaN を含む）と等しくないと規定されていますが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | 現在のインスタンスが接続するサーバー URI を返します。 |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | ローカル [IPEndPoint](../ipendpoint/) を現在のインスタンスに関連付けるために使用されるデリゲートを取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | 現在のインスタンスで使用される証明書を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | 最後のクライアント証明書を返します。 |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | アクティブな [ServicePoint](./) が閉じられるまでのタイムアウト（ミリ秒）を取得します。 |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | 現在のインスタンスで許可される最大接続数を取得します。 |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | 接続名を返します。 |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | 開かれた接続数を返します。 |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | 100-Continue 動作が使用されているかどうかを示す値を取得します。 |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | ホストへの最新接続の日時を返します。 |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | アイデル接続が閉じられるまでの時間（ミリ秒）を取得します。 |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | HTTP バージョンを返します。 |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | 受信バッファのサイズを取得します。 |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | 現在のインスタンスがパイプライン接続をサポートしているかどうかを示す値を返します。 |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | 現在のインスタンスが管理する接続で Nagle アルゴリズムが使用されているかどうかを示す値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | ローカル [IPEndPoint](../ipendpoint/) を現在のインスタンスに関連付けるために使用されるデリゲートを設定します。 |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | アクティブな [ServicePoint](./) が閉じられるまでのタイムアウト（ミリ秒）を設定します。 |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | 現在のインスタンスで許可される最大接続数を設定します。 |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | 100-Continue 動作が使用されているかどうかを示す値を設定します。 |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | アイデル接続が閉じられるまでの時間（ミリ秒）を設定します。 |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | 受信バッファのサイズを設定します。 |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | 現在のインスタンスが管理する接続で Nagle アルゴリズムが使用されているかどうかを示す値を設定します。 |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' オプションが有効かどうかを示す値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（shared ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)