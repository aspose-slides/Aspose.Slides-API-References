---
title: IEffectFormat
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプの効果プロパティを表します。
type: docs
weight: 2029
url: /ja/aspose.slides/ieffectformat/
---
## IEffectFormat クラス

シェイプの効果プロパティを表します。

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | ぼかし効果を無効にします。 |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | 塗り重ね効果を無効にします。 |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | 発光効果を無効にします。 |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | 内側影効果を無効にします。 |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | 外側影効果を無効にします。 |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | プリセット影効果を無効にします。 |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | 反射効果を無効にします。 |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | ソフトエッジ効果を無効にします。 |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | 塗り重ね効果を有効にします。 |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | 発光効果を有効にします。 |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | 内側影効果を有効にします。 |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | 外側影効果を有効にします。 |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | プリセット影効果を有効にします。 |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | 反射効果を有効にします。 |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | ソフトエッジ効果を有効にします。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | ぼかし効果。 [Effects::IBlur](../../aspose.slides.effects/iblur/) を取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | 塗り重ね効果。 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) を取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | 発光効果。 [Effects::IGlow](../../aspose.slides.effects/iglow/) を取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | 内側影。 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) を取得。 |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | すべての効果が無効化されている場合に true を返します（作成直後のデフォルト [EffectFormat](../effectformat/) オブジェクト）。 読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | 外側影。 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) を取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | プリセット影。 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) を取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | 反射。 [Effects::IReflection](../../aspose.slides.effects/ireflection/) を取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | ソフトエッジ。 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) を取得。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | 継承が適用された実際の効果書式設定データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を有効にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローンを有効にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | ぼかし効果。 [Effects::IBlur](../../aspose.slides.effects/iblur/) に書き込みます。 |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | 塗り重ね効果。 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) に書き込みます。 |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | 発光効果。 [Effects::IGlow](../../aspose.slides.effects/iglow/) に書き込みます。 |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | 内側影。 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) に書き込みます。 |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | 外側影。 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) に書き込みます。 |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | プリセット影。 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) に書き込みます。 |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | 反射。 [Effects::IReflection](../../aspose.slides.effects/ireflection/) に書き込みます。 |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | ソフトエッジ。 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) に書き込みます。 |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | ぼかし効果を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタに設定します（shared ではなく）。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントして返します。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出さないでください。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* Class [IEffectParamSource](../ieffectparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)