---
title: GroupShapeLock
second_title: Aspose.Slides for C++ APIリファレンス
description: 親 GroupShape 上で無効化されている操作を決定します。
type: docs
weight: 1210
url: /ja/aspose.slides/groupshapelock/
---
## GroupShapeLock クラス


親 [GroupShape](../groupshape/) 上で無効化されている操作を決定します。

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。この比較では、IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。この比較では、IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | リサイズ時にシェイプがアスペクト比を保持する必要があるかどうかを決定します。読み取り **bool**。 |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | このシェイプをグループに追加できないかどうかを決定します。読み取り **bool**。 |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | すべてのロックフラグが無効な場合に true を返します。読み取り専用 **bool**。 |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | このシェイプの移動が禁止されているかどうかを決定します。読み取り **bool**。 |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | このシェイプの回転角度の変更が禁止されているかどうかを決定します。読み取り **bool**。 |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | このシェイプの選択が禁止されているかどうかを決定します。読み取り **bool**。 |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | このシェイプのサイズ変更が禁止されているかどうかを決定します。読み取り **bool**。 |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | このグループシェイプの分割が禁止されているかどうかを決定します。読み取り **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しに相当します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減らします。 |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | リサイズ時にシェイプがアスペクト比を保持する必要があるかどうかを決定します。**bool** に書き込みます。 |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | このシェイプをグループに追加できないかどうかを決定します。**bool** に書き込みます。 |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | このシェイプの移動が禁止されているかどうかを決定します。**bool** に書き込みます。 |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | このシェイプの回転角度の変更が禁止されているかどうかを決定します。**bool** に書き込みます。 |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | このシェイプの選択が禁止されているかどうかを決定します。**bool** に書き込みます。 |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | このシェイプのサイズ変更が禁止されているかどうかを決定します。**bool** に書き込みます。 |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | このグループシェイプの分割が禁止されているかどうかを決定します。**bool** に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドに相当します。カスタムオブジェクトを文字列に変換することが可能です。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [BaseShapeLock](../baseshapelock/)
* クラス [IGroupShapeLock](../igroupshapelock/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)