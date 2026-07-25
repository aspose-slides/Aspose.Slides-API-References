---
title: X509Certificate
second_title: Aspose.Slides for C++ API リファレンス
description: "X.509 v.3 証明書です。暗号化された証明書はサポートされていません。X509KeyStorageFlags::DefaultKeySet フラグのみがサポートされています。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 27
url: /ja/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate クラス

X.509 v.3 証明書です。暗号化された証明書はサポートされていません。[X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) フラグのみがサポートされています。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## メソッド

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | 指定されたPKCS7ファイルから証明書を作成します。 |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | 指定された署名付きファイルから証明書を作成します。 |
| void [Dispose](./dispose/)() override | 何もしません。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 2つの証明書を比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | 指定されたフォーマットを使用して現在のオブジェクトをバイト配列にエクスポートします。未実装です。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | 指定されたフォーマットを使用して現在のオブジェクトをバイト配列にエクスポートします。未実装です。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | 指定されたフォーマットを使用して現在のオブジェクトをバイト配列にエクスポートします。未実装です。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| IntPtr [get_Handle](./get_handle/)() const | Microsoft Cryptographic API 証明書コンテキストへのハンドルを取得します。 |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | X.509v3 証明書を発行した認証局の名前を取得します。 |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | 証明書からサブジェクトの識別名を取得します。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | 現在のオブジェクトのハッシュをバイト配列として取得します。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 現在のオブジェクトのハッシュをバイト配列として取得します。 |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | 現在のオブジェクトの [SHA1](../../system.security.cryptography/sha1/) ハッシュを16進文字列として取得します。 |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 現在のオブジェクトの [SHA1](../../system.security.cryptography/sha1/) ハッシュを16進文字列として取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | 現在の証明書の有効開始日を取得します。 |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | 現在の証明書の有効期限日を取得します。 |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | 証明書フォーマットの名前を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 証明書のハッシュコードを取得します。 |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | 現在の証明書を発行した認証局の名前を取得します。 |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | 現在の証明書の鍵情報を文字列として取得します。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | 現在の証明書の鍵情報をバイト配列として取得します。 |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | 現在の証明書の鍵情報を16進文字列として取得します。 |
| virtual [String](../../system/string/) [GetName](./getname/)() const | 現在の証明書が発行された主体の名前を取得します。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | 証明書から公開鍵をバイト配列として取得します。 |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | 証明書から公開鍵を16進文字列として取得します。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | 証明書から生データをバイト配列として取得します。 |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | 証明書から生データを16進文字列として取得します。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | 証明書からシリアル番号をバイト配列として取得します。 |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | 証明書からシリアル番号を16進文字列として取得します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しに相当します。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 指定された証明書ファイルから情報をインポートします。未実装です。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 指定された証明書ファイルから情報をインポートします。未実装です。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 指定された証明書データから情報をインポートします。未実装です。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 指定された証明書データから情報をインポートします。未実装です。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | 指定された証明書ファイルから情報をインポートします。未実装です。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 指定された証明書データから情報をインポートします。未実装です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [Reset](./reset/)() | 証明書の状態をリセットします。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、結果を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | 証明書情報をテキスト形式で返します。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 証明書情報をテキスト形式で返します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
| [X509Certificate](./x509certificate/)() | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | コンストラクタ。 |
| [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | コンストラクタ。 |
| virtual [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型エイリアス

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | ポインタ型です。 |

## 参照

* クラス [Object](../../system/object/)
* クラス [IDisposable](../../system/idisposable/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../)
* ライブラリ [Aspose.Slides](../../)