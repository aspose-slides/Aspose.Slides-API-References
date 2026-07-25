---
title: ChartDataPoint
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズ データポイントを表します。
type: docs
weight: 144
url: /ja/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint クラス


シリーズ データポイントを表します。

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
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
| **float** [get_ActualHeight](./get_actualheight/)() override | チャート要素の実際の高さを指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | チャート要素の実際の幅を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| **float** [get_ActualX](./get_actualx/)() override | チャート要素の左上隅に対する実際の x 位置（左）を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| **float** [get_ActualY](./get_actualy/)() override | チャート要素の左上隅に対する実際の上位置を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。**float** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | チャートデータポイントのカラー値を返します。Map チャートで使用されます。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | 指定されたインデックスのデータポイントレベルを返します。Treeamp および Sunburst 系列に適用されます。データポイントレベルのインデックスは 0 から始まります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | データポイントレベルのコンテナを返します。Treeamp および Sunburst 系列に適用されます。データポイントレベルのインデックスは 0 から始まります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | カスタム値型の場合のシリーズエラーバー値を表します。読み取り専用 [IErrorBarsCustomValues](../ierrorbarscustomvalues/)。 |
| **int32_t** [get_Explosion](./get_explosion/)() override | パイの中心からデータポイントを移動させる量を指定します。**int32_t** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 書式設定プロパティを表します。[IFormat](../iformat/) を読み取ります。 |
| **uint32_t** [get_Index](./get_index/)() override | このデータポイントが適用される親の子コレクションを決定します。**uint32_t** を読み取ります。 |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | 値が負の場合、データポイントの色を反転させることを指定します。**bool** を読み取ります。 |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | バブルに 3-D 効果が適用されていることを指定します。**bool** を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | Label。読み取り専用 [IDataLabel](../idatalabel/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | データマーカーを指定します。読み取り専用 [IMarker](../imarker/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | [ChartType::BarOfPie](../charttype/)、[ChartType::ExplodedPie](../charttype/)、[ChartType::ExplodedPie3D](../charttype/)、[ChartType::Pie](../charttype/)、[ChartType::Pie3D](../charttype/)、[ChartType::PieOfPie](../charttype/) のいずれかのチャートタイプの場合の対応する凡例エントリのプロパティです。読み取り専用 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | データポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | Treemap および Sunburst チャートで使用されるチャートデータポイントのサイズ値を返します。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | Value。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | XValue。読み取り専用 [IStringOrDoubleChartValue](../istringordoublechartvalue/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | YValue。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | シリーズインデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、チャートスタイルに基づくデータポイントの自動カラーを返します。FillType が NotDefined の場合、このカラーがデフォルトで使用されます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| void [Remove](./remove/)() override | チャート系列から DataPoint を削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | パイの中心からデータポイントを移動させる量を指定します。**int32_t** を書き込みます。 |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | 書式設定プロパティを表します。[IFormat](../iformat/) に書き込みます。 |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | 値が負の場合、データポイントの色を反転させることを指定します。**bool** を書き込みます。 |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | バブルに 3-D 効果が適用されていることを指定します。**bool** を書き込みます。 |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | データポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンターの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IChartDataPoint](../ichartdatapoint/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)