---
title: ITextFrameFormat
second_title: Aspose.Slides for C++ API リファレンス
description: TextFrame の書式プロパティを含みます。
type: docs
weight: 4083
url: /ja/aspose.slides/itextframeformat/
---
## ITextFrameFormat クラス

[TextFrame](../textframe/) の書式プロパティを含みます。

```cpp
class ITextFrameFormat : public virtual System::Object
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | [TextFrame](../textframe/) 内の垂直アンカー テキストを返します。[TextAnchorType](../textanchortype/) を参照してください。 |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | テキストの自動調整モードを返します。[TextAutofitType](../textautofittype/) を参照してください。 |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | [NullableBool::True](../nullablebool/) の場合、テキストはボックス内で水平に中央揃えされるべきです。[NullableBool](../nullablebool/) を参照してください。 |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | テキスト領域の列数を返します。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。0 は未定義の値を意味します。**int32_t** を参照してください。 |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | テキスト領域の列間の間隔（ポイント単位）を返します。これは列が 1 つ以上ある場合にのみ適用されます。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。**double** を参照してください。 |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | テキストを 3D シーンから完全に除外するかどうかを取得または設定します。**bool** を参照してください。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/) の下余白（ポイント）を返します。**double** を参照してください。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/) の左余白（ポイント）を返します。**double** を参照してください。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/) の右余白（ポイント）を返します。**double** を参照してください。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/) の上余白（ポイント）を返します。**double** を参照してください。 |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用されます。このプロパティと TextVerticalType プロパティの事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。**float** を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | テキストのスタイルを返します。読み取り専用 [ITextStyle](../itextstyle/)。 |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | テキストの向きを決定します。このプロパティと RotationAngle プロパティのカスタム角度から要約された視覚的テキスト回転の結果値です。[Slides::TextVerticalType](../textverticaltype/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | [ThreeDFormat](../threedformat/) オブジェクトを返します。これはテキストの 3D エフェクト プロパティを表します。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | テキスト折り返しシェイプを取得します。[TextShapeType](../textshapetype/) を参照してください。 |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | テキストが [TextFrame](../textframe/) の余白で折り返されている場合は **True** です。[NullableBool](../nullablebool/) を参照してください。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | 継承が適用された有効なテキストフレーム書式データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | [TextFrame](../textframe/) 内の垂直アンカー テキストを設定します。[TextAnchorType](../textanchortype/) に書き込みます。 |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | テキストの自動調整モードを設定します。[TextAutofitType](../textautofittype/) に書き込みます。 |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | [NullableBool::True](../nullablebool/) の場合、テキストはボックス内で水平に中央揃えされるべきです。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | テキスト領域の列数を設定します。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。0 は未定義の値を意味します。**int32_t** に書き込みます。 |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | テキスト領域の列間の間隔（ポイント単位）を設定します。これは列が 1 つ以上ある場合にのみ適用されます。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。**double** に書き込みます。 |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | テキストを 3D シーンから完全に除外するかどうかを取得または設定します。**bool** に書き込みます。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/) の下余白（ポイント）を設定します。**double** に書き込みます。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/) の左余白（ポイント）を設定します。**double** に書き込みます。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/) の右余白（ポイント）を設定します。**double** に書き込みます。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/) の上余白（ポイント）を設定します。**double** に書き込みます。 |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用されます。このプロパティと TextVerticalType プロパティの事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。**float** に書き込みます。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | テキストの向きを決定します。このプロパティと RotationAngle プロパティのカスタム角度から要約された視覚的テキスト回転の結果値です。[Slides::TextVerticalType](../textverticaltype/) に書き込みます。 |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | テキスト折り返しシェイプを設定します。[TextShapeType](../textshapetype/) に書き込みます。 |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | [TextFrame](../textframe/) の余白でテキストが折り返されている場合は **True** です。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)