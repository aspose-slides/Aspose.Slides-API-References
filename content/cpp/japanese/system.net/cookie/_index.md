---
title: Cookie
second_title: Aspose.Slides for C++ API リファレンス
description: "HTTP クッキーを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。"
type: docs
weight: 1
url: /ja/system.net/cookie/
---
## Cookie クラス


HTTP クッキーを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class Cookie : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | 現在のインスタンスのコピーを作成します。 |
|  [Cookie](./cookie/)() | 新しいインスタンスを構築します。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | 新しいインスタンスを構築します。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 新しいインスタンスを構築します。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 新しいインスタンスを構築します。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 参照型オブジェクトを C# スタイルで比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | 'Comment' 属性の値を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | 'CommentURL' 属性の値を取得します。 |
| **bool** [get_Discard](./get_discard/)() const | 'Discard' 属性の値を取得します。 |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | 'Domain' 属性の値を取得します。 |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | ドメインが暗黙的かどうかを示す値を取得します。 |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | ドメインキーを返します。 |
| **bool** [get_Expired](./get_expired/)() | クッキーが期限切れかどうかを示す値を取得します。 |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | 'Expires' 属性の値を取得します。 |
| **bool** [get_HttpOnly](./get_httponly/)() const | 'HttpOnly' 属性の値を取得します。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | クッキーの名前を取得します。 |
| [String](../../system/string/) [get_Path](./get_path/)() const | 'Path' 属性の値を取得します。 |
| **bool** [get_Plain](./get_plain/)() const | クッキー仕様が 'Plain' かどうかを示す値を返します。 |
| [String](../../system/string/) [get_Port](./get_port/)() const | 'Port' 属性の値を取得します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | 'Port' 属性の値のコレクションを返します。 |
| **bool** [get_Secure](./get_secure/)() const | 'Secure' 属性の値を取得します。 |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | クッキーが作成された時刻を返します。 |
| [String](../../system/string/) [get_Value](./get_value/)() const | クッキーの値を取得します。 |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | クッキーの仕様を取得します。 |
| **int32_t** [get_Version](./get_version/)() const | '[Version](../../system/version/)' 属性の値を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | このメソッドは他のメソッドから呼び出され、メソッド名を設定します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | 'Comment' 属性の値を設定します。 |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 'CommentURL' 属性の値を設定します。 |
| void [set_Discard](./set_discard/)(**bool**) | 'Discard' 属性の値を設定します。 |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | 'Domain' 属性の値を設定します。 |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | ドメインが暗黙的かどうかを示す値を設定します。 |
| void [set_Expired](./set_expired/)(**bool**) | クッキーが期限切れかどうかを示す値を設定します。 |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | 'Expires' 属性の値を設定します。 |
| void [set_HttpOnly](./set_httponly/)(**bool**) | 'HttpOnly' 属性の値を設定します。 |
| void [set_Name](./set_name/)([String](../../system/string/)) | クッキーの名前を設定します。 |
| void [set_Path](./set_path/)([String](../../system/string/)) | 'Path' 属性の値を設定します。 |
| void [set_Port](./set_port/)([String](../../system/string/)) | 'Port' 属性の値を設定します。 |
| void [set_Secure](./set_secure/)(**bool**) | 'Secure' 属性の値を設定します。 |
| void [set_Value](./set_value/)([String](../../system/string/)) | クッキーの値を設定します。 |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | クッキーの仕様を設定します。 |
| void [set_Version](./set_version/)(**int32_t**) | '[Version](../../system/version/)' 属性の値を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ (共有ではなく) に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、値を返します。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | 現在のインスタンスを文字列表現にシリアライズします。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | デフォルト属性の値を検証し設定します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | 'Comment' 属性の名前です。 |
| static [CommentUrlAttributeName](./commenturlattributename/) | 'CommentURL' 属性の名前です。 |
| static [DiscardAttributeName](./discardattributename/) | 'Discard' 属性の名前です。 |
| static [DomainAttributeName](./domainattributename/) | 'Domain' 属性の名前です。 |
| static [EqualsLiteral](./equalsliteral/) | 属性の名前と値を区切るために使用されるセパレータです。 |
| static [ExpiresAttributeName](./expiresattributename/) | 'Expires' 属性の名前です。 |
| static [HttpOnlyAttributeName](./httponlyattributename/) | 'HttpOnly' 属性の名前です。 |
| static [MaxAgeAttributeName](./maxageattributename/) | 'Max-Age' 属性の名前です。 |
| static [MaxSupportedVersion](./maxsupportedversion/) | サポートされる最大バージョンです。 |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | サポートされる最大バージョンの文字列表現です。 |
| static [PathAttributeName](./pathattributename/) | 'Path' 属性の名前です。 |
| static [PortAttributeName](./portattributename/) | 'Port' 属性の名前です。 |
| static [PortSplitDelimiters](./portsplitdelimiters/) | 'Port' 属性の値のデリミタを含む配列です。 |
| static [QuotesLiteral](./quotesliteral/) | 属性の各部分を囲むために使用されるシンボルです。 |
| static [ReservedToName](./reservedtoname/) | クッキー名に予約されている値です。 |
| static [ReservedToValue](./reservedtovalue/) | クッキー値に予約されている値です。 |
| static [SecureAttributeName](./secureattributename/) | 'Secure' 属性の名前です。 |
| static [SeparatorLiteral](./separatorliteral/) | 属性セパレータです。 |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | 特別属性名のプレフィックスです。 |
| static [VersionAttributeName](./versionattributename/) | '[Version](../../system/version/)' 属性の名前です。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)