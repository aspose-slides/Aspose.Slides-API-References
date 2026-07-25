---
title: ProtectionManager
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのパスワード保護管理。
type: docs
weight: 4915
url: /ja/aspose.slides/protectionmanager/
---
## ProtectionManager クラス

[Presentation](../presentation/) パスワード保護管理。

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | プレゼンテーションが変更用にパスワードで保護されているかどうかを判定します。 |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | [Presentation](../presentation/) を指定されたパスワードで暗号化します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートし、 IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートし、 IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用専用です。 |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションは暗号化されますがドキュメントプロパティは公開されます。読み取り **bool**。 |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | プレゼンテーション暗号化に使用されるパスワードを取得します。読み取り専用 [System::String](../../system/string/)。 |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | このインスタンスが暗号化されているかどうかを示す値を取得します。読み取り専用 **bool**。 |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | このプロパティは、プレゼンテーションファイルがパスワードで保護され、かつこのファイルのドキュメントプロパティが公開されている場合に意味があります。true の場合、パスワードを使用せずに暗号化されたプレゼンテーションファイルからドキュメントプロパティのみがロードされます。false の場合、正しいパスワードを使用して全体の暗号化されたプレゼンテーションがロードされ、ドキュメントプロパティだけでなく全体がロードされます。プレゼンテーションが暗号化されていない場合、プロパティ値は常に false です。暗号化されたファイルのドキュメントプロパティが公開されていない場合も、プロパティ値は常に false です。Presentation.EncryptDocumentProperties が true の場合、IsOnlyDocumentPropertiesLoaded プロパティ値は常に false です。読み取り専用 **bool**。 |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。読み取り専用 **bool**。 |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | 読み取り専用の推奨設定を取得します。読み取り **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合に対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemoveEncryption](./removeencryption/)() override | 暗号化を解除します。 |
| void [RemoveWriteProtection](./removewriteprotection/)() override | このプレゼンテーションの書き込み保護を解除します。 |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションは暗号化されますがドキュメントプロパティは公開されます。書き込み **bool**。 |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | 読み取り専用の推奨設定を設定します。書き込み **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | 指定されたパスワードでこのプレゼンテーションの書き込み保護を設定します。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IProtectionManager](../iprotectionmanager/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)