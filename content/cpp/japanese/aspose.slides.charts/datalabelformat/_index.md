---
title: DataLabelFormat
second_title: Aspose.Slides for C++ API リファレンス
description: DataLabel の書式設定オプションを表します。
type: docs
weight: 391
url: /ja/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat クラス

[DataLabel](../datalabel/) の書式設定オプションを表します。

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | データラベルの書式を表します。読み取り専用 [IFormat](../iformat/)。 |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | **bool** を読み取ります。 |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | DataLabels オブジェクトの書式文字列を表します。[System::String](../../system/string/) を読み取ります。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../../aspose.slides/idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | データラベルの位置を表します。[LegendDataLabelPosition](../legenddatalabelposition/) を読み取ります。 |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | チャート上のデータラベルに使用される区切り文字を表す Variant を設定または返します。[System::String](../../system/string/) を読み取ります。 |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | 指定されたチャートのデータラベルのバブルサイズ値表示動作を表します。True の場合はバブルサイズ値を表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | 指定されたチャートのデータラベルのカテゴリ名表示動作を表します。True の場合はカテゴリ名を表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | 指定されたチャートのデータラベルがデータコールアウトとして表示されるか、データラベルとして表示されるかを決定します。 |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | 指定されたチャートのデータラベルのセル値表示動作を表します。True の場合はセル値を表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | 指定されたチャートのデータラベルのリーダーライン表示動作を表します。True の場合はリーダーラインを表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | 指定されたチャートのデータラベルの凡例キー表示動作を表します。True の場合、データラベルの凡例キーが表示されます。**bool** を読み取ります。 |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | チャート上のデータラベルのシリーズ名表示動作を示す Boolean を返します。True の場合はシリーズ名を表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| **bool** [get_ShowValue](./get_showvalue/)() override | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。**bool** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | チャートのテキスト書式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | **bool** を書き込みます。 |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | DataLabels オブジェクトの書式文字列を表します。[System::String](../../system/string/) を書き込みます。 |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | データラベルの位置を表します。[LegendDataLabelPosition](../legenddatalabelposition/) を書き込みます。 |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | チャート上のデータラベルに使用される区切り文字を表す Variant を設定または返します。[System::String](../../system/string/) を書き込みます。 |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | 指定されたチャートのデータラベルのバブルサイズ値表示動作を表します。True の場合はバブルサイズ値を表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | 指定されたチャートのデータラベルのカテゴリ名表示動作を表します。True の場合はカテゴリ名を表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | 指定されたチャートのデータラベルがデータコールアウトとして表示されるか、データラベルとして表示されるかを決定します。 |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | 指定されたチャートのデータラベルのセル値表示動作を表します。True の場合はセル値を表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | 指定されたチャートのデータラベルのリーダーライン表示動作を表します。True の場合はリーダーラインを表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | 指定されたチャートのデータラベルの凡例キー表示動作を表します。True の場合、データラベルの凡例キーが表示されます。**bool** を書き込みます。 |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | チャート上のデータラベルのシリーズ名表示動作を示す Boolean を設定します。True の場合はシリーズ名を表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。**bool** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 関連項目

* クラス [PVIObject](../../aspose.slides/pviobject/)
* クラス [IDataLabelFormat](../idatalabelformat/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)