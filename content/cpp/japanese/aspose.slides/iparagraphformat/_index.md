---
title: IParagraphFormat
second_title: Aspose.Slides for C++ API リファレンス
description: このクラスは段落の書式設定プロパティを含みます。IParagraphFormatEffectiveData とは異なり、このクラスのすべてのプロパティは書き込み可能です。
type: docs
weight: 3147
url: /ja/aspose.slides/iparagraphformat/
---
## IParagraphFormat クラス


This class contains the paragraph formatting properties. Unlike [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), all properties of this class are writeable.

```cpp
class IParagraphFormat : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | 継承なしで段落のテキスト揃えを返します。参照 [TextAlignment](../textalignment/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | 段落の箇条書き形式を返します。読み取り専用 [IBulletFormat](../ibulletformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | 段落のデフォルトの一部形式を返します。継承は適用されません。読み取り専用 [IPortionFormat](../iportionformat/)。 |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | 継承なしでデフォルトのタブ幅を返します。読み取り **float**。 |
| virtual **int16_t** [get_Depth](./get_depth/)() | 段落の深さを返します。値 0 は未定義を意味します。読み取り **int16_t**。 |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 段落で東アジアの改行が使用されているかを判断します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 継承なしで段落のフォント揃えを返します。参照 [Slides::FontAlignment](../fontalignment/)。 |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 段落で句読点のハンギングが使用されているかを判断します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_Indent](./get_indent/)() | 継承なしで段落の最初の行インデント/ハンギングインデントを返します。ハンギングインデントは負の値で定義できます。読み取り **float**。 |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 段落でラテン文字の改行が使用されているかを判断します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 継承なしで段落の左余白を返します。読み取り **float**。 |
| virtual **float** [get_MarginRight](./get_marginright/)() | 継承なしで段落の右余白を返します。読み取り **float**。 |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 段落で右から左への書字が使用されているかを判断します。継承は適用されません。参照 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 継承なしで段落の最終行の後の余白量を返します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズでの余白サイズを指定します。読み取り **float**。 |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 継承なしで段落の最初の行の前の余白量を返します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズでの余白サイズを指定します。読み取り **float**。 |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 段落内のベースライン間の余白量を返します。正の値はパーセンテージ、負の値はポイントでのサイズを示します。継承は適用されません。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 指定したインデックスの段落タブ設定を返します。継承は適用されません。読み取り専用 [Aspose::Slides::ITab](../itab/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | 段落のタブ設定を返します。継承は適用されません。読み取り専用 [ITabCollection](../itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | 継承が適用された有効な段落書式データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | 継承なしで段落のテキスト揃えを設定します。書き込み [TextAlignment](../textalignment/)。 |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | 継承なしでデフォルトのタブ幅を設定します。書き込み **float**。 |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | 段落の深さを設定します。値 0 は未定義を意味します。書き込み **int16_t**。 |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | 段落で東アジアの改行が使用されているかを設定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | 継承なしで段落のフォント揃えを設定します。書き込み [Slides::FontAlignment](../fontalignment/)。 |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | 段落で句読点のハンギングが使用されているかを設定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_Indent](./set_indent/)(**float**) | 継承なしで段落の最初の行インデント/ハンギングインデントを設定します。ハンギングインデントは負の値で定義できます。書き込み **float**。 |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | 段落でラテン文字の改行が使用されているかを設定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 継承なしで段落の左余白を設定します。書き込み **float**。 |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 継承なしで段落の右余白を設定します。書き込み **float**。 |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | 段落で右から左への書字が使用されているかを設定します。継承は適用されません。書き込み [NullableBool](../nullablebool/)。 |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 継承なしで段落の最終行の後の余白量を設定します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズでの余白サイズを指定します。書き込み **float**。 |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 継承なしで段落の最初の行の前の余白量を設定します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズでの余白サイズを指定します。書き込み **float**。 |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 段落内のベースライン間の余白量を設定します。正の値はパーセンテージ、負の値はポイントでのサイズを示します。継承は適用されません。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考


このクラスは、特定の段落に定義された段落書式プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が得られます。

継承されたものを含む有効な書式パラメータ値を取得するには、[IParagraphFormat::GetEffective](./geteffective/) メソッドを使用する必要があり、このメソッドは [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) インスタンスを返します。

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* Library [Aspose.Slides](../../)