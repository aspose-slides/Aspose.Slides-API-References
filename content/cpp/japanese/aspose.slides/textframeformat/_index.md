---
title: TextFrameFormat
second_title: Aspose.Slides for C++ APIリファレンス
description: TextFrame の formatTextFrameFormatting プロパティを含みます。
type: docs
weight: 5461
url: /ja/aspose.slides/textframeformat/
---
## TextFrameFormat クラス

[TextFrame](../textframe/) の formatTextFrameFormatting プロパティを含みます。

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## メソッド

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみに使用されます。 |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | [TextFrame](../textframe/) の垂直アンカーテキストを返します。取得 [TextAnchorType](../textanchortype/)。 |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | テキストの自動フィットモードを返します。取得 [TextAutofitType](../textautofittype/)。 |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | [NullableBool::True](../nullablebool/) の場合、テキストは水平方向にボックスの中央に配置されるべきです。取得 [NullableBool](../nullablebool/)。 |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | テキスト領域の列数を返します。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。0 は未定義の値を意味します。取得 **int32_t**。 |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | テキスト領域の列間の間隔（ポイント単位）を返します。1 列以上が存在する場合にのみ適用されます。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。取得 **double**。 |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | 3-D 回転効果が適用されてもテキストを平坦に保つかどうかを取得します。取得 **bool**。 |
| **double** [get_MarginBottom](./get_marginbottom/)() override | [TextFrame](../textframe/) の下余白（ポイント）を返します。取得 **double**。 |
| **double** [get_MarginLeft](./get_marginleft/)() override | [TextFrame](../textframe/) の左余白（ポイント）を返します。取得 **double**。 |
| **double** [get_MarginRight](./get_marginright/)() override | [TextFrame](../textframe/) の右余白（ポイント）を返します。取得 **double**。 |
| **double** [get_MarginTop](./get_margintop/)() override | [TextFrame](../textframe/) の上余白（ポイント）を返します。取得 **double**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| **float** [get_RotationAngle](./get_rotationangle/)() override | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されていても、テキスト自体にも回転が適用されます。このプロパティと TextVerticalType プロパティの事前定義された垂直タイプから要約された、視覚的テキスト回転の結果値を取得します。取得 **float**。 |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | テキストの向きを決定します。このプロパティと RotationAngle プロパティのカスタム角度から要約された視覚的テキスト回転の結果値を取得します。取得 [Slides::TextVerticalType](../textverticaltype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | [ThreeDFormat](../threedformat/) オブジェクト（テキストの 3D 効果プロパティを表す）を返します。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | テキストラッピングシェイプを取得します。取得 [TextShapeType](../textshapetype/)。 |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | [TextFrame](../textframe/) の余白でテキストがラップされている場合は **True**。取得 [NullableBool](../nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された実効テキストフレーム書式設定データを取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | [TextFrame](../textframe/) の垂直アンカーテキストを設定します。設定 [TextAnchorType](../textanchortype/)。 |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | テキストの自動フィットモードを設定します。設定 [TextAutofitType](../textautofittype/)。 |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | [NullableBool::True](../nullablebool/) の場合、テキストは水平方向にボックスの中央に配置されるべきです。設定 [NullableBool](../nullablebool/)。 |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | テキスト領域の列数を設定します。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。0 は未定義の値を意味します。設定 **int32_t**。 |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | テキスト領域の列間の間隔（ポイント単位）を設定します。1 列以上が存在する場合にのみ適用されます。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。設定 **double**。 |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | 3-D 回転効果が適用されてもテキストを平坦に保つかどうかを設定します。設定 **bool**。 |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | [TextFrame](../textframe/) の下余白（ポイント）を設定します。設定 **double**。 |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | [TextFrame](../textframe/) の左余白（ポイント）を設定します。設定 **double**。 |
| void [set_MarginRight](./set_marginright/)(**double**) override | [TextFrame](../textframe/) の右余白（ポイント）を設定します。設定 **double**。 |
| void [set_MarginTop](./set_margintop/)(**double**) override | [TextFrame](../textframe/) の上余白（ポイント）を設定します。設定 **double**。 |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | バウンディングボックス内のテキストに適用されるカスタム回転を設定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されていても、テキスト自体にも回転が適用されます。このプロパティと TextVerticalType プロパティの事前定義された垂直タイプから要約された、視覚的テキスト回転の結果値を取得します。設定 **float**。 |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | テキストの向きを決定します。このプロパティと RotationAngle プロパティのカスタム角度から要約された視覚的テキスト回転の結果値を取得します。設定 [Slides::TextVerticalType](../textverticaltype/)。 |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | テキストラッピングシェイプを設定します。設定 [TextShapeType](../textshapetype/)。 |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | [TextFrame](../textframe/) の余白でテキストがラップされている場合は **True**。設定 [NullableBool](../nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [TextFrameFormat](./textframeformat/)() | [TextFrameFormat](./) クラスの新しいインスタンスを初期化します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文によるロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [ITextFrameFormat](../itextframeformat/)
* クラス [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)