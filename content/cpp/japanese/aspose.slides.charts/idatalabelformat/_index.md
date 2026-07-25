---
title: IDataLabelFormat
second_title: Aspose.Slides for C++ API リファレンス
description: DataLabel の書式オプションを表します。
type: docs
weight: 963
url: /ja/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat クラス

[DataLabel](../datalabel/) の書式オプションを表します。

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用のみです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | データラベルの形式を表します。読み取り専用 [IFormat](../iformat/)。 |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 読み取り **bool**。 |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | DataLabels オブジェクトの書式文字列を表します。読み取り [System::String](../../system/string/)。 |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | データラベルの位置を表します。読み取り [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | チャート上のデータラベルに使用される区切り文字を表す Variant を設定または取得します。読み取り [System::String](../../system/string/)。 |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | 指定されたチャートのデータラベルのバブルサイズ値の表示動作を表します。True の場合はバブルサイズ値を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | 指定されたチャートのデータラベルのカテゴリ名の表示動作を表します。True の場合はカテゴリ名を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | 指定されたチャートのデータラベルがデータ呼び出しとして表示されるか、データラベルとして表示されるかを決定します。 |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | 指定されたチャートのデータラベルのセルの値の表示動作を表します。True の場合はセルの値を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | 指定されたチャートのデータラベルのリーダー線の表示動作を表します。True の場合はリーダー線を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | 指定されたチャートのデータラベルの凡例キーの表示動作を表します。True の場合は凡例キーが表示され、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | 指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | チャート上のデータラベルの系列名の表示動作を示す Boolean を返します。True の場合は系列名を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | 指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | チャートのテキスト書式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を有効にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を有効にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースの特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 書き込み **bool**。 |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | DataLabels オブジェクトの書式文字列を表します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | データラベルの位置を表します。書き込み [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | チャート上のデータラベルに使用される区切り文字を表す Variant を設定または取得します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | 指定されたチャートのデータラベルのバブルサイズ値の表示動作を表します。True の場合はバブルサイズ値を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | 指定されたチャートのデータラベルのカテゴリ名の表示動作を表します。True の場合はカテゴリ名を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | 指定されたチャートのデータラベルがデータ呼び出しとして表示されるか、データラベルとして表示されるかを決定します。 |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | 指定されたチャートのデータラベルのセルの値の表示動作を表します。True の場合はセルの値を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | 指定されたチャートのデータラベルのリーダー線の表示動作を表します。True の場合はリーダー線を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | 指定されたチャートのデータラベルの凡例キーの表示動作を表します。True の場合は凡例キーが表示され、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | 指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | チャート上のデータラベルの系列名の表示動作を示す Boolean を設定します。True の場合は系列名を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | 指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。True の場合はパーセンテージ値を表示し、False の場合は非表示にします。書き込み **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IFormattedTextContainer](../iformattedtextcontainer/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)