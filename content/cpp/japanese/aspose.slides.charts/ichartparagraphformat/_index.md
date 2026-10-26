---
title: IChartParagraphFormat
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの段落書式プロパティを表します。
type: docs
weight: 781
url: /ja/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat クラス


チャートの段落書式プロパティを表します。

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 参照型オブジェクトを C# スタイルで比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 値型オブジェクトを C# スタイルで比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | 段落のテキスト配置を取得します。[TextAlignment](../../aspose.slides/textalignment/) を参照してください。 |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | デフォルトのタブ幅を取得します。**float** を取得してください。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 段落で東アジアの改行が使用されているかどうかを判定します。[NullableBool](../../aspose.slides/nullablebool/) を参照してください。 |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 段落のフォント配置を取得します。[Slides::FontAlignment](../../aspose.slides/fontalignment/) を参照してください。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 段落でハンギング句読点が使用されているかどうかを判定します。[NullableBool](../../aspose.slides/nullablebool/) を参照してください。 |
| virtual **float** [get_Indent](./get_indent/)() | 段落の先頭行インデント/ハンギングインデントを取得します。ハンギングインデントは負の値で定義できます。**float** を取得してください。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 段落でラテン文字の改行が使用されているかどうかを判定します。[NullableBool](../../aspose.slides/nullablebool/) を参照してください。 |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 段落の左余白を取得します。**float** を取得してください。 |
| virtual **float** [get_MarginRight](./get_marginright/)() | 段落の右余白を取得します。**float** を取得してください。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 段落で右から左への書字が使用されているかどうかを判定します。[NullableBool](../../aspose.slides/nullablebool/) を参照してください。 |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 段落の最終行の後のスペース量を取得します。**float** を取得してください。 |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 段落の最初の行の前のスペース量を取得します。**float** を取得してください。 |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 段落のベースライン間のスペース量を取得します。**float** を取得してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 指定したインデックスの段落タブを取得します。読み取り専用 [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | 段落のタブ設定を取得します。読み取り専用 [ITabCollection](../../aspose.slides/itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 対象の型がオブジェクトのインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | 段落のテキスト配置を設定します。[TextAlignment](../../aspose.slides/textalignment/) を設定してください。 |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | デフォルトのタブ幅を設定します。**float** を設定してください。 |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | 段落で東アジアの改行が使用されているかどうかを設定します。[NullableBool](../../aspose.slides/nullablebool/) を設定してください。 |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | 段落のフォント配置を設定します。[Slides::FontAlignment](../../aspose.slides/fontalignment/) を設定してください。 |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | 段落でハンギング句読点が使用されているかどうかを設定します。[NullableBool](../../aspose.slides/nullablebool/) を設定してください。 |
| virtual void [set_Indent](./set_indent/)(**float**) | 段落の先頭行インデント/ハンギングインデントを設定します。ハンギングインデントは負の値で定義できます。**float** を設定してください。 |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | 段落でラテン文字の改行が使用されているかどうかを設定します。[NullableBool](../../aspose.slides/nullablebool/) を設定してください。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 段落の左余白を設定します。**float** を設定してください。 |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 段落の右余白を設定します。**float** を設定してください。 |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | 段落で右から左への書字が使用されているかどうかを設定します。[NullableBool](../../aspose.slides/nullablebool/) を設定してください。 |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 段落の最終行の後のスペース量を設定します。**float** を設定してください。 |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 段落の最初の行の前のスペース量を設定します。**float** を設定してください。 |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 段落のベースライン間のスペース量を設定します。**float** を設定してください。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタ（共有ポインタではなく）に設定します。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照項目

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)