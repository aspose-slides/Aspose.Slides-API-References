---
title: Rotation3D
second_title: Aspose.Slides for C++ API リファレンス
description: チャートの 3D 回転を表します。
type: docs
weight: 1327
url: /ja/aspose.slides.charts/rotation3d/
---
## Rotation3D クラス

チャートの 3D 回転を表します。

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はいかなる値とも等しくない（NaN を含む）にもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はいかなる値とも等しくない（NaN を含む）にもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | 3D チャートの深さをチャート幅のパーセンテージ（20%〜2000%）で返します。 **uint16_t** を読み取ります。 |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | 3-D チャートの高さをチャート幅のパーセンテージ（5%〜500%）で指定します。 **uint16_t** を読み取ります。 |
| **uint8_t** [get_Perspective](./get_perspective/)() override | 3D チャートの視点値（視野角）を 0〜240 の範囲で返します。RightAngleAxes プロパティの値が true の場合は無視されます。 **uint8_t** を読み取ります。 |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | チャート軸が遠近法で描画されるのではなく、直角であるかどうかを判定します。言い換えれば、軸の角度がチャートの回転や高さに依存しないかを判定します。 **bool** を読み取ります。 |
| **int8_t** [get_RotationX](./get_rotationx/)() override | 3D チャートにおける X 軸（Y 方向）周りの回転角度を -90〜90 度の範囲で返します。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007+ の "Y Rotation" オプションに対応しています。 **int8_t** を読み取ります。 |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | 3D チャートにおける Y 軸（X 方向）周りの回転角度を 0〜360 度の範囲で返します。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007+ の "X Rotation" オプションに対応しています。 **uint16_t** を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | 3D チャートの深さをチャート幅のパーセンテージ（20%〜2000%）で設定します。**uint16_t** を書き込みます。 |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | 3-D チャートの高さをチャート幅のパーセンテージ（5%〜500%）で指定します。**uint16_t** を書き込みます。 |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | 3D チャートの視点値（視野角）を 0〜240 の範囲で設定します。RightAngleAxes プロパティが true の場合は無視されます。**uint8_t** を書き込みます。 |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | チャート軸が遠近法で描画されるのではなく、直角であるかどうかを判定します。言い換えれば、軸の角度がチャートの回転や高さに依存しないかを判定します。**bool** を書き込みます。 |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | 3D チャートにおける X 軸（Y 方向）周りの回転角度を -90〜90 度の範囲で設定します。このプロパティは ECMA-376 の 21.2.2.157 rotX（X Rotation）項目および PowerPoint 2007+ の "Y Rotation" オプションに対応しています。**int8_t** を書き込みます。 |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | 3D チャートにおける Y 軸（X 方向）周りの回転角度を 0〜360 度の範囲で設定します。このプロパティは ECMA-376 の 21.2.2.158 rotY（Y Rotation）項目および PowerPoint 2007+ の "X Rotation" オプションに対応しています。**uint16_t** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IRotation3D](../irotation3d/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)