---
title: Uri
second_title: Aspose.Slides for C++ API リファレンス
description: "統一リソース識別子。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡して使用してください。"
type: docs
weight: 1392
url: /ja/system/uri/
---
## Uri クラス

統一リソース識別子。このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数の引数として渡します。

```cpp
class Uri : public System::Object
```

## メソッド

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | 指定されたホスト名のタイプを決定します。 |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | 指定されたスキームが有効かどうかを判断します。 |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | 指定された比較規則を使用して、指定された [Uri](./) オブジェクトを比較します。 |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | 現在のオブジェクトと指定されたオブジェクトが表す URI が等しいかどうかを判定します。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 により NaN は任意の値（NaN を含む）と等しくないと規定されているにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 により NaN は任意の値（NaN を含む）と等しくないと規定されているにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | 文字列をエスケープ表現に変換します。 |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | URI 文字列をエスケープ表現に変換します。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部利用専用です。 |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | 16 進数の桁の十進数値を取得します。 |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | URI の絶対パスを返します。 |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | 絶対 URI を返します。 |
| [String](../string/) [get_Authority](./get_authority/)() const | サーバーのホスト名とポート番号を返します。 |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | エスケープされていないホスト名を返します。 |
| [String](../string/) [get_Fragment](./get_fragment/)() const | エスケープされた URI フラグメントを返します。 |
| [String](../string/) [get_Host](./get_host/)() const | ホスト名を返します。 |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | ホスト名のタイプを返します。 |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | ホストの国際化ドメイン名を返します。 |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | 現在のオブジェクトが表す URI が絶対かどうかを判断します。 |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | 現在のオブジェクトが表す URI がそのスキームのデフォルトポートを持つかどうかを判断します。 |
| **bool** [get_IsFile](./get_isfile/)() const | 現在のオブジェクトが表す URI がファイルかどうかを判断します。 |
| **bool** [get_IsLoopback](./get_isloopback/)() const | 現在のオブジェクトが表す URI がローカルホストを参照しているかどうかを判断します。 |
| **bool** [get_IsUnc](./get_isunc/)() const | 現在のオブジェクトが表す URI が UNC パスかどうかを判断します。 |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | 現在のオブジェクトが表す URI が参照するファイル名の OS 表現を返します。 |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | 現在のオブジェクトが構築されたときにコンストラクタに渡された URI 文字列を返します。 |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | 現在のオブジェクトが表す URI の絶対パスとクエリコンポーネントを、疑問符 (?) で区切って返します。 |
| **int32_t** [get_Port](./get_port/)() const | 現在のオブジェクトが表す URI のポート番号を返します。 |
| [String](../string/) [get_Query](./get_query/)() const | 現在のオブジェクトが表す URI に含まれるクエリ情報を返します。 |
| [String](../string/) [get_Scheme](./get_scheme/)() const | 現在のオブジェクトが表す URI のスキームを返します。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | 現在のオブジェクトが表す URI のパスセグメントを含む文字列配列を返します。 |
| **bool** [get_UserEscaped](./get_userescaped/)() const | 現在のオブジェクトのコンストラクタに渡された URI 文字列が完全にエスケープされているかどうかを判定します。 |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | ユーザー名、パスワード、および現在のオブジェクトが表す URI に関連付けられたその他のユーザー情報を返します。 |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | 指定されたエスケープ方式を使用して、現在のオブジェクトが表す URI の指定されたコンポーネントを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | URI のハッシュコードを取得します。 |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | 現在のオブジェクトが表す URI の指定された部分を返します。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../object/gettype/) 呼び出しのアナログです。 |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | 指定された文字の 16 進数表現を返します。 |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | 指定された文字の 16 進数表現を文字に変換します。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | 現在の [Uri](./) オブジェクトが表す URI が、指定された [Uri](./) オブジェクトが表す URI のベースかどうかを判定します。 |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | 指定された文字が有効な 16 進数の桁かどうかを判定します。 |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | 指定された位置にある、指定された文字列内の文字が 16 進数エンコードされているかどうかを判定します。 |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | この [Uri](./) の構築に使用された文字列が正しく形成されており、さらにエスケープする必要がないかどうかを示します。 |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | 指定された文字列が正しく形成された URI かどうかを判定します。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 2 つの [Uri](./) インスタンス間の差分を判定します。 |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 現在のオブジェクトと指定された [Uri](./) オブジェクトが表す URI 間の差分を判定します。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../string/) [ToString](./tostring/)() const override | 現在のオブジェクトが表す URI の文字列表現を返します。 |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 指定された URI を表す [Uri](./) オブジェクトを構築します。引数で URI の種別を指定します。 |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | ベース URI を表す指定された [Uri](./) オブジェクトと相対 URI の文字列表現から [Uri](./) オブジェクトを構築します。 |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 指定されたベース URI と相対 URI から [Uri](./) オブジェクトを構築します。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# の typeof([System.Object](../object/)) 構文を実装します。 |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | 指定されたエスケープ文字列のエスケープを解除します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
|  [Uri](./uri/)(const [String](../string/)\&) | 指定された URI を表す [Uri](./) オブジェクトを構築します。 |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | 指定された URI を表す [Uri](./) オブジェクトを構築します。引数で URI をエスケープするかどうかを指定します。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | ベース URI を表す指定された [Uri](./) オブジェクトと相対 URI の文字列表現から [Uri](./) オブジェクトを構築します。引数で URI をエスケープするかどうかを指定します。 |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | 指定された URI を表す [Uri](./) オブジェクトを構築します。引数で URI の種別を指定します。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | 指定されたベース URI と相対 URI から [Uri](./) オブジェクトを構築します。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 指定されたベース URI と相対 URI から [Uri](./) オブジェクトを構築します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## フィールド

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | [Uri](./) のアドレス部分と通信プロトコルスキームを区切る文字を指定します。 |
| static [UriSchemeFile](./urischemefile/) | [Uri](./) がファイルへのポインタであることを指定します。 |
| static [UriSchemeFtp](./urischemeftp/) | [Uri](./) がファイル転送プロトコルでアクセスされることを指定します。 |
| static [UriSchemeGopher](./urischemegopher/) | [Uri](./) が Gopher プロトコルでアクセスされることを指定します。 |
| static [UriSchemeHttp](./urischemehttp/) | [Uri](./) がハイパーテキスト転送プロトコルでアクセスされることを指定します。 |
| static [UriSchemeHttps](./urischemehttps/) | [Uri](./) がセキュアハイパーテキスト転送プロトコルでアクセスされることを指定します。 |
| static [UriSchemeMailto](./urischememailto/) | [Uri](./) がメールアドレスであり、シンプルメールトランスポートプロトコルでアクセスされることを指定します。 |
| static [UriSchemeNetPipe](./urischemenetpipe/) | [Uri](./) が [Windows](../../system.windows/) Communication Foundation が使用する NetPipe スキームでアクセスされることを指定します。 |
| static [UriSchemeNetTcp](./urischemenettcp/) | [Uri](./) が [Windows](../../system.windows/) Communication Foundation が使用する NetTcp スキームでアクセスされることを指定します。 |
| static [UriSchemeNews](./urischemenews/) | [Uri](./) がインターネットニュースグループであり、Network News Transport Protocol でアクセスされることを指定します。 |
| static [UriSchemeNntp](./urischemenntp/) | [Uri](./) がインターネットニュースグループであり、Network News Transport Protocol でアクセスされることを指定します。 |

## 備考

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
このコード例は以下の出力を生成します:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## 参考

* クラス [Object](../object/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)