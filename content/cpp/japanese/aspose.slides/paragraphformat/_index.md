---
title: ParagraphFormat
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスは段落の書式設定プロパティを含みます。IParagraphFormatEffectiveDataとは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 4668
url: /ja/aspose.slides/paragraphformat/
---
## ParagraphFormat クラス

このクラスは段落の書式設定プロパティを含みます。[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | 継承なしで段落のテキスト配置を返します。参照 [TextAlignment](../textalignment/)。 |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | 継承なしでデフォルトのタブ幅を返します。参照 **float**。 |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | 段落で東アジアの改行が使用されているかを判定します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | 継承なしで段落のフォント配置を返します。参照 [Slides::FontAlignment](../fontalignment/)。 |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | 段落でぶら下げ句読点が使用されているかを判定します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| **float** [get_Indent](./get_indent/)() override | 継承なしで段落の最初行インデント/ぶら下げインデントを返します。ぶら下げインデントは負の値で定義できます。参照 **float**。 |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | 段落でラテン文字の改行が使用されているかを判定します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| **float** [get_MarginLeft](./get_marginleft/)() override | 継承なしで段落の左余白を返します。参照 **float**。 |
| **float** [get_MarginRight](./get_marginright/)() override | 継承なしで段落の右余白を返します。参照 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | 段落で右から左への書字が使用されているかを判定します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | 継承なしで段落の最終行の後の空白量を返します。正の値はフォントサイズの割合で空白を指定し、負の値はポイントサイズで空白のサイズを指定します。参照 **float**。 |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | 継承なしで段落の最初行の前の空白量を返します。正の値はフォントサイズの割合で空白を指定し、負の値はポイントサイズで空白のサイズを指定します。参照 **float**。 |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | 段落の基準線間の空白量を返します。正の値は割合を、負の値はポイント単位のサイズを示します。継承は適用されません。参照 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | 指定されたインデックスの段落のタブ位置を返します。継承は適用されません。読み取り専用 [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | 段落のタブ位置を返します。継承は適用されません。読み取り専用 [ITabCollection](../itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効な段落書式設定データを取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
|  [ParagraphFormat](./paragraphformat/)() | [ParagraphFormat](./) クラスの新しいインスタンスを初期化します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | 継承なしで段落のテキスト配置を設定します。書き込み [TextAlignment](../textalignment/)。 |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | 継承なしでデフォルトのタブ幅を設定します。書き込み **float**。 |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | 段落で東アジアの改行が使用されているかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | 継承なしで段落のフォント配置を設定します。書き込み [Slides::FontAlignment](../fontalignment/)。 |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | 段落でぶら下げ句読点が使用されているかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| void [set_Indent](./set_indent/)(**float**) override | 継承なしで段落の最初行インデント/ぶら下げインデントを設定します。ぶら下げインデントは負の値で定義できます。書き込み **float**。 |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | 段落でラテン文字の改行が使用されているかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | 継承なしで段落の左余白を設定します。書き込み **float**。 |
| void [set_MarginRight](./set_marginright/)(**float**) override | 継承なしで段落の右余白を設定します。書き込み **float**。 |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | 段落で右から左への書字が使用されているかを判定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | 継承なしで段落の最終行の後の空白量を設定します。正の値はフォントサイズの割合で空白を指定し、負の値はポイントサイズで空白のサイズを指定します。書き込み **float**。 |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | 継承なしで段落の最初行の前の空白量を設定します。正の値はフォントサイズの割合で空白を指定し、負の値はポイントサイズで空白のサイズを指定します。書き込み **float**。 |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | 継承なしで段落の基準線間の空白量を設定します。正の値は割合を、負の値はポイント単位のサイズを示します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

このクラスは特定の段落に対して定義された段落書式設定プロパティを取得・操作するために使用されます。つまり、値を取得する際に継承が適用されないため、ほとんどの場合は「未定義」を意味する値が返されます。

継承を含む有効な書式設定パラメータ値を取得するには、[ParagraphFormat::GetEffective](./geteffective/) メソッドを使用してください。このメソッドは [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) インスタンスを返します。

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IParagraphFormat](../iparagraphformat/)
* クラス [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)