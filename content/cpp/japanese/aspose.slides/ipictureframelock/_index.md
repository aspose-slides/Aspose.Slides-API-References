---
title: IPictureFrameLock
second_title: Aspose.Slides for C++ API リファレンス
description: 親 PictureFrameEx 上でどの操作が無効になっているかを決定します。
type: docs
weight: 3264
url: /ja/aspose.slides/ipictureframelock/
---
## IPictureFrameLock クラス


Determines which operations are disabled on the parent PictureFrameEx.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN 含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN 含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | 調整値の変更が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | 矢じりの変更が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | サイズ変更時に形状がアスペクト比を保持する必要があるかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | 画像の切り抜きが禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | この形状の輪郭の直接変更が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | この形状をグループに追加することが禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | すべてのロックフラグが無効な場合に true を返します。読み取り専用 **bool**。 |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | この形状の移動が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | この形状の回転角度の変更が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | この形状の選択が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | 形状タイプの変更が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | この形状のサイズ変更が禁止されているかどうかを判断します。**bool** を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | 調整値の変更が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | 矢じりの変更が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | サイズ変更時に形状がアスペクト比を保持する必要があるかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | 画像の切り抜きが禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | この形状の輪郭の直接変更が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | この形状をグループに追加することが禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | この形状の移動が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | この形状の回転角度の変更が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | この形状の選択が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | 形状タイプの変更が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | この形状のサイズ変更が禁止されているかどうかを判断します。**bool** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタや ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [IBaseShapeLock](../ibaseshapelock/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)