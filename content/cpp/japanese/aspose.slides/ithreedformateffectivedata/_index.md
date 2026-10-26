---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for C++ API リファレンス
description: 有効な3-D書式設定プロパティを表す不変オブジェクト。
type: docs
weight: 4174
url: /ja/aspose.slides/ithreedformateffectivedata/
---
## IThreeDFormatEffectiveData クラス

有効な3-D書式設定プロパティを表す不変オブジェクト。

```cpp
class IThreeDFormatEffectiveData : public Aspose::Slides::IThreeDParamSource
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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelBottom](./get_bevelbottom/)() | 下部 3D ベベルのタイプを返します。読み取り専用 [IShapeBevelEffectiveData](../ishapebeveleffectivedata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelTop](./get_beveltop/)() | 上部 3D ベベルのタイプを返します。読み取り専用 [IShapeBevelEffectiveData](../ishapebeveleffectivedata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICameraEffectiveData](../icameraeffectivedata/)\> [get_Camera](./get_camera/)() | カメラの設定を返します。読み取り専用 [ICameraEffectiveData](../icameraeffectivedata/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ContourColor](./get_contourcolor/)() | 輪郭の色を返します。読み取り専用 [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | 3D 輪郭の幅を返します。読み取り専用 **double**。 |
| virtual **double** [get_Depth](./get_depth/)() | 3D シェイプの深さを返します。読み取り専用 **double**。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ExtrusionColor](./get_extrusioncolor/)() | 押し出しの色を返します。読み取り専用 [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | 押し出し効果の高さを返します。読み取り専用 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRigEffectiveData](../ilightrigeffectivedata/)\> [get_LightRig](./get_lightrig/)() | 光源のタイプを返します。読み取り専用 [ILightRigEffectiveData](../ilightrigeffectivedata/)。 |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | マテリアルのタイプを返します。読み取り専用 [MaterialPresetType](../materialpresettype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスを表すかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n 番目' のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

このインターフェイスは [IThreeDFormat](../ithreedformat/) インターフェイスと組み合わせて使用され、継承が適用された有効な書式設定値を返します。

## 参照

* クラス [IThreeDParamSource](../ithreedparamsource/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)