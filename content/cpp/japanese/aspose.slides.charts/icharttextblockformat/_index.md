---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API リファレンス
description: チャート テキスト要素の書式設定プロパティを表します。
type: docs
weight: 885
url: /ja/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat クラス

Represents formatting properties for chart text elements.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみで使用されます。 |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | [TextFrame](../../aspose.slides/textframe/) の垂直アンカーテキストを返します。参照 [TextAnchorType](../../aspose.slides/textanchortype/)。 |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | テキストの autofit モードを返します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。参照 [TextAutofitType](../../aspose.slides/textautofittype/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | [NullableBool::True](../../aspose.slides/nullablebool/) の場合、テキストはボックス内で水平に中央揃えになるべきです。参照 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../../aspose.slides/textframe/) の下余白（ポイント）を返します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。参照 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../../aspose.slides/textframe/) の左余白（ポイント）を返します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。参照 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../../aspose.slides/textframe/) の右余白（ポイント）を返します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。参照 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../../aspose.slides/textframe/) の上余白（ポイント）を返します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。参照 **double**。 |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、対応するシェイプの回転が使用されます。指定された場合、シェイプとは独立して適用されます。すなわち、シェイプに回転が適用されている場合でも、テキスト自体にも回転が適用されます。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。参照 **float**。 |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | テキストの向きを決定します。このプロパティとプロパティ RotationAngle のカスタム角度から要約された視覚的テキスト回転の結果値です。参照 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | [TextFrame](../../aspose.slides/textframe/) の余白でテキストが折り返されている場合は **True**。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2007/2013 で完全にサポート）。参照 [NullableBool](../../aspose.slides/nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケース用特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケース用特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | [TextFrame](../../aspose.slides/textframe/) の垂直アンカーテキストを設定します。設定 [TextAnchorType](../../aspose.slides/textanchortype/)。 |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | テキストの autofit モードを設定します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。設定 [TextAutofitType](../../aspose.slides/textautofittype/)。 |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | [NullableBool::True](../../aspose.slides/nullablebool/) の場合、テキストはボックス内で水平に中央揃えにすべきです。設定 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../../aspose.slides/textframe/) の下余白（ポイント）を設定します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。設定 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../../aspose.slides/textframe/) の左余白（ポイント）を設定します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。設定 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../../aspose.slides/textframe/) の右余白（ポイント）を設定します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。設定 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../../aspose.slides/textframe/) の上余白（ポイント）を設定します。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2013 で完全にサポート、PowerPoint 2007 ではレンダリングに影響なし）。設定 **double**。 |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、対応するシェイプの回転が使用されます。指定された場合、シェイプとは独立して適用されます。すなわち、シェイプに回転が適用されている場合でも、テキスト自体にも回転が適用されます。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。設定 **float**。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | テキストの向きを決定します。このプロパティとプロパティ RotationAngle のカスタム角度から要約された視覚的テキスト回転の結果値です。設定 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)。 |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | [TextFrame](../../aspose.slides/textframe/) の余白でテキストが折り返されている場合は **True**。このプロパティの変更は、次のチャート パーツにのみ特定の影響を与える可能性があります: [DataLabel](../datalabel/) と [DataLabelFormat](../datalabelformat/)（PowerPoint 2007/2013 で完全にサポート）。設定 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりに、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではありません。代わりに、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりに、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりに、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 関連項目

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)