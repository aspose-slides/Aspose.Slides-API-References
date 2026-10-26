---
title: GroupCollectionPtr
second_title: Aspose.Slides for C++ API リファレンス
description: グループコレクションポインタ。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。
type: docs
weight: 53
url: /ja/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr クラス


[Group](../group/) コレクションポインタ。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 基底コレクションの [begin()](../../system/smartptr/begin/) メソッドへのアクセサ。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| auto [begin](../../system/smartptr/begin/)() const | 基底コレクションの [begin()](../../system/smartptr/begin/) メソッドへのアクセサ。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | ポインタをその型自身にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 基底コレクションの [cbegin()](../../system/smartptr/cbegin/) メソッドへのアクセサ。SmartPtr_ が [cbegin()](../../system/smartptr/cbegin/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| auto [cend](../../system/smartptr/cend/)() const | 基底コレクションの [cend()](../../system/smartptr/cend/) メソッドへのアクセサ。SmartPtr_ が [cend()](../../system/smartptr/cend/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | ポインタが指すオブジェクトに const_cast を適用して別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | ポインタが指すオブジェクトに dynamic_cast を適用して別の型にキャストします。 |
| auto [end](../../system/smartptr/end/)() | 基底コレクションの [end()](../../system/smartptr/end/) メソッドへのアクセサ。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| auto [end](../../system/smartptr/end/)() const | 基底コレクションの [end()](../../system/smartptr/end/) メソッドへのアクセサ。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 指し示すオブジェクトを取得します。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 指し示すオブジェクトを取得しますが、ポインタが共有モードであることをアサートします。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 参照されたオブジェクトに対して存在する共有ポインタの数（現在のポインタも含む）を取得します。現在のポインタが共有モードであることをアサートします。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 指し示すオブジェクトの [GetHashCode()](../../system/smartptr/gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 現在参照されているオブジェクト（存在すれば）を取得し、存在しなければ例外をスローします。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 指し示すオブジェクト（存在すれば）または nullptr を取得します。[get()](../../system/smartptr/get/) と同じです。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 参照されたオブジェクトを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 指し示すオブジェクト（存在すれば）または nullptr を取得します。[get()](../../system/smartptr/get/) と同じです。 |
|  [GroupCollectionPtr](./groupcollectionptr/)() | ヌルポインタコンストラクタです。 |
|  [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | 型変換コンストラクタです。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 指し示すオブジェクトが特定の型またはその子型であるかどうかをチェックします。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ポインタが所有しているオブジェクトとは別のオブジェクトを指しているかどうかをチェックします（エイリアシングコンストラクタで作成されたもの）。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ポインタが共有モードかどうかをチェックします。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ポインタが弱参照モードかどうかをチェックします。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ポインタが null でないかどうかをチェックします。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ポインタが null かどうかをチェックします。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 指し示すオブジェクトへの参照を取得します。ポインタが null でないことをアサートします。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 参照されたオブジェクトのメンバーにアクセスできます。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較のセマンティクスを提供します。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較のセマンティクスを提供します。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) オブジェクトにムーブ代入します。x は使用できなくなります。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) オブジェクトにコピー代入します。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) オブジェクトにコピー代入します。必要な型変換を行います。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 生ポインタを [SmartPtr](../../system/smartptr/) オブジェクトに割り当てます。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ポインタの値を nullptr に設定します。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ポインタが nullptr を指しているかどうかをチェックします。 |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(size_t) const | [Group](../group/) アクセサ。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成されたもの）をポインタから除去し、指し示す同じオブジェクトを（共有の場合は管理し、弱参照の場合は追跡する）ことを保証します。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 指し示すオブジェクトを設定します。 |
| void [reset](../../system/smartptr/reset/)() | ポインタを nullptr を指すようにします。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ポインタモードを設定します。参照オブジェクトの参照カウントを変更する可能性があります。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 指し示すオブジェクト（存在すれば）に SetTemplateWeakPtr() メソッドを呼び出します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの null ポインタ [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](../../system/smartptr/) を作成するか、生ポインタを [SmartPtr](../../system/smartptr/) に変換します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。両方のポインタはその後同じオブジェクトを指します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。両方のポインタはその後同じオブジェクトを指します。許可されていれば型変換を行います。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをムーブ構築します。実質的に、両方が同じモードであれば二つのポインタを入れ替えます。呼び出し後、x は使用できなくなる可能性があります。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 参照された配列の型を別の型の新しい配列を作成して変換します。C# で配列型キャストがサポートされていない場合に有用です。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 空の配列を初期化します。C# のコード構文を変換する際に使用されます。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) を構築します。このオブジェクトは ptr の初期値と所有情報を共有しますが、無関係で管理されていないポインタ p を保持します。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | ポインタが指すオブジェクトに static_cast を適用して別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 任意のポインタ型を [Object](../../system/object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ 型の [System::TypeInfo](../../system/typeinfo/) オブジェクトを取得するショートカットです。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) オブジェクトを破棄します。必要に応じて、指し示すオブジェクトの参照カウンタを減少させ、オブジェクトを削除します。 |

## 参照

* クラス [SmartPtr](../../system/smartptr/)
* 名前空間 [System::Text::RegularExpressions](../)
* ライブラリ [Aspose.Slides](../../)