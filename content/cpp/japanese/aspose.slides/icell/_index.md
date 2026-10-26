---
title: ICell
second_title: Aspose.Slides for C++ API リファレンス
description: テーブル内のセルを表します。
type: docs
weight: 1639
url: /ja/aspose.slides/icell/
---
## ICell クラス

Represents a cell in a table.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいと見なす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいと見なす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | テキストボックスがセル内で中央に配置されているかどうかを判断します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | このセルの書式設定プロパティを含む [CellFormat](../cellformat/) オブジェクトを返します。読み取り専用 [ICellFormat](../icellformat/)。 |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | 現在のセルが跨ぐ親テーブルのテーブルグリッド内の列数を返します。このプロパティにより、セルはテーブル内の他のセルの垂直境界を跨いで結合されたように見えます。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | セルの最初の列を取得します。読み取り専用 [IColumn](../icolumn/)。 |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | セルがカバーする最初の列のインデックスを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | セルの最初の行を取得します。読み取り専用 [IRow](../irow/)。 |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | セルがカバーする最初の行のインデックスを返します。読み取り専用 **int32_t**。 |
| virtual **double** [get_Height](./get_height/)() | セルの高さを返します。読み取り専用 **double**。 |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | セルが調整されたセルと結合されている場合は true、そうでない場合は false を返します。読み取り専用 **bool**。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/) の下余白を返します。読み取り **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/) の左余白を返します。読み取り **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/) の右余白を返します。読み取り **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/) の上余白を返します。読み取り **double**。 |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | セルの最小高さを返します。これはセルが覆うすべての行の最小高さの合計です。読み取り専用 **double**。 |
| virtual **double** [get_OffsetX](./get_offsetx/)() | テーブルの左側からセルの左側までの距離を返します。読み取り専用 **double**。 |
| virtual **double** [get_OffsetY](./get_offsety/)() | テーブルの上側からセルの上側までの距離を返します。読み取り専用 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | 結合されたセルが跨ぐ行数を返します。これは他のセルの vMerge 属性と組み合わせて水平結合の開始セルを指定するために使用されます。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | セルの親 [Table](../table/) オブジェクトを返します。読み取り専用 [ITable](../itable/)。 |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | テキストアンカータイプを返します。読み取り [Slides::TextAnchorType](../textanchortype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | セルのテキストフレームを返します。読み取り専用 [ITextFrame](../itextframe/)。 |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 縦書きテキストのタイプを返します。読み取り [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual **double** [get_Width](./get_width/)() | セルの幅を返します。読み取り専用 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | テキストボックスがセル内で中央に配置されているかどうかを判断します。書き込み **bool**。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/) の下余白を設定します。書き込み **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/) の左余白を設定します。書き込み **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/) の右余白を設定します。書き込み **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/) の上余白を設定します。書き込み **double**。 |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | テキストアンカータイプを設定します。書き込み [Slides::TextAnchorType](../textanchortype/)。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 縦書きテキストのタイプを設定します。書き込み [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | 列インデックスでセルを2つに分割します。 |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | 高さでセルを分割します。 |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | 行インデックスでセルを2つに分割します。 |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | 幅でセルを分割します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ISlideComponent](../islidecomponent/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)