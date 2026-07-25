---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API リファレンス
description: "'Cache-Control' ヘッダーの値を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 14
url: /ja/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue クラス

‘Cache-Control’ ヘッダーの値を表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡すようにしてください。

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## メソッド

| Method | Description |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | 新しいインスタンスを構築します。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | キャッシュ拡張トークンのコレクションを返します。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | クライアントがレスポンスを受け入れる期間を決定する、秒単位の最大エイジ値を取得します。 |
| **bool** [get_MaxStale](./get_maxstale/)() | クライアントが期限切れのレスポンスを受け入れるかどうかを決定する値を取得します。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | クライアントが期限切れのレスポンスを受け入れる期間を秒で決定する値を取得します。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | 新鮮度の有効期間を決定する値を取得します。 |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | サーバーがキャッシュエントリが古くなったときに再検証を要求するかどうかを決定する値を取得します。 |
| **bool** [get_NoCache](./get_nocache/)() | クライアントがキャッシュされたレスポンスを受け入れるかどうかを決定する値を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | ‘Cache-Control’ ヘッダーの ‘no-cache’ ディレクティブに含まれるフィールド名のコレクションを取得します。 |
| **bool** [get_NoStore](./get_nostore/)() | キャッシュが HTTP リクエストまたはレスポンスのいずれの部分も保存してはならないかどうかを決定する値を取得します。 |
| **bool** [get_NoTransform](./get_notransform/)() | キャッシュまたはプロキシがエンティティ本体のいずれの部分も変更してはならないかどうかを決定する値を取得します。 |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | クライアントがキャッシュエントリのみを使用しなければならないかどうかを決定する値を取得します。 |
| **bool** [get_Private](./get_private/)() | HTTP レスポンスメッセージまたはその一部が単一ユーザー向けであり、共有キャッシュに保存すべきでないかどうかを決定する値を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | ‘Cache-Control’ ヘッダーの ‘private’ ディレクティブに含まれるフィールド名のコレクションを取得します。 |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | サーバーが共有ユーザーエージェントキャッシュに対して、キャッシュエントリが古くなったときに再検証を要求するかどうかを決定する値を取得します。 |
| **bool** [get_Public](./get_public/)() | HTTP レスポンスが任意のキャッシュに保存できるかどうかを決定する値を取得します。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | 共有キャッシュに対して、'Cache-Control' の 'max-age' ディレクティブまたは 'Expires' ヘッダーを上書きする、秒単位の共有最大エイジ値を取得します。 |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 指定されたインデックスから渡された文字列を [CacheControlHeaderValue](./) クラスのインスタンスに変換します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 渡された文字列を [CacheControlHeaderValue](./) クラスのインスタンスに変換します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | クライアントがレスポンスを受け入れる期間を決定する、秒単位の最大エイジ値を設定します。 |
| void [set_MaxStale](./set_maxstale/)(**bool**) | クライアントが期限切れのレスポンスを受け入れるかどうかを決定する値を設定します。 |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | クライアントが期限切れのレスポンスを受け入れる期間を秒で決定する値を設定します。 |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 新鮮度の有効期間を決定する値を設定します。 |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | サーバーがキャッシュエントリが古くなったときに再検証を要求するかどうかを決定する値を設定します。 |
| void [set_NoCache](./set_nocache/)(**bool**) | クライアントがキャッシュされたレスポンスを受け入れるかどうかを決定する値を設定します。 |
| void [set_NoStore](./set_nostore/)(**bool**) | キャッシュが HTTP リクエストまたはレスポンスのいずれの部分も保存してはならないかどうかを決定する値を設定します。 |
| void [set_NoTransform](./set_notransform/)(**bool**) | キャッシュまたはプロキシがエンティティ本体のいずれの部分も変更してはならないかどうかを決定する値を設定します。 |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | クライアントがキャッシュエントリのみを使用しなければならないかどうかを決定する値を設定します。 |
| void [set_Private](./set_private/)(**bool**) | HTTP レスポンスメッセージまたはその一部が単一ユーザー向けであり、共有キャッシュに保存すべきでないかどうかを決定する値を設定します。 |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | サーバーが共有ユーザーエージェントキャッシュに対して、キャッシュエントリが古くなったときに再検証を要求するかどうかを決定する値を設定します。 |
| void [set_Public](./set_public/)(**bool**) | HTTP レスポンスが任意のキャッシュに保存できるかどうかを決定する値を設定します。 |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 共有キャッシュに対して、'Cache-Control' の 'max-age' ディレクティブまたは 'Expires' ヘッダーを上書きする、秒単位の共有最大エイジ値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 渡された文字列を [CacheControlHeaderValue](./) クラスのインスタンスに変換しようとします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ICloneable](../../system/icloneable/)
* 名前空間 [System::Net::Http::Headers](../)
* ライブラリ [Aspose.Slides](../../)