---
title: GraphicsPath
second_title: Aspose.Slides for C++ API リファレンス
description: "接続された直線と曲線の集合を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上でこの型のインスタンスを作成したり、operator new を使用したりしないでください。そうすると実行時エラーやアサーション障害が発生します。このクラスは必ず System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡してください。"
type: docs
weight: 66
url: /ja/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath クラス

接続された直線と曲線の集合を表します。このクラスのオブジェクトは、[System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり、operator new を使用したりしないでください。そうすると実行時エラーやアサーション失敗が発生します。このクラスは常に [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class GraphicsPath : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | 指定された楕円弧を現在のオブジェクトが表すパスに追加します。 |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | 指定された楕円弧を現在のオブジェクトが表すパスに追加します。 |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | 指定された楕円弧を現在のオブジェクトが表すパスに追加します。 |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 指定された楕円弧を現在のオブジェクトが表すパスに追加します。 |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 指定された三次ベジェ曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 指定された三次ベジェ曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | 指定された三次ベジェ曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 指定された三次ベジェ曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 現在の図に接続された三次ベジェ曲線のシーケンスを追加します。 |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 現在の図に接続された三次ベジェ曲線のシーケンスを追加します。 |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 指定された閉曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 指定された閉曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 指定された曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 指定された曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | 指定された曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | 指定された曲線を現在のオブジェクトが表すパスに追加します。 |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | 指定された楕円を現在のオブジェクトが表すパスに追加します。 |
| void [AddEllipse](./addellipse/)(int, int, int, int) | 指定された楕円を現在のオブジェクトが表すパスに追加します。 |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 指定された楕円を現在のオブジェクトが表すパスに追加します。 |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 指定された楕円を現在のオブジェクトが表すパスに追加します。 |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 指定された直線を現在のオブジェクトが表すパスに追加します。 |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 指定された直線を現在のオブジェクトが表すパスに追加します。 |
| void [AddLine](./addline/)(int, int, int, int) | 指定された直線を現在のオブジェクトが表すパスに追加します。 |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | 指定された直線を現在のオブジェクトが表すパスに追加します。 |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 現在のオブジェクトが表すパスに接続された線分の系列を追加します。 |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 現在のオブジェクトが表すパスに接続された線分の系列を追加します。 |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | 指定されたパスを現在のオブジェクトが表すパスに追加します。 |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | 指定された円グラフ形状のアウトラインを現在のオブジェクトが表すパスに追加します。 |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | 指定された円グラフ形状のアウトラインを現在のオブジェクトが表すパスに追加します。 |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 指定された円グラフ形状のアウトラインを現在のオブジェクトが表すパスに追加します。 |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 指定された多角形を現在のオブジェクトが表すパスに追加します。 |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 指定された多角形を現在のオブジェクトが表すパスに追加します。 |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 指定された矩形を現在のオブジェクトが表すパスに追加します。 |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 指定された矩形を現在のオブジェクトが表すパスに追加します。 |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | 現在のオブジェクトが表すパスに矩形の系列を追加します。 |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | 現在のオブジェクトが表すパスに矩形の系列を追加します。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 指定された文字列を現在のオブジェクトが表すパスに追加します。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 指定された文字列を現在のオブジェクトが表すパスに追加します。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 指定された文字列を現在のオブジェクトが表すパスに追加します。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 指定された文字列を現在のオブジェクトが表すパスに追加します。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | 現在のオブジェクトのコピーを作成します。 |
| void [CloseAllFigures](./closeallfigures/)() | すべての開いている図形を閉じて、新しい図形を開始します。 |
| void [CloseFigure](./closefigure/)() | 現在の図形を閉じて、新しい図形を開始します。 |
| void [Dispose](./dispose/)() | 現在のオブジェクトが取得したすべてのオペレーティングシステムリソースを解放します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみで使用されます。 |
| void [Flatten](./flatten/)() | パス内の各曲線を接続された直線の系列に変換して平坦化します。平坦度の値は 0.25 が使用されます。 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | パス内の各曲線を接続された直線の系列に変換して平坦化します。平坦度の値は 0.25 が使用されます。 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | パス内の各曲線を接続された直線の系列に変換して平坦化します。 |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | 現在のオブジェクトの塗りつぶしモードを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | 現在のオブジェクトが表すパスを構成する点とそのタイプを含む [PathData](../pathdata/) オブジェクトを返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | 現在のオブジェクトが表すパスを構成する点を含む配列を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | 現在のオブジェクトが表すパスを構成する点のタイプを示す値を含む配列を返します。 |
| int [get_PointCount](./get_pointcount/)() const | 現在のオブジェクトが表すパスの点の数を返します。 |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | 指定された行列で変換されたときに、現在のオブジェクトが表すパスを囲む矩形を表す [RectangleF](../../system.drawing/rectanglef/) オブジェクトを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | 現在のオブジェクトが表すパスに含まれる図形のタイプを示す Detail::FigureType 値のビット単位の組み合わせを返します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | パスの最後の点を表す [PointF](../../system.drawing/pointf/) オブジェクトを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | 指定された塗りつぶしモードで [GraphicsPath](./) クラスの新しいインスタンスを構築します。 |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 指定されたパスを表す [GraphicsPath](./) オブジェクトの新しいインスタンスを構築します。 |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 指定されたパスを表す [GraphicsPath](./) オブジェクトの新しいインスタンスを構築します。 |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 指定された [Pen](../../system.drawing/pen/) で描画されたこの [GraphicsPath](./) のアウトライン内（下）に指定された点が含まれるかどうかを示します。実装されていません。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | 指定された点が現在のオブジェクトが表すパス内に含まれるかどうかを判定します。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 指定された点が現在のオブジェクトが表すパス内に含まれるかどうかを判定します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [Reset](./reset/)() | すべての点を削除してパスを空にします。 |
| void [Reverse](./reverse/)() | この [GraphicsPath](./) の PathPoints 配列内の点の順序を逆にします。 |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | 現在のオブジェクトの塗りつぶしモードを設定します。 |
| void [SetMarkers](./setmarkers/)() | 未実装です。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [StartFigure](./startfigure/)() | 新しい図形を開始します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | 指定された変換行列を適用して、現在のオブジェクトが表すパスを変換します。 |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | このパスを元のパスのアウトラインで置き換えます。 |
|  [~GraphicsPath](./~graphicspath/)() | デストラクタです。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Drawing::Drawing2D](../)
* ライブラリ [Aspose.Slides](../../)