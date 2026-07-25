---
title: SlideShowSettings
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのスライドショー設定を表します。
type: docs
weight: 5214
url: /ja/aspose.slides/slideshowsettings/
---
## SlideShowSettings クラス


プレゼンテーションのスライドショー設定を表します。

```cpp
class SlideShowSettings : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされる C#-style の浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされる C#-style の浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **bool** [get_Loop](./get_loop/)() | ループ [Slide](../slide/) 表示 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_PenColor](./get_pencolor/)() | [Slide](../slide/) ショーのペンカラー |
| **bool** [get_ShowAnimation](./get_showanimation/)() | [Slide](../slide/) ショーで [Animation](../../aspose.slides.animation/) を表示 |
| **bool** [get_ShowMediaControls](./get_showmediacontrols/)() const | メディアコントロールを表示 |
| **bool** [get_ShowNarration](./get_shownarration/)() | [Slide](../slide/) ショーでナレーションを表示 |
| [System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\> [get_Slides](./get_slides/)() const | [Slides](../) 範囲 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\> [get_SlideShowType](./get_slideshowtype/)() | スライドショーのタイプを取得します。次の [SlideShowType](../slideshowtype/) 祖先で表されます: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) および [BrowsedByIndividual](../browsedbyindividual/) |
| **bool** [get_UseTimings](./get_usetimings/)() | [Slide](../slide/) ショーでタイミングを使用 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Loop](./set_loop/)(**bool**) | ループ [Slide](../slide/) 表示 |
| void [set_ShowAnimation](./set_showanimation/)(**bool**) | [Slide](../slide/) ショーで [Animation](../../aspose.slides.animation/) を表示 |
| void [set_ShowMediaControls](./set_showmediacontrols/)(**bool**) | メディアコントロールを表示 |
| void [set_ShowNarration](./set_shownarration/)(**bool**) | [Slide](../slide/) ショーでナレーションを表示 |
| void [set_Slides](./set_slides/)([System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\>) | [Slides](../) 範囲 |
| void [set_SlideShowType](./set_slideshowtype/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\>) | スライドショーのタイプを設定します。次の [SlideShowType](../slideshowtype/) 祖先で表されます: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) および [BrowsedByIndividual](../browsedbyindividual/) |
| void [set_UseTimings](./set_usetimings/)(**bool**) | [Slide](../slide/) ショーでタイミングを使用 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させて返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)