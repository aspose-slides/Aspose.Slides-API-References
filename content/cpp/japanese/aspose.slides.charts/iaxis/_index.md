---
title: IAxis
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
weight: 534
url: /ja/aspose.slides.charts/iaxis/
---
## IAxis クラス

Encapsulates the object that represents a chart's axis.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | 軸の実際のメジャー単位を指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。 |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | 軸の実際のメジャー単位スケールを指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。 |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | 軸上の実際の最大値を指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。 |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | 軸の実際のマイナーユニットを指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。 |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | 軸の実際のマイナーユニットスケールを指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。 |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | 軸上の実際の最小値を指定します。実際の値を取得するには、事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。 |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | 値軸がカテゴリ間でカテゴリ軸を横切るかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3D チャートには適用されません。**bool** を読み取ります。 |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | 日付軸で表される最小の時間単位を指定します。[TimeUnitType](../timeunittype/) を読み取ります。 |
| virtual **double** [get_BinWidth](./get_binwidth/)() | AggregationType プロパティの値が [AxisAggregationType::ByBinWidth](../axisaggregationtype/) に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | カテゴリ軸のタイプを指定します。[CategoryAxisType](../categoryaxistype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual **float** [get_CrossAt](./get_crossat/)() | 垂直軸が交差する軸上の点を表します。**float** を読み取ります。 |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | 指定された軸上で他の軸が交差する CrossType を表します。[CrossesType](../crossestype/) を読み取ります。 |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | 値軸の表示単位のスケーリング値を指定します。[DisplayUnitType](../displayunittype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | 軸のフォーマットを表します。読み取り専用 [IAxisFormat](../iaxisformat/)。 |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | 軸に表示タイトルがあるかどうかを判定します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | 軸のメジャーユニットが自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | 最大値が自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | 軸のマイナーユニットが自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | 最小値が自動的に割り当てられるかどうかを示します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | 自動ティックラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | 自動ティックマーク間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。**bool** を読み取ります。 |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | 値軸のスケールタイプが対数かどうかを表します。**bool** を読み取ります。 |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | フォーマットがリンクされたソースデータかどうかを示します。**bool** を読み取ります。 |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。 |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。**bool** を読み取ります。 |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。 |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | 軸が表示されているかどうかを表します。**bool** を読み取ります。 |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | ラベルと軸との距離を指定します。カテゴリ軸または日付軸に適用され、値は 0% から 1000% の間でなければなりません。**uint16_t** を読み取ります。 |
| virtual **double** [get_LogBase](./get_logbase/)() | 対数の基数を表します。デフォルト値は 10 です。**double** を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | チャート軸上のメジャーグリッドラインのフォーマットを表します。読み取り専用 [IChartLinesFormat](../ichartlinesformat/)。 |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | 指定された軸のメジャーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を読み取ります。 |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | 日付または値軸のメジャーユニットを表します。**double** を読み取ります。 |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を読み取ります。 |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | 値軸上の最大値を表します。**double** を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | チャート軸上のマイナーグリッドラインのフォーマットを表します。読み取り専用 [IChartLinesFormat](../ichartlinesformat/)。 |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | 指定された軸のマイナーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を読み取ります。 |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | 日付または値軸のマイナーユニットを表します。**double** を読み取ります。 |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を読み取ります。 |
| virtual **double** [get_MinValue](./get_minvalue/)() | 値軸上の最小値を表します。**double** を読み取ります。 |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | [Axis](../axis/) ラベルのフォーマット文字列を表します。[System::String](../../system/string/) を読み取ります。 |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | AggregationType プロパティの値が [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true のときに適用されます。 |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | 軸の位置を表します。[AxisPositionType](../axispositiontype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | メジャーグリッドラインが表示されているかどうかを表します。読み取り専用 **bool**。 |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | マイナーグリッドラインが表示されているかどうかを表します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | チャートのテキストフォーマットを返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | 指定された軸上のティックマークラベルの位置を表します。[TickLabelPositionType](../ticklabelpositiontype/) を読み取ります。 |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | ティックラベルの回転角度を表します。**float** を読み取ります。 |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | 描画されるラベル間でスキップするティックラベルの数を指定します。**uint32_t** を読み取ります。 |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | 次のティックを描画する前にスキップするティックマークの数を指定します。カテゴリ軸またはシリーズ軸に適用され、**uint16_t** を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | 軸のタイトルを取得します。読み取り専用 [IChartTitle](../icharttitle/)。 |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true のときに適用されます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | 値軸がカテゴリ間でカテゴリ軸を横切るかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3D チャートには適用されません。**bool** を書き込みます。 |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | 日付軸で表される最小の時間単位を指定します。[TimeUnitType](../timeunittype/) を書き込みます。 |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | AggregationType プロパティの値が [AxisAggregationType::ByBinWidth](../axisaggregationtype/) に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | カテゴリ軸のタイプを指定します。[CategoryAxisType](../categoryaxistype/) を書き込みます。 |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | 垂直軸が交差する軸上の点を表します。**float** を書き込みます。 |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | 指定された軸上で他の軸が交差する CrossType を表します。[CrossesType](../crossestype/) を書き込みます。 |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | 値軸の表示単位のスケーリング値を指定します。[DisplayUnitType](../displayunittype/) を書き込みます。 |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | 軸に表示タイトルがあるかどうかを判定します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | 軸のメジャーユニットが自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | 最大値が自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | 軸のマイナーユニットが自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | 最小値が自動的に割り当てられるかどうかを示します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | 自動ティックラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | 自動ティックマーク間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。**bool** を書き込みます。 |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | 値軸のスケールタイプが対数かどうかを表します。**bool** を書き込みます。 |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | フォーマットがリンクされたソースデータかどうかを示します。**bool** を書き込みます。 |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。 |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。**bool** を書き込みます。 |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。 |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | 軸が表示されているかどうかを表します。**bool** を書き込みます。 |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | ラベルと軸との距離を指定します。カテゴリ軸または日付軸に適用され、値は 0% から 1000% の間でなければなりません。**uint16_t** を書き込みます。 |
| virtual void [set_LogBase](./set_logbase/)(**double**) | 対数の基数を表します。デフォルト値は 10 です。**double** を書き込みます。 |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | 指定された軸のメジャーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を書き込みます。 |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | 日付または値軸のメジャーユニットを表します。**double** を書き込みます。 |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を書き込みます。 |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | 値軸上の最大値を表します。**double** を書き込みます。 |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | 指定された軸のマイナーティックマークのタイプを表します。[TickMarkType](../tickmarktype/) を書き込みます。 |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | 日付または値軸のマイナーユニットを表します。**double** を書き込みます。 |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | 日付軸のメジャーユニットスケールを表します。[TimeUnitType](../timeunittype/) を書き込みます。 |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | 値軸上の最小値を表します。**double** を書き込みます。 |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | [Axis](../axis/) ラベルのフォーマット文字列を表します。[System::String](../../system/string/) を書き込みます。 |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | AggregationType プロパティの値が [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true のときに適用されます。 |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | 軸の位置を表します。[AxisPositionType](../axispositiontype/) を書き込みます。 |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | 指定された軸上のティックマークラベルの位置を表します。[TickLabelPositionType](../ticklabelpositiontype/) を書き込みます。 |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | ティックラベルの回転角度を表します。**float** を書き込みます。 |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | 描画されるラベル間でスキップするティックラベルの数を指定します。**uint32_t** を書き込みます。 |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | 次のティックを描画する前にスキップするティックマークの数を指定します。カテゴリ軸またはシリーズ軸に適用され、**uint16_t** を書き込みます。 |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true のときに適用されます。 |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | IAxis::get(set)_CategoryAxisType プロパティを、軸データに基づいて自動的に決定される値に設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IFormattedTextContainer](../iformattedtextcontainer/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)