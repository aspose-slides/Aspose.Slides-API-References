---
title: IReflection
second_title: Aspose.Slides for C++ API リファレンス
description: 反射効果を表します。
type: docs
weight: 937
url: /ja/aspose.slides.effects/ireflection/
---
## IReflection クラス

反射効果を表します。

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 半径。**double** を読み取ります。 |
| virtual **float** [get_Direction](./get_direction/)() | 反射の方向。**float** を読み取ります。 |
| virtual **double** [get_Distance](./get_distance/)() | 反射の距離。**double** を読み取ります。 |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | アルファ勾配ランプに沿った終了アルファ値（パーセント）の終了位置を指定します。**float** を読み取ります。 |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | 反射の終了不透明度（パーセント）。**float** を読み取ります。 |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | 反射をオフセットする方向（角度）を指定します。**float** を読み取ります。 |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 矩形の配置。[RectangleAlignment](../../aspose.slides/rectanglealignment/) を読み取ります。 |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | シェイプが回転した場合に、反射もシェイプとともに回転すべきかどうかを指定します。**bool** を読み取ります。 |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 水平方向のスケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を読み取ります。 |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 垂直方向のスケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を読み取ります。 |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 水平方向のせん断角度を指定します。**double** を読み取ります。 |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 垂直方向のせん断角度を指定します。**double** を読み取ります。 |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | アルファ勾配ランプに沿った開始アルファ値（パーセント）の開始位置を指定します。**float** を読み取ります。 |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | 開始時の反射不透明度（パーセント）。**float** を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 継承が適用された有効データを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 半径。**double** を書き込みます。 |
| virtual void [set_Direction](./set_direction/)(**float**) | 反射の方向。**float** を書き込みます。 |
| virtual void [set_Distance](./set_distance/)(**double**) | 反射の距離。**double** を書き込みます。 |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | アルファ勾配ランプに沿った終了アルファ値（パーセント）の終了位置を指定します。**float** を書き込みます。 |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | 反射の終了不透明度（パーセント）。**float** を書き込みます。 |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | 反射をオフセットする方向（角度）を指定します。**float** を書き込みます。 |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 矩形の配置。[RectangleAlignment](../../aspose.slides/rectanglealignment/) を書き込みます。 |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | シェイプが回転した場合に、反射もシェイプとともに回転すべきかどうかを指定します。**bool** を書き込みます。 |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 水平方向のスケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を書き込みます。 |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 垂直方向のスケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を書き込みます。 |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 水平方向のせん断角度を指定します。**double** を書き込みます。 |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 垂直方向のせん断角度を指定します。**double** を書き込みます。 |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | アルファ勾配ランプに沿った開始アルファ値（パーセント）の開始位置を指定します。**float** を書き込みます。 |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | 開始時の反射不透明度（パーセント）。**float** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IImageTransformOperation](../iimagetransformoperation/)
* クラス [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 名前空間 [Aspose::Slides::Effects](../)
* ライブラリ [Aspose.Slides](../../)