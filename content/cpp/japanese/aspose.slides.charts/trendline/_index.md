---
title: Trendline
second_title: Aspose.Slides for C++ API リファレンス
description: クラスはチャート系列のトレンドラインを表します
type: docs
weight: 1366
url: /ja/aspose.slides.charts/trendline/
---
## Trendline クラス

このクラスはチャート系列のトレンドラインを表します。

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | パラメータ \"text\" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding がすでに初期化されている場合は、単にそのテキストを変更します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| **double** [get_Backward](./get_backward/)() override | トレンドが適用される系列のデータの前に、トレンドラインが伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は任意の非負の値でなければなりません。読み取り **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 親チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | トレンドラインの方程式がチャートに表示されることを指定します（Rsquaredvalue と同じラベルに）。読み取り **bool**。 |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | トレンドラインの決定係数 (R-squared) がチャートに表示されることを指定します（方程式と同じラベルに）。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | トレンドラインの書式を表します。読み取り [IFormat](../iformat/)。 |
| **double** [get_Forward](./get_forward/)() override | トレンドが適用される系列のデータの後に、トレンドラインが伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は任意の非負の値でなければなりません。読み取り **double**。 |
| **double** [get_Intercept](./get_intercept/)() override | トレンドラインが y 軸と交差する位置の値を指定します。このプロパティはトレンドラインのタイプが exp、linear、または poly の場合にのみサポートされます。読み取り **double**。 |
| **uint8_t** [get_Order](./get_order/)() override | 多項式トレンドラインの次数を指定します。他のトレンドラインタイプでは無視されます。値は 2 から 6 の間でなければなりません。読み取り **uint8_t**。 |
| **uint8_t** [get_Period](./get_period/)() override | 移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間でなければなりません。読み取り **uint8_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | このトレンドラインに関連する凡例エントリを表します。読み取り専用 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | テキスト書式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | リッチ書式テキストを含めることができます。このプロパティが null でない場合、この書式テキスト値はデータラベルの自動生成テキストを上書きします。データラベルの自動生成テキストとは、ShowSeriesName、ShowValue などのプロパティで管理され、TextFormatManager.TextFormat プロパティで書式設定されたテキストを指します。読み取り専用 [ITextFrame](../../aspose.slides/itextframe/)。 |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | トレンドラインの名前を取得します。読み取り [System::String](../../system/string/)。 |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | トレンドラインのタイプを取得します。読み取り [Charts::TrendlineType](../trendlinetype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しに相当します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Backward](./set_backward/)(**double**) override | トレンドが適用される系列のデータの前に、トレンドラインが伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は任意の非負の値でなければなりません。書き込み **double**。 |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | トレンドラインの方程式がチャートに表示されることを指定します（Rsquaredvalue と同じラベルに）。書き込み **bool**。 |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | トレンドラインの決定係数 (R-squared) がチャートに表示されることを指定します（方程式と同じラベルに）。書き込み **bool**。 |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | トレンドラインの書式を表します。書き込み [IFormat](../iformat/)。 |
| void [set_Forward](./set_forward/)(**double**) override | トレンドが適用される系列のデータの後に、トレンドラインが伸びるカテゴリ数（または散布図の単位数）を指定します。散布図および非散布図では、値は任意の非負の値でなければなりません。書き込み **double**。 |
| void [set_Intercept](./set_intercept/)(**double**) override | トレンドラインが y 軸と交差する位置の値を指定します。このプロパティはトレンドラインのタイプが exp、linear、または poly の場合にのみサポートされます。書き込み **double**。 |
| void [set_Order](./set_order/)(**uint8_t**) override | 多項式トレンドラインの次数を指定します。他のトレンドラインタイプでは無視されます。値は 2 から 6 の間でなければなりません。書き込み **uint8_t**。 |
| void [set_Period](./set_period/)(**uint8_t**) override | 移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間でなければなりません。書き込み **uint8_t**。 |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | トレンドラインの名前を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | トレンドラインのタイプを設定します。書き込み [Charts::TrendlineType](../trendlinetype/)。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドに相当します。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [DomObject](../../aspose.slides/domobject/)
* クラス [ITrendline](../itrendline/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)