---
title: Matrix
second_title: Aspose.Slides for C++ API リファレンス
description: "変換操作を定義する 3x3 行列を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこのタイプのインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。"
type: docs
weight: 118
url: /ja/system.drawing.drawing2d/matrix/
---
## Matrix クラス

変換操作を定義する 3x3 行列を表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡すようにしてください。

```cpp
class Matrix : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | 現在のオブジェクトのコピーを作成します。 |
| void [Dispose](./dispose/)() | 現在のオブジェクトが取得したすべてのオペレーティングシステムリソースを解放します。 |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | 指定されたオブジェクトが [Matrix](./) であり、かつこのオブジェクトと同一であるかをテストします。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、ここでは二つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、ここでは二つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | 行列の要素を次の順序で含む配列を返します: m11, m12, m21, m22, dx, dy。 |
| **bool** [get_IsIdentity](./get_isidentity/)() const | 現在のオブジェクトが表す行列が単位行列かどうかを判定します。 |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | 現在のオブジェクトが表す行列が逆行列可能かどうかを判定します。 |
| **float** [get_OffsetX](./get_offsetx/)() const | 現在のオブジェクトが表す行列の X 平行移動値を返します。 |
| **float** [get_OffsetY](./get_offsety/)() const | 現在のオブジェクトが表す行列の Y 平行移動値を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| void [Invert](./invert/)() | 現在のオブジェクトが表す行列を反転させます。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| [Matrix](./matrix/)() | [Matrix](./) クラスの新しいインスタンス（単位行列を表す）を構築します。 |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | [Matrix](./) クラスの新しいインスタンスを構築し、指定された値で初期化します。 |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 指定された矩形と点の配列で定義された幾何変換に対する [Matrix](./) クラスの新しいインスタンスを構築します。 |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 指定された矩形と点の配列で定義された幾何変換に対する [Matrix](./) クラスの新しいインスタンスを構築します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | 現在のオブジェクトが表す行列に、指定された行列を掛け合わせます。 |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | 現在のオブジェクトが表す行列に、指定された行列を掛け合わせます。 |
| [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [Reset](./reset/)() | 現在のオブジェクトが表す行列をリセットし、単位行列にします。 |
| void [Rotate](./rotate/)(**float**) | 現在のオブジェクトが表す行列を指定された角度だけ時計回りに回転させます。 |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | 現在のオブジェクトが表す行列を原点周りに指定された角度だけ時計回りに回転させます。 |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | 現在のオブジェクトが表す行列を指定された点の周りに指定された角度だけ時計回りに回転させます。 |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | 現在のオブジェクトが表す行列を指定された点の周りに指定された角度だけ時計回りに回転させます。 |
| void [Scale](./scale/)(**float**, **float**) | 現在のオブジェクトが表す行列に指定されたスケールベクトルを適用します。 |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 現在のオブジェクトが表す行列に指定されたスケールベクトルを適用します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Shear](./shear/)(**float**, **float**) | 現在のオブジェクトが表す行列に指定されたシアベクトルを適用します。 |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 現在のオブジェクトが表す行列に指定されたシアベクトルを適用します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表す行列で定義された幾何変換を指定された点に適用します。 |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表す行列で定義された幾何変換を指定された点に適用します。 |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 現在のオブジェクトが表す行列で定義された幾何変換を指定された点に適用します。 |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | 現在のオブジェクトが表す行列で定義された幾何変換を指定された点に適用します。 |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表す行列のスケールと回転成分のみを指定された点に適用します。 |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表す行列のスケールと回転成分のみを指定された点に適用します。 |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 現在のオブジェクトが表す行列のスケールと回転成分のみを指定された点に適用します。 |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | 現在のオブジェクトが表す行列のスケールと回転成分のみを指定された点に適用します。 |
| void [Translate](./translate/)(**float**, **float**) | 現在のオブジェクトが表す行列に指定された平行移動ベクトルを適用します。 |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 現在のオブジェクトが表す行列に指定された平行移動ベクトルを適用します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表す行列で配列内の各ベクトルを掛け合わせます。 |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表す行列で配列内の各ベクトルを掛け合わせます。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Matrix](./~matrix/)() | デストラクタです。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Drawing::Drawing2D](../)
* ライブラリ [Aspose.Slides](../../)