---
title: DocumentProperties
second_title: Aspose.Slides の C++ API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 794
url: /ja/aspose.slides/documentproperties/
---
## DocumentProperties クラス


プレゼンテーションのプロパティを表します。

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | すべての builtIn プロパティの値をクリアし、デフォルト値に設定します。 |
| void [ClearCustomProperties](./clearcustomproperties/)() override | すべてのカスタムプロパティを削除します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | 現在のオブジェクトをクローンします |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | 現在のオブジェクトをクローンします |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | 指定された名前のカスタムプロパティが存在するか確認します。 |
|  [DocumentProperties](./documentproperties/)() | [DocumentProperties](./) クラスの新しいインスタンスを初期化します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | アプリケーションのテンプレートを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | アプリのバージョンを返します。読み取り専用 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | プレゼンテーションの作者を返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | プレゼンテーションのカテゴリを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | プレゼンテーションのコメントを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | 会社プロパティを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | プレゼンテーションのコンテンツステータスを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | プレゼンテーションのコンテンツタイプを返します。読み取り [System::String](../../system/string/)。 |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | コレクションに実際に含まれるカスタムプロパティの数を返します。読み取り専用 **int32_t**。 |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | プレゼンテーションが作成された日付を返します。値は UTC です。読み取り [System::DateTime](../../system/datetime/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | ドキュメントパーツのグループ化と各グループのパーツ数を示します。読み取り専用 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)。 |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | プレゼンテーションドキュメント内の非表示スライド数を返します。読み取り専用 **int32_t**。 |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | HyperlinkBase ドキュメントプロパティを返します。読み取り [System::String](../../system/string/)。 |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | このパート内の 1 つ以上のハイパーリンクがプロデューサーによってこのパート内でのみ更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み取り **bool**。 |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | プレゼンテーションのキーワードを返します。読み取り [System::String](../../system/string/)。 |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | プレゼンテーションが最後に印刷された日付を返します。読み取り [System::DateTime](../../system/datetime/)。 |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | プレゼンテーションを最後に変更した人物の名前を返します。読み取り [System::String](../../system/string/)。 |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | プレゼンテーションが最後に変更された日付を返します。値は UTC です。[Presentation::get_DocumentProperties](../presentation/get_documentproperties/) の場合は読み取り専用です（[IPresentation](../ipresentation/) オブジェクトの保存プロセス中に内部で更新されるため）。[IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) メソッドが返す [DocumentProperties](./) インスタンスを介して変更可能です。例は [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) メソッド要約をご参照ください。 |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示し、**false** に設定するとハイパーリンクが古いことを示します。読み取り **bool**。 |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | マネージャープロパティを返します。読み取り [System::String](../../system/string/)。 |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | ドキュメントに存在するサウンドまたはビデオクリップの総数を返します。読み取り専用 **int32_t**。 |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | アプリケーションの名前を返します。読み取り [System::String](../../system/string/)。 |
| **int32_t** [get_Notes](./get_notes/)() override | ノートを含むプレゼンテーションのスライド数を返します。読み取り専用 **int32_t**。 |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | 該当する場合、ドキュメント内に見つかった段落の総数を返します。読み取り専用 **int32_t**。 |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | プレゼンテーションの意図された形式を返します。読み取り [System::String](../../system/string/)。 |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | プレゼンテーションのリビジョン番号を返します。読み取り **int32_t**。 |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルがディスプレイに合わせて拡大縮小され、**false** に設定するとディスプレイに合うセクションのみを表示するようにサムネイルが切り取られます。読み取り **bool**。 |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | プレゼンテーションが複数のユーザー間で共有されているかどうかを判断します。読み取り **bool**。 |
| **int32_t** [get_Slides](./get_slides/)() override | プレゼンテーションドキュメント内のスライド総数を返します。読み取り専用 **int32_t**。 |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | プレゼンテーションの件名を返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | プレゼンテーションのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | 各ドキュメントパートのタイトルを指定します。これらのパートは実際のドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 [System::ArrayPtr<System::String>](../../system/arrayptr/)。 |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | プレゼンテーションの総編集時間を返します。読み取り [System::TimeSpan](../../system/timespan/)。 |
| **int32_t** [get_Words](./get_words/)() override | ドキュメントに含まれる単語の総数を返します。読み取り専用 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | 指定されたインデックスのカスタムプロパティ名を返します。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | カスタムプロパティから名前付きブール値を取得します。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | カスタムプロパティから名前付き整数値を取得します。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | カスタムプロパティから名前付き DateTime 値を取得します。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | カスタムプロパティから名前付き文字列値を取得します。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | カスタムプロパティから名前付き float 値を取得します。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | カスタムプロパティから名前付き double 値を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | カスタムドキュメントプロパティから感度ラベルの配列を取得します (Microsoft Information Protection SDK メタデータ)。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | 指定された名前に関連付けられたカスタムプロパティを返します。読み取り [System::Object](../../system/object/)。 |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定された名前に関連付けられたカスタムプロパティを設定します。書き込み [System::Object](../../system/object/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | アプリケーションのテンプレートを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | プレゼンテーションの作者を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | プレゼンテーションのカテゴリを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | プレゼンテーションのコメントを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | 会社プロパティを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | プレゼンテーションのコンテンツステータスを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | プレゼンテーションのコンテンツタイプを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | プレゼンテーションが作成された日付を返します。値は UTC です。書き込み [System::DateTime](../../system/datetime/)。 |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | HyperlinkBase ドキュメントプロパティを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | このパート内の 1 つ以上のハイパーリンクがプロデューサーによってこのパート内でのみ更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。書き込み **bool**。 |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | プレゼンテーションのキーワードを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | プレゼンテーションが最後に印刷された日付を返します。書き込み [System::DateTime](../../system/datetime/)。 |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | プレゼンテーションを最後に変更した人物の名前を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | プレゼンテーションが最後に変更された日付を返します。値は UTC です。[Presentation::get_DocumentProperties](../presentation/get_documentproperties/) の場合は読み取り専用です（[IPresentation](../ipresentation/) オブジェクトの保存プロセス中に内部で更新されるため）。[IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) メソッドが返す [DocumentProperties](./) インスタンスを介して変更可能です。例は [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) メソッド要約をご参照ください。 |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されていることを示し、**false** に設定するとハイパーリンクが古いことを示します。書き込み **bool**。 |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | マネージャープロパティを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | アプリケーションの名前を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | プレゼンテーションの意図された形式を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | プレゼンテーションのリビジョン番号を設定します。書き込み **int32_t**。 |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルがディスプレイに合わせて拡大縮小され、**false** に設定するとディスプレイに合うセクションのみを表示するようにサムネイルが切り取られます。書き込み **bool**。 |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | プレゼンテーションが複数のユーザー間で共有されているかどうかを判断します。書き込み **bool**。 |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | プレゼンテーションの件名を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | プレゼンテーションのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | プレゼンテーションの総編集時間を設定します。書き込み [System::TimeSpan](../../system/timespan/)。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | 名前付きブール型カスタムプロパティを設定します。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | 名前付き整数型カスタムプロパティを設定します。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | 名前付き DateTime カスタムプロパティを設定します。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 名前付き文字列カスタムプロパティを設定します。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | 名前付き float カスタムプロパティを設定します。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | 名前付き double カスタムプロパティを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考


次の例は PowerPoint [Presentation](../presentation/) の組み込みプロパティへのアクセス方法を示します。

```cpp
// プレゼンテーションを表す Presentation クラスをインスタンス化します
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
 次の例は PowerPoint [Presentation](../presentation/) の組み込みプロパティを変更する方法を示します。

```cpp
// プレゼンテーションを表す Presentation クラスをインスタンス化します
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Set the builtin properties
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [IDocumentProperties](../idocumentproperties/)
* クラス [IGenericCloneable](../igenericcloneable/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)