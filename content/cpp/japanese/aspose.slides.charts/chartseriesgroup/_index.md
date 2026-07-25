---
title: ChartSeriesGroup
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズのグループを表します。
type: docs
weight: 300
url: /ja/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup クラス


シリーズのグループを表します。

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、2 つの NaN は等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、2 つの NaN は等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみです。 |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。[BubbleSizeRepresentationType](../bubblesizerepresentationtype/) を参照してください。 |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | バブルチャートのスケール ファクターを指定します（デフォルトサイズの 0〜300％の範囲）。**int32_t** を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 親チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | 指定されたインデックスのグループ内のチャートシリーズを返します。 |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | ドーナツ チャートの穴のサイズを指定します（プロット領域のサイズの 0〜90％の範囲）。**uint8_t** を参照してください。 |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 最初の円グラフまたはドーナツチャートのスライスの角度を取得します（上から時計回り、0〜360 度）。**uint16_t** を参照してください。 |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | 3D チャートでデータシリーズ間の距離を、マーカー幅のパーセンテージで返します。**uint16_t** を参照してください。 |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | 棒または列のクラスター間の間隔を、棒または列の幅のパーセンテージで指定します。**uint16_t** を参照してください。 |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | チャートにシリーズラインがある場合は true です。積み上げ棒グラフと OfPie チャートに適用されます。**bool** を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | HiLowLines の形式を指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャート タイプと共に使用されます。 |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | シリーズ内の各データ マーカーが異なる色を持つことを指定します。**bool** を参照してください。 |
| **int8_t** [get_Overlap](./get_overlap/)() override | 2-D チャートで棒および列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。 |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第2 の円または棒に属するかを決定する方法を指定します。[PieSplitType](../piesplittype/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。インデックスで指定された、pie-of-pie または bar-of-pie チャートの第2 の円または棒に描画されるデータポイントを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。pie-of-pie または bar-of-pie チャートの第2 の円または棒に描画されるデータポイントを含みます。読み取り専用 [PieSplitCustomPointCollection](../piesplitcustompointcollection/)。 |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第2 の円または棒に属するかを決定するために使用される値を指定します。PieSplitBy プロパティと共に使用されます。**double** を参照してください。 |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | このグループのシリーズがセカンダリ軸にプロットされているかどうかを示します。読み取り専用 **bool**。 |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | pie-of-pie または bar-of-pie チャートの第2 の円または棒のサイズを、最初の円のサイズのパーセンテージで指定します（5〜200％の範囲）。**uint16_t** を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | シリーズのコレクションを返します。読み取り専用 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)。 |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | このシリーズグループの型を返します。読み取り専用 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | ラインまたはストックチャートの上下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../iupdownbarsmanager/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | 指定されたインデックスの要素を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック処理を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリー オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピー コンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。[BubbleSizeRepresentationType](../bubblesizerepresentationtype/) に書き込みます。 |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | バブルチャートのスケール ファクターを指定します（デフォルトサイズの 0〜300％の範囲）。**int32_t** に書き込みます。 |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | ドーナツ チャートの穴のサイズを指定します（プロット領域のサイズの 0〜90％の範囲）。**uint8_t** に書き込みます。 |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | 最初の円グラフまたはドーナツチャートのスライスの角度を度数で設定します（上から時計回り、0〜360 度）。**uint16_t** に書き込みます。 |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | 3D チャートでデータシリーズ間の距離を、マーカー幅のパーセンテージで設定します。**uint16_t** に書き込みます。 |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | 棒または列のクラスター間の間隔を、棒または列の幅のパーセンテージで設定します。**uint16_t** に書き込みます。 |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | チャートにシリーズラインがある場合は true です。積み上げ棒グラフと OfPie チャートに適用されます。**bool** に書き込みます。 |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | シリーズ内の各データマーカーが異なる色を持つことを指定します。**bool** に書き込みます。 |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | 2-D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。 |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第2 の円または棒に属するかを決定する方法を指定します。[PieSplitType](../piesplittype/) に書き込みます。 |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第2 の円または棒に属するかを決定するために使用される値を指定します。PieSplitBy プロパティと共に使用されます。**double** に書き込みます。 |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | pie-of-pie または bar-of-pie チャートの第2 の円または棒のサイズを、最初の円のサイズのパーセンテージで指定します（5〜200％の範囲）。**uint16_t** に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | テンプレート引数 n 番目を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトの文字列変換を可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロック処理を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリー オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

1) ChartSeriesGroupCollection クラスおよび CombinableSeriesTypesGroup 列挙体の概要と備考を参照してください。 2) 系列のグループには、グループ内の各系列に共通するいくつかの系列プロパティ（"series group properties"）が含まれます。"Series group properties" は [ChartSeriesGroup](./) クラスで読み書き可能です。各 "series group properties" は [ChartSeries](../chartseries/) クラスで読み取り専用の投影を持つことができます。

## 参照

* クラス [IChartSeriesGroup](../ichartseriesgroup/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)