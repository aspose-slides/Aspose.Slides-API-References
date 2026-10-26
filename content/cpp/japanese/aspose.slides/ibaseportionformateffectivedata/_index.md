---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for C++ API リファレンス
description: 効果的なテキスト部分の書式設定プロパティを含む不変オブジェクトのための基本インターフェイスです。
type: docs
weight: 1470
url: /ja/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData クラス


効果的なテキスト部分の書式設定プロパティを含む不変オブジェクトのための基本インターフェイスです。

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style の浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style の浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const |  For internal purposes only. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | 代替言語の Id を返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | 複合スクリプトフォント情報を返します。読み取り専用 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | 東アジアフォント情報を返します。読み取り専用 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | テキスト [EffectFormat](../effectformat/) プロパティを返します。読み取り専用 [IEffectFormatEffectiveData](../ieffectformateffectivedata/)。 |
| virtual **float** [get_Escapement](./get_escapement/)() | 上付きまたは下付きテキストを返します。値は -100%（下付き）から 100%（上付き）です。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | テキスト [FillFormat](../fillformat/) プロパティを返します。読み取り専用 [IFillFormatEffectiveData](../ifillformateffectivedata/)。 |
| virtual **bool** [get_FontBold](./get_fontbold/)() | フォントが太字かどうかを判定します。読み取り専用 **bool**。 |
| virtual **float** [get_FontHeight](./get_fontheight/)() | テキスト部分のフォント高さ（ポイント単位）を返します。読み取り専用 **float**。 |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | フォントがイタリックかどうかを判定します。読み取り専用 **bool**。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | テキストの下線タイプを返します。読み取り専用 [TextUnderlineType](../textunderlinetype/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | テキストのハイライトに使用される色を返します。読み取り専用 [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | 下線スタイルが独自の [FillFormat](../fillformat/) プロパティを持つか、テキストの [FillFormat](../fillformat/) プロパティから継承するかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | 下線スタイルが独自の [LineFormat](../lineformat/) プロパティを持つか、テキストの [LineFormat](../lineformat/) プロパティから継承するかを判定します。読み取り専用 **bool**。 |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | カーニングを有効にすべき最小フォントサイズを返します。読み取り専用 **float**。 |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | 言語の Id を返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | ラテンフォント情報を返します。読み取り専用 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | テキストのアウトライン用 [LineFormat](../lineformat/) プロパティを返します。読み取り専用 [ILineFormatEffectiveData](../ilineformateffectivedata/)。 |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | テキストの高さを正規化すべきかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | テキストが校正されないようにすべきかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | スマートタグをクリーニングすべきかどうかを判定します。読み取り専用 **bool**。 |
| virtual **float** [get_Spacing](./get_spacing/)() | 文字間隔の増分（ポイント単位）を返します。読み取り専用 **float**。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | テキストの取り消し線タイプを返します。読み取り専用 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | シンボリックフォント情報を返します。読み取り専用 [IFontData](../ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | テキストの大文字化タイプを返します。読み取り専用 [Slides::TextCapType](../textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | 下線線 [FillFormat](../fillformat/) のプロパティを返します。読み取り専用 [IFillFormatEffectiveData](../ifillformateffectivedata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | 下線線をアウトラインするために使用される [LineFormat](../lineformat/) プロパティを返します。読み取り専用 [ILineFormatEffectiveData](../ilineformateffectivedata/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクターです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文によるロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)