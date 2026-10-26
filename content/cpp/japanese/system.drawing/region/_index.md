---
title: Region
second_title: Aspose.Slides for C++ API リファレンス
description: "グラフィックシェイプの内部を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 261
url: /ja/system.drawing/region/
---
## Region クラス

グラフィックシェイプの内部を表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class Region : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | 現在のオブジェクトのコピーを返します。 |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域のうち、この領域と交差しない部分に置き換えます。 |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域のうち、この領域と交差しない部分に置き換えます。 |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 現在のオブジェクトが表す領域を、指定されたパスで定義された領域のうち、この領域と交差しない部分に置き換えます。 |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 現在のオブジェクトが表す領域を、指定された領域のうち、この領域と交差しない部分に置き換えます。 |
| void [Dispose](./dispose/)() | 現在のオブジェクトが取得したすべてのオペレーティングシステムリソースを解放します。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 指定された描画面上で、指定された領域が現在のオブジェクトが表す領域と同一かどうかを判定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域を除外した結果に置き換えます。 |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域を除外した結果に置き換えます。 |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 現在のオブジェクトが表す領域を、指定されたパスで定義された領域を除外した結果に置き換えます。 |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 現在のオブジェクトが表す領域を、指定された領域を除外した結果に置き換えます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | [Graphics](../graphics/) オブジェクトの描画面上でこの [Region](./) を囲む矩形を表す [RectangleF](../rectanglef/) 構造体を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造体を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | 現在のオブジェクトが表す領域を定義するデータを含む RegionData オブジェクトを返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | 指定された行列変換が適用された後のこの [Region](./) を近似する [RectangleF](../rectanglef/) 構造体の配列を返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域との交差結果に置き換えます。 |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域との交差結果に置き換えます。 |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 現在のオブジェクトが表す領域を、指定されたパスで定義された領域との交差結果に置き換えます。 |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 現在のオブジェクトが表す領域を、指定された領域との交差結果に置き換えます。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 指定された描画面上で、現在のオブジェクトが表す領域が空の内部を持つかどうかを判定します。 |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 指定された描画面上で、現在のオブジェクトが表す領域が無限の内部を持つかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | 指定された点が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | 指定された点が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | 指定された矩形の任意の部分が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | 指定された矩形の任意の部分が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 指定されたグラフィックスを使用して、指定された点が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 指定されたグラフィックスを使用して、指定された点が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 指定されたグラフィックスを使用して、指定された矩形の任意の部分が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 指定されたグラフィックスを使用して、指定された矩形の任意の部分が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | 指定された点が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 指定されたグラフィックスを使用して、指定された点が現在のオブジェクトが表す領域に含まれているかどうかを判定します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| void [MakeEmpty](./makeempty/)() | 現在のオブジェクトを空の内部に初期化します。 |
| void [MakeInfinite](./makeinfinite/)() | この領域オブジェクトを無限の内部に初期化します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
|  [Region](./region/)() | [Region](./) クラスの新しいインスタンスを構築します。 |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | 指定された矩形で定義された領域を表す [Region](./) クラスの新しいインスタンスを構築します。 |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | 指定された矩形で定義された領域を表す [Region](./) クラスの新しいインスタンスを構築します。 |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 指定されたパスで定義された領域を表す [Region](./) クラスの新しいインスタンスを構築します。 |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | 指定された RegionData オブジェクトで定義された領域を表す [Region](./) クラスの新しいインスタンスを構築します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することが可能です。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 指定された行列でこの領域を変換します。 |
| void [Transform](./transform/)(const SkMatrix\&) | 指定された行列でこの領域を変換します。 |
| void [Translate](./translate/)(int, int) | 領域の座標を指定された量だけ移動します。 |
| void [Translate](./translate/)(**float**, **float**) | 領域の座標を指定された量だけ移動します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域との合成結果に置き換えます。 |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域との合成結果に置き換えます。 |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 現在のオブジェクトが表す領域を、指定されたパスで定義された領域との合成結果に置き換えます。 |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 現在のオブジェクトが表す領域を、指定された領域との合成結果に置き換えます。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域と交差しない部分に置き換えます。 |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | 現在のオブジェクトが表す領域を、指定された矩形で定義された領域と交差しない部分に置き換えます。 |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 現在のオブジェクトが表す領域を、指定されたパスで定義された領域と交差しない部分に置き換えます。 |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 現在のオブジェクトが表す領域を、指定された領域と交差しない部分に置き換えます。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
| virtual  [~Region](./~region/)() | デストラクタです。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)