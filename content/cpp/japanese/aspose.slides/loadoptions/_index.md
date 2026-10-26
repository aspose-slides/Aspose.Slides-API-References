---
title: LoadOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションの読み込み時に、形式やデフォルトフォントなどの追加オプションを指定できます。
type: docs
weight: 4395
url: /ja/aspose.slides/loadoptions/
---
## LoadOptions クラス

プレゼンテーションの読み込み時に、追加オプション（形式やデフォルトフォントなど）を指定できます。

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | 一時ファイルの使用やメモリ内の BLOB バイト数の上限など、Binary Large Objects (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。これらのオプションは、特定の環境や要件に対して最適なパフォーマンス／メモリ使用率の比率を設定することを目的としています。 |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | 元のフォントが見つからない場合に使用されるアジアフォントを返します。[System::String](../../system/string/) を参照してください。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | 元のフォントが見つからない場合に使用されるレギュラーフォントを返します。[System::String](../../system/string/) を参照してください。 |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | 元のフォントが見つからない場合に使用されるシンボルフォントを返します。[System::String](../../system/string/) を参照してください。 |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | プレゼンテーションテキストのデフォルト言語を返します。[System::String](../../system/string/) を参照してください。 |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | [Aspose.Slides](../) がプレゼンテーションの読み込み中にすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用でき、他のプレゼンテーションと共有されません。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | 中断要求を監視するためのトークンです。 |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | 読み込むプレゼンテーションの形式を返します。[Slides::LoadFormat](../loadformat/) を参照してください。 |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。true の場合、暗号化されたプレゼンテーションファイルからはドキュメントプロパティのみがロードされ、パスワードは無視されます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体がロードされます。プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。暗号化ファイルのドキュメントプロパティが非公開で、プロパティが true の場合、ドキュメントプロパティはロードできず例外がスローされます。**bool** を参照してください。 |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | パスワードを取得します。[System::String](../../system/string/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | 外部リソースのロードを管理するコールバックインターフェイスを返します。[IResourceLoadingCallback](../iresourceloadingcallback/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | スプレッドシート用のオプションを取得します。例えば、これらのオプションはチャートの数式計算に影響します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | 警告を受け取り、ロード処理を続行するか中止するかを決定するオブジェクトを返します。[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を参照してください。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| [LoadOptions](./loadoptions/)() | 新しいデフォルトのロードオプションを作成します。 |
| [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | 新しいロードオプションを作成します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | 一時ファイルの使用やメモリ内の BLOB バイト数の上限など、Binary Large Objects (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。これらのオプションは、特定の環境や要件に対して最適なパフォーマンス／メモリ使用率の比率を設定することを目的としています。 |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | 元のフォントが見つからない場合に使用されるアジアフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | 元のフォントが見つからない場合に使用されるレギュラーフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | 元のフォントが見つからない場合に使用されるシンボルフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | プレゼンテーションテキストのデフォルト言語を設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | [Aspose.Slides](../) がプレゼンテーションの読み込み中にすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。 |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用でき、他のプレゼンテーションと共有されません。 |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | 中断要求を監視するためのトークンです。 |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | 読み込むプレゼンテーションの形式を設定します。[Slides::LoadFormat](../loadformat/) に書き込みます。 |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。true の場合、暗号化されたプレゼンテーションファイルからはドキュメントプロパティのみがロードされ、パスワードは無視されます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体がロードされます。プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。暗号化ファイルのドキュメントプロパティが非公開で、プロパティが true の場合、ドキュメントプロパティはロードできず例外がスローされます。**bool** に書き込みます。 |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | パスワードを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | 外部リソースのロードを管理するコールバックインターフェイスを設定します。[IResourceLoadingCallback](../iresourceloadingcallback/) に書き込みます。 |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | スプレッドシート用のオプションを取得します。例えば、これらのオプションはチャートの数式計算に影響します。 |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、ロード処理を続行するか中止するかを決定するオブジェクトを設定します。[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ILoadOptions](../iloadoptions/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)