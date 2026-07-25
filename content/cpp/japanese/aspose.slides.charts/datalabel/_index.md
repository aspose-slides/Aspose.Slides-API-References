---
title: DataLabel
second_title: Aspose.Slides for C++ API リファレンス
description: シリーズ ラベルを表します。
type: docs
weight: 365
url: /ja/aspose.slides.charts/datalabel/
---
## DataLabel クラス

シリーズ ラベルを表します。

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding が既に初期化されている場合は、テキストを単に変更します。 |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | [DataLabel](./) クラスの新しいインスタンスを作成します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 参照型オブジェクトを C# スタイルで比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 値型オブジェクトを C# スタイルで比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | チャート要素の実際の高さを指定します。実際の値を取得するには、先に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | チャート要素の実際の幅を指定します。実際の値を取得するには、先に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | チャート要素の左上隅に対する実際の x 位置（左）を指定します。実際の値を取得するには、先に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | チャート要素の左上隅に対する実際の上位置を指定します。実際の値を取得するには、先に [IChart::ValidateChartLayout](../ichart/validatechartlayout/) メソッドを呼び出してください。読み取り **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 下端。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 親チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | データラベル形式を返します。読み取り専用 [IDataLabelFormat](../idatalabelformat/)。 |
| **float** [get_Height](./get_height/)() override | タイトルの高さを、チャートの高さの比率で返します。読み取り **float**。 |
| **bool** [get_IsVisible](./get_isvisible/)() override | False はデータラベルが表示されないことを意味します（したがってすべての Show* フラグ (ShowValue, ...) は false になります）。読み取り専用 **bool**。 |
| **float** [get_Right](./get_right/)() override | 右端。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | テキスト形式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | リッチテキスト形式を含めることができます。このプロパティが null でない場合、フォーマットされたテキストはデータラベルの自動生成テキストを上書きします。データラベルの自動生成テキストとは、ShowSeriesName、ShowValue、... プロパティによって管理され、TextFormatManager.TextFormat プロパティでフォーマットされたテキストを指します。読み取り専用 [ITextFrame](../../aspose.slides/itextframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | ワークブックのデータセルを取得します。IDataLabelFormat::get(set)_ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| **float** [get_Width](./get_width/)() override | タイトルの幅を、チャートの幅の比率で返します。読み取り **float**。 |
| **float** [get_X](./get_x/)() override | タイトルの x 座標を、チャートの幅の比率で返します。読み取り **float**。 |
| **float** [get_Y](./get_y/)() override | タイトルの y 座標を、チャートの高さの比率で返します。読み取り **float**。 |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | [DataLabelFormat](../datalabelformat/) 設定または [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() の値に基づく実際のラベルテキストを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| void [Hide](./hide/)() override | すべての Show* フラグ (ShowValue, ...) を false に設定することでデータラベルを非表示にします。この後 IsVisible は false になります。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合に対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_Height](./set_height/)(**float**) override | タイトルの高さを、チャートの高さの比率で設定します。書き込み **float**。 |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | ワークブックのデータセルを設定します。IDataLabelFormat::get(set)_ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| void [set_Width](./set_width/)(**float**) override | タイトルの幅を、チャートの幅の比率で設定します。書き込み **float**。 |
| void [set_X](./set_x/)(**float**) override | タイトルの x 座標を、チャートの幅の比率で設定します。書き込み **float**。 |
| void [set_Y](./set_y/)(**float**) override | タイトルの y 座標を、チャートの高さの比率で設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th テンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) 監視オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [IDataLabel](../idatalabel/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)