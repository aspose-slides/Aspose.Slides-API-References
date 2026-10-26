---
title: Cell
second_title: Aspose.Slides の C++ API リファレンス
description: テーブルのセルを表します。
type: docs
weight: 300
url: /ja/aspose.slides/cell/
---
## Cell クラス

テーブルのセルを表します。

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | セル内にテキストボックスが中央揃えかどうかを判断します。Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | このセルの書式設定プロパティを含む [CellFormat](../cellformat/) オブジェクトを返します。Read-only [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | 現在のセルが跨ぐ親テーブルのテーブルグリッド内の列数を返します。このプロパティにより、セルはテーブル内の他のセルの垂直境界を跨ぐことで結合されたように見えます。Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | セルの最初の列を取得します。Read-only [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | セルがカバーする最初の列のインデックスを返します。Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | セルの最初の行を取得します。Read-only [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | セルがカバーする最初の行のインデックスを返します。Read-only **int32_t**. |
| **double** [get_Height](./get_height/)() override | セルの高さを返します。Read-only **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | セルが調整されたセルと結合されている場合は true、そうでない場合は false を返します。Read-only **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | [TextFrame](../textframe/) の下余白を返します。Read **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | [TextFrame](../textframe/) の左余白を返します。Read **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | [TextFrame](../textframe/) の右余白を返します。Read **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | [TextFrame](../textframe/) の上余白を返します。Read **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | セルの最小高さを返します。これはセルがカバーするすべての行の最小高さの合計です。Read-only **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | テーブルの左側からセルの左側までの距離を返します。Read-only **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | テーブルの上側からセルの上側までの距離を返します。Read-only **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | セルの親プレゼンテーションを返します。Read-only [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | 結合されたセルが跨ぐ行数を返します。これは他のセルの vMerge 属性と組み合わせて水平結合の開始セルを指定するために使用されます。Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | セルの親スライドを返します。Read-only [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | セルの親 [Table](../table/) オブジェクトを返します。Read-only [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | テキストアンカーのタイプを返します。Read [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | セルのテキストフレームを返します。Read-only [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | 縦書きテキストのタイプを返します。Read [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | セルの幅を返します。Read-only **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | セル内にテキストボックスが中央揃えかどうかを判断します。Write **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | [TextFrame](../textframe/) の下余白を設定します。Write **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | [TextFrame](../textframe/) の左余白を設定します。Write **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | [TextFrame](../textframe/) の右余白を設定します。Write **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | [TextFrame](../textframe/) の上余白を設定します。Write **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | テキストアンカーのタイプを設定します。Write [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | 縦書きテキストのタイプを設定します。Write [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | 列インデックスでセルを 2 つに分割します。 |
| void [SplitByHeight](./splitbyheight/)(**double**) override | 高さでセルを分割します。 |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | 行インデックスでセルを 2 つに分割します。 |
| void [SplitByWidth](./splitbywidth/)(**double**) override | 幅でセルを分割します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IDOMObject](../idomobject/)
* クラス [ICell](../icell/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)