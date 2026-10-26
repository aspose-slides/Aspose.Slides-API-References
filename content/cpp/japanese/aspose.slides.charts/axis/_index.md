---
title: Axis
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
weight: 14
url: /ja/aspose.slides.charts/axis/
---
## Axis クラス


チャートの軸を表すオブジェクトをカプセル化します。

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | 軸の実際のメジャーユニットを指定します。実際の値を取得するには、事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。 |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | 軸の実際のメジャーユニットスケールを指定します。実際の値を取得するには、事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。 |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | 軸上の実際の最大値を指定します。実際の値を取得するには、事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。 |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | 軸の実際のマイナーユニットを指定します。実際の値を取得するには、事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。 |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | 軸の実際のマイナーユニットスケールを指定します。実際の値を取得するには、事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。 |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | 軸上の実際の最小値を指定します。実際の値を取得するには、事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。 |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | 値軸がカテゴリ間でカテゴリ軸を横切るかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。**bool** を読み取ります。 |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | 日付軸で表される最小の時間単位を指定します。[TimeUnitType](../timeunittype/) を読み取ります。 |
| **double** [get_BinWidth](./get_binwidth/)() override | AggregationType プロパティの値が [AxisAggregationType::ByBinWidth](../axisaggregationtype/) に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | カテゴリ軸のタイプを指定します。[Charts::CategoryAxisType](../categoryaxistype/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 親チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| **float** [get_CrossAt](./get_crossat/)() override | 軸上で垂直軸が交差する点を表します。**float** を読み取ります。 |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | 指定された軸上で他の軸が交差する CrossType を表します。[CrossesType](../crossestype/) を読み取ります。 |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | 値軸の表示単位のスケーリング値を指定します。[DisplayUnitType](../displayunittype/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | 軸の形式を表します。読み取り専用 [IAxisFormat](../iaxisformat/)。 |
| **bool** [get_HasTitle](./get_hastitle/)() override | 軸に表示可能なタイトルがあるかどうかを判定します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | 軸のメジャーユニットが自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | 最大値が自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | 軸のマイナーユニットが自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | 最小値が自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | 自動オーバーフロービン値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | 自動ティックラベル間隔値を指定します。false の場合は TickLabelSpacing プロパティを使用します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | 自動ティックマーク間隔値を指定します。false の場合は TickMarksSpacing プロパティを使用します。**bool** を読み取ります。 |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | 自動アンダーフロービン値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | 値軸のスケールタイプが対数かどうかを表します。**bool** を読み取ります。 |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | フォーマットがリンクされたソースデータかどうかを示します。**bool** を読み取ります。 |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービン値を調整します。 |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。**bool** を読み取ります。 |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービン値を調整します。 |
| **bool** [get_IsVisible](./get_isvisible/)() override | 軸が表示されているかどうかを表します。**bool** を読み取ります。 |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | 軸からラベルまでの距離を指定します。カテゴリ軸または日付軸に適用され、値は 0%〜1000% の間である必要があります。**uint16_t** を読み取ります。 |
| **double** [get_LogBase](./get_logbase/)() override | 対数の底を表します。デフォルト値は 10 です。**double** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | チャート軸上のメジャーグリッドラインの形式を表します。読み取り専用 [IChartLinesFormat](../ichartlinesformat/)。 |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | 指定された軸のメジャーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を読み取ります。 |
| **double** [get_MajorUnit](./get_majorunit/)() override | 日付軸または値軸のメジャーユニットを表します。**double** を読み取ります。 |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を読み取ります。 |
| **double** [get_MaxValue](./get_maxvalue/)() override | 値軸の最大値を表します。**double** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | チャート軸上のマイナーグリッドラインの形式を表します。読み取り専用 [IChartLinesFormat](../ichartlinesformat/)。 |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | 指定された軸のマイナーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を読み取ります。 |
| **double** [get_MinorUnit](./get_minorunit/)() override | 日付軸または値軸のマイナーユニットを表します。**double** を読み取ります。 |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を読み取ります。 |
| **double** [get_MinValue](./get_minvalue/)() override | 値軸の最小値を表します。**double** を読み取ります。 |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | [Axis](./) ラベルの書式文字列を表します。[System::String](../../system/string/) を読み取ります。 |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | AggregationType プロパティの値が [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| **double** [get_OverflowBin](./get_overflowbin/)() override | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true の場合に適用されます。 |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | 軸の位置を表します。[AxisPositionType](../axispositiontype/) を読み取ります。 |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | メジャーグリッドラインを非表示にするには、[get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() を [FillType::NoFill](../../aspose.slides/filltype/) に設定します。読み取り専用 **bool**。 |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | マイナーグリッドラインを非表示にするには、[get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() を [FillType::NoFill](../../aspose.slides/filltype/) に設定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | テキストの書式を表します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | 指定された軸上のティックマークラベルの位置を表します。[TickLabelPositionType](../ticklabelpositiontype/) を読み取ります。 |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | ティックラベルの回転角度を表します。**float** を読み取ります。 |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | 描画されるラベル間でスキップするティックラベルの数を指定します。カテゴリ軸またはシリーズ軸に適用され、**uint32_t** を読み取ります。 |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | 次のティックマークが描画されるまでにスキップすべきティックマークの数を指定します。カテゴリ軸またはシリーズ軸に適用され、**uint16_t** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | 軸のタイトルを取得します。読み取り専用 [IChartTitle](../icharttitle/)。 |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true の場合に適用されます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | 値軸がカテゴリ間でカテゴリ軸を横切るかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。**bool** を書き込みます。 |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | 日付軸で表される最小の時間単位を指定します。[TimeUnitType](../timeunittype/) を書き込みます。 |
| void [set_BinWidth](./set_binwidth/)(**double**) override | AggregationType プロパティの値が [AxisAggregationType::ByBinWidth](../axisaggregationtype/) に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | カテゴリ軸のタイプを指定します。[Charts::CategoryAxisType](../categoryaxistype/) を書き込みます。 |
| void [set_CrossAt](./set_crossat/)(**float**) override | 軸上で垂直軸が交差する点を表します。**float** を書き込みます。 |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | 指定された軸上で他の軸が交差する CrossType を表します。[CrossesType](../crossestype/) を書き込みます。 |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | 値軸の表示単位のスケーリング値を指定します。[DisplayUnitType](../displayunittype/) を書き込みます。 |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | 軸に表示可能なタイトルがあるかどうかを判定します。**bool** を書き込みます。 |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | 軸のメジャーユニットが自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | 最大値が自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | 軸のマイナーユニットが自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | 最小値が自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | 自動オーバーフロービン値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | 自動ティックラベル間隔値を指定します。false の場合は TickLabelSpacing プロパティを使用します。**bool** を書き込みます。 |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | 自動ティックマーク間隔値を指定します。false の場合は TickMarksSpacing プロパティを使用します。**bool** を書き込みます。 |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | 自動アンダーフロービン値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | 値軸のスケールタイプが対数かどうかを表します。**bool** を書き込みます。 |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | フォーマットがリンクされたソースデータかどうかを示します。**bool** を書き込みます。 |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービン値を調整します。 |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。**bool** を書き込みます。 |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービン値を調整します。 |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | 軸が表示されているかどうかを表します。**bool** を書き込みます。 |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | 軸からラベルまでの距離を指定します。カテゴリ軸または日付軸に適用され、値は 0%〜1000% の間である必要があります。**uint16_t** を書き込みます。 |
| void [set_LogBase](./set_logbase/)(**double**) override | 対数の底を表します。デフォルト値は 10 です。**double** を書き込みます。 |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | 指定された軸のメジャーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を書き込みます。 |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | 日付軸または値軸のメジャーユニットを表します。**double** を書き込みます。 |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を書き込みます。 |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | 値軸の最大値を表します。**double** を書き込みます。 |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | 指定された軸のマイナーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を書き込みます。 |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | 日付軸または値軸のマイナーユニットを表します。**double** を書き込みます。 |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を書き込みます。 |
| void [set_MinValue](./set_minvalue/)(**double**) override | 値軸の最小値を表します。**double** を書き込みます。 |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | [Axis](./) ラベルの書式文字列を表します。[System::String](../../system/string/) を書き込みます。 |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | AggregationType プロパティの値が [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true の場合に適用されます。 |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | 軸の位置を表します。[AxisPositionType](../axispositiontype/) を書き込みます。 |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | 指定された軸上のティックマークラベルの位置を表します。[TickLabelPositionType](../ticklabelpositiontype/) を書き込みます。 |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | ティックラベルの回転角度を表します。**float** を書き込みます。 |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | 描画されるラベル間でスキップするティックラベルの数を指定します。カテゴリ軸またはシリーズ軸に適用され、**uint32_t** を書き込みます。 |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | 次のティックマークが描画されるまでにスキップすべきティックマークの数を指定します。カテゴリ軸またはシリーズ軸に適用され、**uint16_t** を書き込みます。 |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true の場合に適用されます。 |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | IAxis::get(set)_CategoryAxisType プロパティを、軸データに基づいて自動的に決定される値で設定します。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | テンプレート引数 n 番目を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンターの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [DomObject](../../aspose.slides/domobject/)
* クラス [IAxis](../iaxis/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)