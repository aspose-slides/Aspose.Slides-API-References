---
title: IDocumentProperties
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのプロパティを表します。
type: docs
weight: 1977
url: /ja/aspose.slides/idocumentproperties/
---
## IDocumentProperties クラス

プレゼンテーションのプロパティを表します。

```cpp
class IDocumentProperties : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | すべての builtIn プロパティのデフォルト値をクリアし、設定します。 |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | すべてのカスタムプロパティを削除します。 |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | 指定された名前のカスタムプロパティが存在するか確認します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | アプリケーションのテンプレートを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | アプリのバージョンを返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | プレゼンテーションの作成者を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | プレゼンテーションのカテゴリを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | プレゼンテーションのコメントを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | 会社プロパティを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | プレゼンテーションのコンテンツステータスを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | プレゼンテーションのコンテンツタイプを返します。読み取り [System::String](../../system/string/)。 |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | コレクションに実際に含まれるカスタムプロパティの数を返します。読み取り専用 **int32_t**。 |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | プレゼンテーションが作成された日時を返します。値は UTC です。読み取り [System::DateTime](../../system/datetime/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | ドキュメントパーツのグルーピングと各グループ内のパーツ数を示します。読み取り専用 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)。 |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | プレゼンテーション文書内の非表示スライド数を指定します。読み取り専用 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | HyperlinkBase ドキュメントプロパティを返します。読み取り [System::String](../../system/string/)。 |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | このパート内の 1 つ以上のハイパーリンクがプロデューサーによってこのパートだけで更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。読み取り **bool**。 |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | プレゼンテーションのキーワードを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | プレゼンテーションが最後に印刷された日時を返します。読み取り [System::DateTime](../../system/datetime/)。 |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | プレゼンテーションを最後に編集した人物の名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | プレゼンテーションが最後に変更された日時を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（[IPresentation](../ipresentation/) オブジェクトの保存プロセス中に内部で更新されるため）。[DocumentProperties](../documentproperties/) インスタンス（[IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) メソッドで取得）を介して変更可能です。詳細は [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) メソッド要約の例をご覧ください。 |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されたことを示し、**false** に設定するとハイパーリンクが古いことを示します。読み取り **bool**。 |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | マネージャープロパティを返します。読み取り [System::String](../../system/string/)。 |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | ドキュメントに存在する音声またはビデオクリップの総数を指定します。読み取り専用 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | アプリケーションの名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual **int32_t** [get_Notes](./get_notes/)() | ノートを含むプレゼンテーションのスライド数を指定します。読み取り専用 **int32_t**。 |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | 該当する場合、ドキュメント内に見つかった段落の総数を指定します。読み取り専用 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | プレゼンテーションの意図された形式を返します。読み取り [System::String](../../system/string/)。 |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | プレゼンテーションのリビジョン番号を返します。読み取り **int32_t**。 |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルをディスプレイに合わせて拡大縮小でき、**false** に設定すると表示に合わせてサムネイルをクロップして表示領域に収まるセクションのみを示します。読み取り **bool**。 |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | プレゼンテーションが複数のユーザー間で共有されているかどうかを判断します。読み取り **bool**。 |
| virtual **int32_t** [get_Slides](./get_slides/)() | プレゼンテーション文書内のスライド総数を指定します。読み取り専用 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | プレゼンテーションの件名を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | プレゼンテーションのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | 各ドキュメントパートのタイトルを指定します。これらのパートはドキュメントパートではなく、ドキュメントセクションの概念的表現です。読み取り専用 [System::ArrayPtr<System::String>](../../system/arrayptr/)。 |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | プレゼンテーションの総編集時間を返します。読み取り [System::TimeSpan](../../system/timespan/)。 |
| virtual **int32_t** [get_Words](./get_words/)() | ドキュメントに含まれる総単語数を指定します。読み取り専用 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | カスタムプロパティから名前付きブール値を取得します。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | カスタムプロパティから名前付き整数値を取得します。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | カスタムプロパティから名前付き DateTime 値を取得します。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | カスタムプロパティから名前付き文字列値を取得します。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | カスタムプロパティから名前付き float 値を取得します。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | カスタムプロパティから名前付き double 値を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | カスタムドキュメントプロパティから感度ラベルの配列を取得します（Microsoft Information Protection SDK メタデータ）。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | 指定された名前に関連付けられたカスタムプロパティを返します。読み取り [System::Object](../../system/object/)。 |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 指定された名前に関連付けられたカスタムプロパティを設定します。書き込み [System::Object](../../system/object/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | アプリケーションのテンプレートを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | プレゼンテーションの作成者を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | プレゼンテーションのカテゴリを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | プレゼンテーションのコメントを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | 会社プロパティを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | プレゼンテーションのコンテンツステータスを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | プレゼンテーションのコンテンツタイプを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | プレゼンテーションが作成された日時を返します。値は UTC です。書き込み [System::DateTime](../../system/datetime/)。 |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | HyperlinkBase ドキュメントプロパティを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | このパート内の 1 つ以上のハイパーリンクがプロデューサーによってこのパートだけで更新されたことを指定します。次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。書き込み **bool**。 |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | プレゼンテーションのキーワードを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | プレゼンテーションが最後に印刷された日時を返します。書き込み [System::DateTime](../../system/datetime/)。 |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | プレゼンテーションを最後に編集した人物の名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | プレゼンテーションが最後に変更された日時を返します。値は UTC です。Presentation.DocumentProperties の場合は読み取り専用です（[IPresentation](../ipresentation/) オブジェクトの保存プロセス中に内部で更新されるため）。[DocumentProperties](../documentproperties/) インスタンス（[IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) メソッドで取得）を介して変更可能です。詳細は [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) メソッド要約の例をご覧ください。 |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | ドキュメント内のハイパーリンクが最新かどうかを示します。この要素を **true** に設定するとハイパーリンクが更新されたことを示し、**false** に設定するとハイパーリンクが古いことを示します。書き込み **bool**。 |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | マネージャープロパティを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | アプリケーションの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | プレゼンテーションの意図された形式を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | プレゼンテーションのリビジョン番号を設定します。書き込み **int32_t**。 |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | ドキュメントサムネイルの表示モードを示します。この要素を **true** に設定するとサムネイルをディスプレイに合わせて拡大縮小でき、**false** に設定すると表示に合わせてサムネイルをクロップして表示領域に収まるセクションのみを示します。書き込み **bool**。 |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | プレゼンテーションが複数のユーザー間で共有されているかどうかを判断します。書き込み **bool**。 |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | プレゼンテーションの件名を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | プレゼンテーションのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | プレゼンテーションの総編集時間を設定します。書き込み [System::TimeSpan](../../system/timespan/)。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | 名前付きブール型カスタムプロパティを設定します。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | 名前付き整数型カスタムプロパティを設定します。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | 名前付き DateTime カスタムプロパティを設定します。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | 名前付き文字列カスタムプロパティを設定します。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | 名前付き float カスタムプロパティを設定します。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | 名前付き double カスタムプロパティを設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ポインタではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)