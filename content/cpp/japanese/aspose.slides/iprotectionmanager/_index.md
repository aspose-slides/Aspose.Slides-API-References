---
title: IProtectionManager
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのパスワード保護管理。
type: docs
weight: 3459
url: /ja/aspose.slides/iprotectionmanager/
---
## IProtectionManager class

[Presentation](../presentation/) パスワード保護管理。

```cpp
class IProtectionManager : public virtual System::Object
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | プレゼンテーションが変更用にパスワードで保護されているかどうかを判定します。 |
| virtual void [Encrypt](./encrypt/)([System::String](../../system/string/)) | 指定されたパスワードで [Presentation](../presentation/) を暗号化します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) の意味論を使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみに使用されます。 |
| virtual **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションが暗号化されている間、ドキュメントプロパティは公開されます。読み取り **bool**。 |
| virtual [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() | 暗号化パスワードを返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | このインスタンスが暗号化されているかどうかを示す値を取得します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() | このプロパティは、プレゼンテーションファイルがパスワードで保護され、かつそのファイルのドキュメントプロパティが公開されている場合に意味があります。true の場合、パスワードを使用せずに暗号化されたプレゼンテーションファイルからドキュメントプロパティのみが読み込まれます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体が読み込まれ、ドキュメントプロパティだけでなく全体が読み込まれます。プレゼンテーションが暗号化されていない場合、プロパティの値は常に false です。暗号化されたファイルのドキュメントプロパティが公開されていない場合も、プロパティの値は常に false です。PresentationEx.EncryptDocumentProperties が true の場合、IsOnlyDocumentPropertiesLoaded プロパティの値は常に false です。読み取り専用 **bool**。 |
| virtual **bool** [get_IsWriteProtected](./get_iswriteprotected/)() | このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。読み取り専用 **bool**。 |
| virtual **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() | 読み取り専用の推奨設定を取得します。読み取り **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスを表すかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemoveEncryption](./removeencryption/)() | 暗号化を解除します。 |
| virtual void [RemoveWriteProtection](./removewriteprotection/)() | このプレゼンテーションの書き込み保護を解除します。 |
| virtual void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションが暗号化されている間、ドキュメントプロパティは公開されます。書き込み **bool**。 |
| virtual void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) | 読み取り専用の推奨設定を設定します。書き込み **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱いモードに切り替えることができます。 |
| virtual void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) | 指定されたパスワードでこのプレゼンテーションの書き込み保護を設定します。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)