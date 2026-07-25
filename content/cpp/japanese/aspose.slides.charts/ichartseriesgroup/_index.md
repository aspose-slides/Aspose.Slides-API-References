---
title: IChartSeriesGroup
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズのグループを表します。
type: docs
weight: 846
url: /ja/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup クラス

シリーズのグループを表します。

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | バブル チャート上でバブル サイズ値がどのように表されるかを指定します。[BubbleSizeRepresentationType](../bubblesizerepresentationtype/) を参照してください。 |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の間）。**int32_t** を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | 指定されたインデックスのグループ内のチャートシリーズを返します。 |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の間）。**uint8_t** を参照してください。 |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 最初の円グラフまたはドーナツチャートのスライスの角度を度単位で取得します（上から時計回り、0 から 360 度）。**uint16_t** を参照してください。 |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | 3D チャートのデータシリーズ間の距離をマーカー幅のパーセンテージで返します。**uint16_t** を参照してください。 |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | バーまたは列クラスター間のスペースをバーまたは列幅のパーセンテージで指定します。**uint16_t** を参照してください。 |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | チャートに系列ラインがある場合は true です。積み上げバーと OfPie チャートに適用されます。**bool** を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | HiLowLines の形式を指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、および VolumeOpenHiLowClose チャートタイプで適用されます。 |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | シリーズ内の各データマーカーが異なる色を持つことを指定します。**bool** を参照してください。 |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。 |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | pie-of-pie または bar-of-pie チャートで第2の円またはバーに含まれるデータポイントを判定する方法を指定します。[PieSplitType](../piesplittype/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | カスタム スプリットを持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。インデックスにより第2の円またはバーに描画されるデータポイントを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | カスタム スプリットを持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。第2の円またはバーに描画されるデータポイントを含みます。読み取り専用 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)。 |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | pie-of-pie または bar-of-pie チャートで第2の円またはバーに含まれるデータポイントを判定するために使用される値を指定します。PieSplitBy プロパティと併せて使用されます。**double** を参照してください。 |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | このグループの系列がセカンダリ軸にプロットされるかどうかを示します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | pie-of-pie または bar-of-pie チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の間）。**uint16_t** を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | チャートシリーズの読み取り専用コレクションを返します。読み取り専用 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | このシリーズグループの型を返します。読み取り専用 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | ラインまたはストックチャートの上/下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../iupdownbarsmanager/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | 指定されたインデックスの要素を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリー オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合に対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合に対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | バブル チャート上でバブル サイズ値がどのように表されるかを指定します。[BubbleSizeRepresentationType](../bubblesizerepresentationtype/) に書き込みます。 |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の間）。**int32_t** に書き込みます。 |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の間）。**uint8_t** に書き込みます。 |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | 最初の円またはドーナツチャートのスライスの角度を度単位で設定します（上から時計回り、0 から 360 度）。**uint16_t** に書き込みます。 |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | 3D チャートのデータシリーズ間の距離をマーカー幅のパーセンテージで設定します。**uint16_t** に書き込みます。 |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | バーまたは列クラスター間のスペースをバーまたは列幅のパーセンテージで指定します。**uint16_t** に書き込みます。 |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | チャートに系列ラインがある場合は true です。積み上げバーと OfPie チャートに適用されます。**bool** に書き込みます。 |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | シリーズ内の各データマーカーが異なる色を持つことを指定します。**bool** に書き込みます。 |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | 2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。 |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | pie-of-pie または bar-of-pie チャートで第2の円またはバーに含まれるデータポイントを判定する方法を指定します。[PieSplitType](../piesplittype/) に書き込みます。 |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | pie-of-pie または bar-of-pie チャートで第2の円またはバーに含まれるデータポイントを判定するために使用される値を指定します。PieSplitBy プロパティと併せて使用されます。**double** に書き込みます。 |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | pie-of-pie または bar-of-pie チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の間）。**uint16_t** に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウントの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、値を返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリー オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

1) ChartSeriesGroupCollection クラスおよび CombinableSeriesTypesGroup 列挙体の概要と備考をご覧ください。2) シリーズのグループには、グループ内の各シリーズに共通のいくつかのシリーズプロパティ（「series group properties」）が含まれます。[ChartSeriesGroup](../chartseriesgroup/) クラスの「Series group properties」は読み書き可能です。各「Series group properties」には、[ChartSeries](../chartseries/) クラスで読み取り専用のプロジェクションを持たせることができます。

## 参照

* クラス [IChartComponent](../ichartcomponent/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)