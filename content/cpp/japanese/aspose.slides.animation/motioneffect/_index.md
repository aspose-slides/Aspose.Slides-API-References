---
title: MotionEffect
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトのモーションエフェクトの振る舞いを表します。
type: docs
weight: 469
url: /ja/aspose.slides.animation/motioneffect/
---
## MotionEffect クラス

エフェクトのモーションエフェクトの振る舞いを表します。

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | アニメーション動作が蓄積されるかどうかを表します。取得 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | 現在のアニメーション動作が他の実行中アニメーションと結合されるかどうかを表します。取得 [BehaviorAdditiveType](../behavioradditivetype/)。 |
| **float** [get_Angle](./get_angle/)() override | モーションパスの相対角度を記述します。取得 **float**。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | アニメーションの相対オフセット値（パーセント）を記述します。取得 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | アニメーション開始位置の x/y 座標（パーセント）を指定します。取得 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | モーションパスの原点がスライドのレイアウトや親など、何に対して相対的であるかを指定します。取得 [MotionOriginType](../motionorigintype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | アニメーションの動きのための座標に続くパスプリミティブを指定します。取得 [IMotionPath](../imotionpath/)。 |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | シェイプが移動したときにモーションパスがどのように動くかを指定します。取得 [MotionPathEditMode](../motionpatheditmode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | 動作のプロパティを表します。読み取り専用 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | X 角度でモーションパスを回転させる際に使用される回転の中心を記述します。取得 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | エフェクト動作のタイミングプロパティを表します。取得 [ITiming](../itiming/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | アニメーションモーションエフェクトの対象位置（パーセント）を指定します。取得 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの C# アナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの C# アナログです。カスタム型のクローン作成を可能にします。 |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | アニメーション動作が蓄積されるかどうかを表します。書き込み [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | 現在のアニメーション動作が他の実行中アニメーションと結合されるかどうかを表します。書き込み [BehaviorAdditiveType](../behavioradditivetype/)。 |
| void [set_Angle](./set_angle/)(**float**) override | モーションパスの相対角度を記述します。書き込み **float**。 |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | アニメーションの相対オフセット値（パーセント）を記述します。書き込み [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | アニメーション開始位置の x/y 座標（パーセント）を指定します。書き込み [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | モーションパスの原点がスライドのレイアウトや親など、何に対して相対的であるかを指定します。書き込み [MotionOriginType](../motionorigintype/)。 |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | アニメーションの動きのための座標に続くパスプリミティブを指定します。書き込み [IMotionPath](../imotionpath/)。 |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | シェイプが移動したときにモーションパスがどのように動くかを指定します。書き込み [MotionPathEditMode](../motionpatheditmode/)。 |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | X 角度でモーションパスを回転させる際に使用される回転の中心を記述します。書き込み [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | エフェクト動作のタイミングプロパティを表します。書き込み [ITiming](../itiming/)。 |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | アニメーションモーションエフェクトの対象位置（パーセント）を指定します。書き込み [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) メソッドの C# アナログです。カスタムオブジェクトの文字列変換を可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Behavior](../behavior/)
* クラス [IMotionEffect](../imotioneffect/)
* 名前空間 [Aspose::Slides::Animation](../)
* ライブラリ [Aspose.Slides](../../)