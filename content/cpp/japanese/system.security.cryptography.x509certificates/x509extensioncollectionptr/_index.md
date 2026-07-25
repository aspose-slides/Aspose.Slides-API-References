---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides for C++ API リファレンス
description: X509 拡張機能のコレクションへのポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数に値渡しまたは const 参照で渡すべきです。
type: docs
weight: 170
url: /ja/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr クラス

X509 拡張機能のコレクションへのポインタです。この型は、他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数に値渡しまたは const 参照で渡すべきです。

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 基底コレクションの [begin()](../../system/smartptr/begin/) メソッドへのアクセサです。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化タイプの場合にのみコンパイルされます。 |
| auto [begin](../../system/smartptr/begin/)() const | 基底コレクションの [begin()](../../system/smartptr/begin/) メソッドへのアクセサです。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化タイプの場合にのみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | ポインタをその型自身にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 基底コレクションの [cbegin()](../../system/smartptr/cbegin/) メソッドへのアクセサです。SmartPtr_ が [cbegin()](../../system/smartptr/cbegin/) メソッドを持つ特殊化タイプの場合にのみコンパイルされます。 |
| auto [cend](../../system/smartptr/cend/)() const | 基底コレクションの [cend()](../../system/smartptr/cend/) メソッドへのアクセサです。SmartPtr_ が [cend()](../../system/smartptr/cend/) メソッドを持つ特殊化タイプの場合にのみコンパイルされます。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 指向オブジェクトに const_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 指向オブジェクトに dynamic_cast を使用してポインタを別の型にキャストします。 |
| auto [end](../../system/smartptr/end/)() | 基底コレクションの [end()](../../system/smartptr/end/) メソッドへのアクセサです。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化タイプの場合にのみコンパイルされます。 |
| auto [end](../../system/smartptr/end/)() const | 基底コレクションの [end()](../../system/smartptr/end/) メソッドへのアクセサです。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化タイプの場合にのみコンパイルされます。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 指向オブジェクトを取得します。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 指向オブジェクトを取得しますが、ポインタが共有モードであることをアサートします。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 参照オブジェクトに対して存在する共有ポインタの数（現在のポインタを含む）を取得します。ポインタが共有モードであることをアサートします。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 指向オブジェクトで [GetHashCode()](../../system/smartptr/gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 現在参照されているオブジェクト（存在する場合）を取得します。存在しない場合は例外をスローします。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 指向オブジェクトを取得します（存在する場合）。存在しない場合は nullptr を返します。[get()](../../system/smartptr/get/) と同等です。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 参照オブジェクトを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 指向オブジェクトを取得します（存在する場合）。存在しない場合は nullptr を返します。[get()](../../system/smartptr/get/) と同等です。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 指向オブジェクトが特定の型またはその子型かどうかをチェックします。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ポインタが所有オブジェクト（エイリアシングコンストラクタで作成されたもの）以外の別のオブジェクトを指しているかどうかをチェックします。 |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ポインタが共有モードかどうかをチェックします。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ポインタが弱参照モードかどうかをチェックします。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ポインタが null でないかをチェックします。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ポインタが null かどうかをチェックします。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 指向オブジェクトへの参照を取得します。ポインタが null でないことをアサートします。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 参照オブジェクトのメンバーへアクセスできます。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) オブジェクトに対してムーブ代入を行います。x は使用不能になります。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) オブジェクトに対してコピー代入を行います。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) オブジェクトに対してコピー代入を行います。必要な型変換を行います。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 生ポインタを [SmartPtr](../../system/smartptr/) オブジェクトに割り当てます。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ポインタの値を nullptr に設定します。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ポインタが nullptr を指しているかどうかをチェックします。 |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | アクセサです。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成されたもの）をポインタから削除し、共有の場合は管理し、弱参照の場合は追跡している同じオブジェクトを指すようにします。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 指向オブジェクトを設定します。 |
| void [reset](../../system/smartptr/reset/)() | ポインタを nullptr に設定します。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ポインタモードを設定します。参照オブジェクトの参照カウントが変更される可能性があります。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 指向オブジェクト（存在する場合）で SetTemplateWeakPtr() メソッドを呼び出します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの null ポインタ [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](../../system/smartptr/) を作成するか、生ポインタを [SmartPtr](../../system/smartptr/) に変換します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。構築後、両方のポインタは同じオブジェクトを指します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。構築後、両方のポインタは同じオブジェクトを指します。許可されている場合は型変換を行います。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをムーブ構築します。両ポインタが同一モードの場合に実質的にポインタを入れ替えます。呼び出し後、x は使用不能になる可能性があります。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 異なる型の新しい配列を作成して参照配列の型を変換します。C# でサポートされていない配列型キャストを C++ で実現したい場合に有用です。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 空の配列を初期化します。C# の一部コード構文の変換に使用されます。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 初期の ptr の所有情報を共有しつつ、無関係で管理されていないポインタ p を保持する [SmartPtr](../../system/smartptr/) を構築します。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 指向オブジェクトに static_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 任意のポインタ型を [Object](../../system/object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) オブジェクトへのショートカットを取得します（Pointee_ 型用）。 |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | null ポインタコンストラクタです。 |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | コンストラクタです。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) オブジェクトを破棄します。必要に応じて、指向オブジェクトの参照カウントを減らし、オブジェクトを削除します。 |

## 参照

* クラス [SmartPtr](../../system/smartptr/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../)
* ライブラリ [Aspose.Slides](../../)