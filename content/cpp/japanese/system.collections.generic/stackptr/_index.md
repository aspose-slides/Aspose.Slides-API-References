---
title: StackPtr
second_title: Aspose.Slides for C++ API リファレンス
description: スタックポインタ。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡す必要があります。
type: docs
weight: 612
url: /ja/system.collections.generic/stackptr/
---
## StackPtr クラス

[Stack](../stack/) ポインタ。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡す必要があります。

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 要素型。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | アンダーライングコレクションの [begin()](../../system/smartptr/begin/) メソッドへのアクセサーです。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化型の場合にのみコンパイルされます。 |
| auto [begin](../../system/smartptr/begin/)() const | アンダーライングコレクションの [begin()](../../system/smartptr/begin/) メソッドへのアクセサーです。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化型の場合にのみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | ポインタをその型自身にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static\_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic\_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic\_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | アンダーライングコレクションの [cbegin()](../../system/smartptr/cbegin/) メソッドへのアクセサーです。SmartPtr_ が [cbegin()](../../system/smartptr/cbegin/) メソッドを持つ特殊化型の場合にのみコンパイルされます。 |
| auto [cend](../../system/smartptr/cend/)() const | アンダーライングコレクションの [cend()](../../system/smartptr/cend/) メソッドへのアクセサーです。SmartPtr_ が [cend()](../../system/smartptr/cend/) メソッドを持つ特殊化型の場合にのみコンパイルされます。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 指されたオブジェクトに const\_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 指されたオブジェクトに dynamic\_cast を使用してポインタを別の型にキャストします。 |
| auto [end](../../system/smartptr/end/)() | アンダーライングコレクションの [end()](../../system/smartptr/end/) メソッドへのアクセサーです。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化型の場合にのみコンパイルされます。 |
| auto [end](../../system/smartptr/end/)() const | アンダーライングコレクションの [end()](../../system/smartptr/end/) メソッドへのアクセサーです。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化型の場合にのみコンパイルされます。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 指されたオブジェクトを取得します。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 指されたオブジェクトを取得します。ただし、ポインタが共有モードであることをアサートします。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 参照対象オブジェクトに存在する共有ポインタ数（現在のポインタを含む）を取得します。現在のポインタが共有モードであることをアサートします。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 指されたオブジェクトの [GetHashCode()](../../system/smartptr/gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 現在参照されているオブジェクト（存在すれば）を取得し、存在しない場合は例外をスローします。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 指されたオブジェクト（存在すれば）を取得し、存在しない場合は nullptr を返します。[get()](../../system/smartptr/get/) と同等です。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 参照されているオブジェクトを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 指されたオブジェクト（存在すれば）を取得し、存在しない場合は nullptr を返します。[get()](../../system/smartptr/get/) と同等です。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 指されたオブジェクトが特定の型またはその子孫型であるかをチェックします。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ポインタが所有しているオブジェクト以外（エイリアシングコンストラクタで作成された）を指しているかをチェックします。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ポインタが共有モードかどうかをチェックします。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ポインタがウィークモードかどうかをチェックします。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ポインタが null でないかをチェックします。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ポインタが null かどうかをチェックします。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 指されたオブジェクトへの参照を取得します。ポインタが null でないことをアサートします。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 参照オブジェクトのメンバーにアクセスできます。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較のセマンティクスを提供します。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較のセマンティクスを提供します。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) オブジェクトをムーブ代入します。x は使用不能になります。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー代入します。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー代入します。必要な型変換を行います。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | raw ポインタを [SmartPtr](../../system/smartptr/) オブジェクトに割り当てます。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ポインタの値を nullptr に設定します。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ポインタが nullptr を指しているかをチェックします。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成された）をポインタから除去し、指すオブジェクトが同じであることを（共有の場合は管理し、ウィークの場合は追跡し）保証します。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 指されたオブジェクトを設定します。 |
| void [reset](../../system/smartptr/reset/)() | ポインタを nullptr に設定します。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ポインタモードを設定します。参照オブジェクトの参照カウントが変更される可能性があります。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 指されたオブジェクト（存在すれば）の SetTemplateWeakPtr() メソッドを呼び出します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの null ポインタ [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](../../system/smartptr/) を作成するか、raw ポインタを [SmartPtr](../../system/smartptr/) に変換します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。その結果、両方のポインタは同じオブジェクトを指します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。その結果、両方のポインタは同じオブジェクトを指します。許可されていれば型変換を行います。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをムーブ構築します。実質的に、両ポインタが同じモードであればそれらを交換します。呼び出し後、x は使用不能になる可能性があります。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 参照配列の型を別の型の新しい配列を作成して変換します。C# でサポートされている配列型キャストが C++ で未サポートの場合に有用です。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 空の配列を初期化します。いくつかの C# コード構文の変換に使用されます。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ptr の初期値と所有権情報を共有しつつ、無関係で管理されていないポインタ p を保持する [SmartPtr](../../system/smartptr/) を構築します。 |
|  [StackPtr](./stackptr/)() | null ポインタを構築します。 |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | 特定のスタックを参照するポインタを構築します。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 指されたオブジェクトに static\_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 任意のポインタ型を [Object](../../system/object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ 型の [System::TypeInfo](../../system/typeinfo/) オブジェクトを取得するショートカットです。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) オブジェクトを破棄します。必要に応じて、指されたオブジェクトの参照カウンタを減らし、オブジェクトを削除します。 |

## 参照

* クラス [SmartPtr](../../system/smartptr/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)