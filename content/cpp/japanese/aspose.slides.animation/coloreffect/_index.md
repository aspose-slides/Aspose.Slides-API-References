---
title: ColorEffect
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーション ビヘイビア用のカラー エフェクトを表します。
type: docs
weight: 79
url: /ja/aspose.slides.animation/coloreffect/
---
## ColorEffect クラス

アニメーション ビヘイビア用のカラー エフェクトを表します。

```cpp
class ColorEffect : public Aspose::Slides::Animation::Behavior,
                    public Aspose::Slides::Animation::IColorEffect
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ColorEffect](./coloreffect/)() | 新しいインスタンスを作成します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみです。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | アニメーション ビヘイビアが蓄積されるかどうかを表します。[NullableBool](../../aspose.slides/nullablebool/) を読み取ります。 |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | 現在のアニメーション ビヘイビアが他の実行中アニメーションと結合されるかどうかを表します。[BehaviorAdditiveType](../behavioradditivetype/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOffset](../icoloroffset/)\> [get_By](./get_by/)() override | カラー アニメーションの相対オフセット値を記述します。[IColorOffset](../icoloroffset/) を読み取ります。 |
| [Aspose::Slides::Animation::ColorSpace](../colorspace/) [get_ColorSpace](./get_colorspace/)() override | ビヘイビアの色空間を表します。[Animation::ColorSpace](../colorspace/) を読み取ります。 |
| [ColorDirection](../colordirection/) [get_Direction](./get_direction/)() override | カラーホイール上で色相を回す方向を指定します。[ColorDirection](../colordirection/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_From](./get_from/)() override | この値はビヘイビアの開始色を指定するために使用されます。[IColorFormat](../../aspose.slides/icolorformat/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | ビヘイビアのプロパティを表します。読み取り専用 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | エフェクト ビヘイビアのタイミング プロパティを表します。[ITiming](../itiming/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_To](./get_to/)() override | アニメーション カラー変更の結果カラーを記述します。[IColorFormat](../../aspose.slides/icolorformat/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | アニメーション ビヘイビアが蓄積されるかどうかを表します。[NullableBool](../../aspose.slides/nullablebool/) に書き込みます。 |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | 現在のアニメーション ビヘイビアが他の実行中アニメーションと結合されるかどうかを表します。[BehaviorAdditiveType](../behavioradditivetype/) に書き込みます。 |
| void [set_By](./set_by/)([System::SharedPtr](../../system/sharedptr/)\<[IColorOffset](../icoloroffset/)\>) override | カラー アニメーションの相対オフセット値を記述します。[IColorOffset](../icoloroffset/) に書き込みます。 |
| void [set_ColorSpace](./set_colorspace/)([Aspose::Slides::Animation::ColorSpace](../colorspace/)) override | ビヘイビアの色空間を表します。[Animation::ColorSpace](../colorspace/) に書き込みます。 |
| void [set_Direction](./set_direction/)([ColorDirection](../colordirection/)) override | カラーホイール上で色相を回す方向を指定します。[ColorDirection](../colordirection/) に書き込みます。 |
| void [set_From](./set_from/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | この値はビヘイビアの開始色を指定するために使用されます。[IColorFormat](../../aspose.slides/icolorformat/) に書き込みます。 |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | エフェクト ビヘイビアのタイミング プロパティを表します。[ITiming](../itiming/) に書き込みます。 |
| void [set_To](./set_to/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | アニメーション カラー変更の結果カラーを記述します。[IColorFormat](../../aspose.slides/icolorformat/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | テンプレートの n 番目の引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Behavior](../behavior/)
* クラス [IColorEffect](../icoloreffect/)
* 名前空間 [Aspose::Slides::Animation](../)
* ライブラリ [Aspose.Slides](../../)