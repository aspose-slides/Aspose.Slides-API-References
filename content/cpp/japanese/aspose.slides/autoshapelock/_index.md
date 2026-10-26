---
title: AutoShapeLock
second_title: Aspose.Slides for C++ API リファレンス
description: 親 AutoshapeEx で無効化されている操作を決定します。
type: docs
weight: 79
url: /ja/aspose.slides/autoshapelock/
---
## AutoShapeLock クラス


Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | 調整値の変更が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | 矢じりの変更が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | リサイズ時に形状がアスペクト比を保持しなければならないかどうかを判定します。読み取り **bool**。 |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | この形状の輪郭の直接変更が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | この形状をグループに追加することが禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | すべてのロックフラグが無効な場合に true を返します。読み取り専用 **bool**。 |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | この形状を移動することが禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | この形状の回転角度の変更が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | この形状の選択が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | 形状タイプの変更が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | この形状のサイズ変更が禁止されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_TextLocked](./get_textlocked/)() override | テキストの編集が禁止されているかどうかを判定します。読み取り **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | 調整値の変更が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | 矢じりの変更が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | リサイズ時に形状がアスペクト比を保持しなければならないかどうかを判定します。書き込み **bool**。 |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | この形状の輪郭の直接変更が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | この形状をグループに追加することが禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | この形状を移動することが禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | この形状の回転角度の変更が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | この形状の選択が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | 形状タイプの変更が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | この形状のサイズ変更が禁止されているかどうかを判定します。書き込み **bool**。 |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | テキストの編集が禁止されているかどうかを判定します。書き込み **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [BaseShapeLock](../baseshapelock/)
* クラス [IAutoShapeLock](../iautoshapelock/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)