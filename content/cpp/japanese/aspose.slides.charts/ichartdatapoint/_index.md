---
title: IChartDataPoint
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズ データ ポイントを表します。
type: docs
weight: 677
url: /ja/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint クラス


Represents series data point.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされる C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされる C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | チャート要素の実際の高さを指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | チャート要素の実際の幅を指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | チャート要素の左上隅からの実際の x 位置（左）を指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | チャート要素の左上隅からの実際の上位置を指定します。実際の値を取得するには事前に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | チャート データ ポイントのバブル サイズを返します。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | チャート データ ポイントのカラー値を返します。マップチャートで使用されます。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | 指定されたインデックスにあるデータ ポイント レベルを返します。Treeamp と Sunburst シリーズに適用されます。データ ポイント レベルのインデックスはゼロベースです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | データ ポイント レベルのコンテナを返します。Treeamp と Sunburst シリーズに適用されます。データ ポイント レベルのインデックスはゼロベースです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | カスタム値型の場合のシリーズ誤差バーの値を表します。読み取り専用 [IErrorBarsCustomValues](../ierrorbarscustomvalues/)。 |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | データ ポイントを円グラフの中心から移動させる量を指定します。読み取り **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 書式設定プロパティを表します。読み取り [IFormat](../iformat/)。 |
| virtual **uint32_t** [get_Index](./get_index/)() | このデータ ポイントが適用される親の子コレクションのどれかを決定します。読み取り **uint32_t**。 |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 値が負の場合、データ ポイントが色を反転させることを指定します。読み取り **bool**。 |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | バブルに 3D エフェクトが適用されることを指定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | チャート データ ポイントのラベルを表します。読み取り専用 [IDataLabel](../idatalabel/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | データ マーカーを指定します。読み取り専用 [IMarker](../imarker/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | このリストのチャートタイプの場合の対応する凡例エントリのプロパティ: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/)。読み取り専用 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | データ ポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | チャート データ ポイントのサイズ値を返します。Treemap と Sunburst チャートで使用されます。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | チャート データ ポイントの値を返します。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | チャート データ ポイントの X 値を返します。読み取り専用 [IStringOrDoubleChartValue](../istringordoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | チャート データ ポイントの Y 値を返します。読み取り専用 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | 系列インデックス、データ ポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、チャートスタイルに基づくデータ ポイントの自動カラーを返します。FillType が NotDefined の場合、このカラーがデフォルトで使用されます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの C# アナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。[System.Object.GetType()](../../system/object/gettype/) 呼び出しの C# アナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの C# アナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| virtual void [Remove](./remove/)() | チャート系列から DataPoint を削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | データ ポイントを円グラフの中心から移動させる量を指定します。書き込み **int32_t**。 |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | 書式設定プロパティを表します。書き込み [IFormat](../iformat/)。 |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 値が負の場合、データ ポイントが色を反転させることを指定します。書き込み **bool**。 |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | バブルに 3D エフェクトが適用されることを指定します。書き込み **bool**。 |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | データ ポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) メソッドの C# アナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [IActualLayout](../iactuallayout/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)