---
title: ILoadOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを読み込む際に、形式やデフォルトフォントなどの追加オプションを指定できます。
type: docs
weight: 2796
url: /ja/aspose.slides/iloadoptions/
---
## ILoadOptions クラス

プレゼンテーションを読み込む際に、形式やデフォルトフォントなどの追加オプションを指定できます。

```cpp
class ILoadOptions : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートし、IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートし、IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | 一時ファイルの使用やメモリ内の BLOB バイト数上限など、Binary Large Objects（BLOB）の取り扱い動作を管理するために使用できるオプションを表します。これらのオプションは、特定の環境や要件に対して最適なパフォーマンスとメモリ使用量のバランスを設定することを目的としています。 |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | ソースフォントが見つからない場合に使用されるアジアフォントを返します。[System::String](../../system/string/) を読み取ります。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | ソースフォントが見つからない場合に使用される標準フォントを返します。[System::String](../../system/string/) を読み取ります。 |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | ソースフォントが見つからない場合に使用されるシンボルフォントを返します。[System::String](../../system/string/) を読み取ります。 |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | プレゼンテーションテキストのデフォルト言語を返します。[System::String](../../system/string/) を読み取ります。 |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | [Aspose.Slides](../) がプレゼンテーションのロード中にすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | 割り込み要求を監視するトークンです。 |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | ロードするプレゼンテーションの形式を返します。[Slides::LoadFormat](../loadformat/) を読み取ります。 |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティの値が true の場合、ドキュメントプロパティをロードできず例外がスローされます。**bool** を読み取ります。 |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | パスワードを取得します。[System::String](../../system/string/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | 外部リソースのロードを管理するコールバックインターフェイスを返します。[IResourceLoadingCallback](../iresourceloadingcallback/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | 追加のスプレッドシートの動作を指定するために使用できるオプションを表します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを返します。[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | 一時ファイルの使用やメモリ内の BLOB バイト数上限など、Binary Large Objects（BLOB）の取り扱い動作を管理するために使用できるオプションを表します。これらのオプションは、特定の環境や要件に対して最適なパフォーマンスとメモリ使用量のバランスを設定することを目的としています。 |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | ソースフォントが見つからない場合に使用されるアジアフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | ソースフォントが見つからない場合に使用される標準フォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | ソースフォントが見つからない場合に使用されるシンボルフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | プレゼンテーションテキストのデフォルト言語を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | [Aspose.Slides](../) がプレゼンテーションのロード中にすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。 |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | 割り込み要求を監視するトークンです。 |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | ロードするプレゼンテーションの形式を設定します。[Slides::LoadFormat](../loadformat/) に書き込みます。 |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティの値が true の場合、ドキュメントプロパティをロードできず例外がスローされます。**bool** に書き込みます。 |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | パスワードを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | 外部リソースのロードを管理するコールバックインターフェイスを設定します。[IResourceLoadingCallback](../iresourceloadingcallback/) に書き込みます。 |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | 追加のスプレッドシートの動作を指定するために使用できるオプションを表します。 |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを設定します。[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)