---
title: IBaseSlide
second_title: Aspose.Slides for C++ API リファレンス
description: すべてのスライドタイプに共通するデータを表します。
type: docs
weight: 1496
url: /ja/aspose.slides/ibaseslide/
---
## IBaseSlide クラス

すべてのスライドタイプに共通するデータを表します。

```cpp
class IBaseSlide : public virtual Aspose::Slides::Theme::IThemeable
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | このテーマ可能オブジェクトに対する有効なテーマを返します。 |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](./)\>) | 2つの [IBaseSlide](./) インスタンスが等しいかどうかを判断します。戻り値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、2つのスライドは等しいとみなされます。比較は SlideId などの固有識別子や、Date [Placeholder](../placeholder/) における現在の日付値などの動的コンテンツは考慮しません。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないとされるにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないとされるにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() | スライドの背景を返します。読み取り専用 [IBackground](../ibackground/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) | 指定されたインデックスの ActiveX コントロールを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() | スライド上の ActiveX コントロールのコレクションを返します。読み取り専用 [IControlCollection](../icontrolcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | スライドのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | 含まれるハイパーリンクへの簡易アクセスを提供します。読み取り専用 [IHyperlinkQueries](../ihyperlinkqueries/)。 |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | スライドの名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | 指定されたインデックスのシェイプを返します。読み取り専用 [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | スライドのシェイプを返します。読み取り専用 [IShapeCollection](../ishapecollection/)。 |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | マスタースライド上のシェイプをスライドで表示するかどうかを指定します。マスタースライド自体ではこのプロパティは常に **false** を返します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](./)\> [get_Slide](../islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](./)。 |
| virtual **uint32_t** [get_SlideId](./get_slideid/)() | スライドの ID を返します。読み取り専用 **uint32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() | スライドショー中に指定されたスライドがどのように進行するかに関する情報を含む TransitionEx オブジェクトを返します。読み取り専用 [ISlideShowTransition](../islideshowtransition/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() | アニメーションタイムラインオブジェクトを返します。読み取り専用 [IAnimationTimeLine](../ianimationtimeline/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | すべての許容可能なシェイプ内のすべての段落で、同じ書式設定を持つランを結合します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピーコンストラクトを可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | スライドの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | マスタースライド上のシェイプをスライドで表示するかどうかを指定します。マスタースライド自体ではこのプロパティは常に **false** を返します。書き込み **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウントの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IThemeable](../../aspose.slides.theme/ithemeable/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)