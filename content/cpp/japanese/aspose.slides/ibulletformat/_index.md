---
title: IBulletFormat
second_title: Aspose.Slides for C++ API リファレンス
description: 段落の箇条書き書式設定プロパティを表します。
type: docs
weight: 1561
url: /ja/aspose.slides/ibulletformat/
---
## IBulletFormat クラス

段落の箇条書き書式設定プロパティを表します。

```cpp
class IBulletFormat : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | 箇条書きが有効な場合、実効段落の Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します（PowerPoint が段落の箇条書き/番号付けを有効にしたときと同様です）。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付けを無効にしたときと同様です）。インデントシフトは現在の箇条書きコンテキスト、すなわち IBulletFormat::get(set)_Type、.NumberedBulletStyle、および最初の部分の FontHeight を基準に適用されます。非ゼロのインデントシフトは現在の段落の実効 Indent と MarginLeft に適用され（結果の値はローカル値になります）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual char16_t [get_Char](./get_char/)() | 継承なしで段落の箇条書き文字を返します。**wchar_t** を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | 継承なしで段落の箇条書きの色フォーマットを返します。読み取り専用 [IColorFormat](../icolorformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | 継承なしで段落の箇条書きフォントを返します。[IFontData](../ifontdata/) を読み取ります。 |
| virtual **float** [get_Height](./get_height/)() | 継承なしで段落の箇条書きの高さを返します。値 std::numeric_limits<float>::quiet_NaN() は、箇条書きが段落の最初の部分から高さを継承することを示します。**float** を読み取ります。 |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自の色を持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分から色を継承する場合は **[NullableBool::False](../nullablebool/)** を返します。[NullableBool](../nullablebool/) を読み取ります。 |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自のフォントを持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分からフォントを継承する場合は **[NullableBool::False](../nullablebool/)** を返します。[NullableBool](../nullablebool/) を読み取ります。 |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | 継承なしで番号付き箇条書きグループに使用される最初の番号を返します。**int16_t** を読み取ります。 |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | 継承なしで番号付き箇条書きのスタイルを返します。[NumberedBulletStyle](../numberedbulletstyle/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 継承なしで段落の箇条書きとして使用される画像を返します。読み取り専用 [ISlidesPicture](../islidespicture/)。 |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | 継承なしで段落の箇条書きタイプを返します。[BulletType](../bullettype/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | 継承が適用された実効箇条書き書式データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合に対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定した値だけ共有参照カウントを減少させます。 |
| virtual void [set_Char](./set_char/)(char16_t) | 継承なしで段落の箇条書き文字を設定します。**wchar_t** を書き込みます。 |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 継承なしで段落の箇条書きフォントを設定します。[IFontData](../ifontdata/) を書き込みます。 |
| virtual void [set_Height](./set_height/)(**float**) | 継承なしで段落の箇条書き高さを設定します。値 std::numeric_limits<float>::quiet_NaN() は、箇条書きが段落の最初の部分から高さを継承することを示します。**float** を書き込みます。 |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自の色を持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分から色を継承する場合は **[NullableBool::False](../nullablebool/)** を設定します。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自のフォントを持つ場合は **[NullableBool::True](../nullablebool/)**、段落の最初の部分からフォントを継承する場合は **[NullableBool::False](../nullablebool/)** を設定します。[NullableBool](../nullablebool/) に書き込みます。 |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | 継承なしで番号付き箇条書きグループに使用される最初の番号を設定します。**int16_t** に書き込みます。 |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | 継承なしで番号付き箇条書きのスタイルを設定します。[NumberedBulletStyle](../numberedbulletstyle/) に書き込みます。 |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | 継承なしで段落の箇条書きタイプを設定します。[BulletType](../bullettype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)