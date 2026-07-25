---
title: ShapeFrame
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプフレームのプロパティを表します。
type: docs
weight: 5136
url: /ja/aspose.slides/shapeframe/
---
## ShapeFrame クラス

シェイプフレームのプロパティを表します。

```cpp
class ShapeFrame : public Aspose::Slides::IShapeFrame
```

## メソッド

| Method | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | クローン作成 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [CloneT](./clonet/)() override | クローン作成。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ShapeFrame](./)\>) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **float** [get_CenterX](./get_centerx/)() override | フレームの中心の X 座標を返します。読み取り専用 **float**。 |
| **float** [get_CenterY](./get_centery/)() override | フレームの中心の Y 座標を返します。読み取り専用 **float**。 |
| [NullableBool](../nullablebool/) [get_FlipH](./get_fliph/)() override | フレームが水平方向に反転しているかどうかを判定します。読み取り専用 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_FlipV](./get_flipv/)() override | フレームが垂直方向に反転しているかどうかを判定します。読み取り専用 [NullableBool](../nullablebool/)。 |
| **float** [get_Height](./get_height/)() override | フレームの高さを返します。読み取り専用 **float**。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() override | フレームの座標を返します。読み取り専用 [System::Drawing::RectangleF](../../system.drawing/rectanglef/)。 |
| **float** [get_Rotation](./get_rotation/)() override | フレームが Z 軸周りに回転した度数を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り専用 **float**。 |
| **float** [get_Width](./get_width/)() override | フレームの幅を返します。読み取り専用 **float**。 |
| **float** [get_X](./get_x/)() override | フレーム左上隅の X 座標を返します。読み取り専用 **float**。 |
| **float** [get_Y](./get_y/)() override | フレーム左上隅の Y 座標を返します。読み取り専用 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | このオブジェクトのハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピー コンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化で、文字列と nullptr のケースに対応します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化で、文字列のケースに対応します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
|  [ShapeFrame](./shapeframe/)(**float**, **float**, **float**, **float**, [NullableBool](../nullablebool/), [NullableBool](../nullablebool/), **float**) | 新しいシェイプフレームのプロパティを作成します。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、値を返します。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタム オブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IShapeFrame](../ishapeframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)