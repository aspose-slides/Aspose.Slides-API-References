---
title: Legend
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの凡例プロパティを表します。
type: docs
weight: 1262
url: /ja/aspose.slides.charts/legend/
---
## Legend クラス

チャートの凡例プロパティを表します。

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用にのみ使用されます。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | チャート要素の実際の高さを指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。取得 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | チャート要素の実際の幅を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。取得 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | チャート要素の左上隅に対する実際の x 位置（左）を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。取得 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | チャート要素の左上隅に対する実際の上位置を指定します。実際の値を取得するには事前にメソッド [IChart::ValidateChartLayout](../ichart/validatechartlayout/) を呼び出してください。取得 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 下端。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | 凡例エントリを取得します。読み取り専用 [ILegendEntryCollection](../ilegendentrycollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | 指定されたインデックスのチャート内データポイントに対応する凡例エントリのプロパティを取得します。チャートタイプが bar-of-pie、exploded pie、exploded pie 3D、pie、pie 3D、pie-of-pie の場合、データポイントは最初の系列から取得されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 凡例の書式を返します。読み取り専用 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | 凡例の高さをチャートの高さの比率として返します。取得 **float**。 |
| **bool** [get_Overlay](./get_overlay/)() override | 他のチャート要素が凡例と重なることが許可されるかどうかを判定します。取得 **bool**。 |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | チャート上の凡例の位置を指定します。X、Y、幅、高さプロパティの非 NaN 値はこのプロパティの効果を上書きします。取得 [LegendPositionType](../legendpositiontype/)。 |
| **float** [get_Right](./get_right/)() override | 右端。読み取り専用 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | テキスト書式。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| **float** [get_Width](./get_width/)() override | 凡例の幅をチャートの幅の比率として返します。取得 **float**。 |
| **float** [get_X](./get_x/)() override | 凡例の x 座標をチャートの幅の比率として返します。取得 **float**。 |
| **float** [get_Y](./get_y/)() override | 凡例の y 座標をチャートの高さの比率として返します。取得 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの同等です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの同等です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の同等です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの同等です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合に対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Height](./set_height/)(**float**) override | 凡例の高さをチャートの高さの比率として設定します。書き込み **float**。 |
| void [set_Overlay](./set_overlay/)(**bool**) override | 他のチャート要素が凡例と重なることを許可するかどうかを設定します。書き込み **bool**。 |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | チャート上の凡例の位置を指定します。X、Y、幅、高さプロパティの非 NaN 値はこのプロパティの効果を上書きします。書き込み [LegendPositionType](../legendpositiontype/)。 |
| void [set_Width](./set_width/)(**float**) override | 凡例の幅をチャートの幅の比率として設定します。書き込み **float**。 |
| void [set_X](./set_x/)(**float**) override | 凡例の x 座標をチャートの幅の比率として設定します。書き込み **float**。 |
| void [set_Y](./set_y/)(**float**) override | 凡例の y 座標をチャートの高さの比率として設定します。書き込み **float**。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの同等です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [DomObject](../../aspose.slides/domobject/)
* クラス [ILegend](../ilegend/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)