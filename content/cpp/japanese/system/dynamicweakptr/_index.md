---
title: DynamicWeakPtr
second_title: Aspose.Slides for C++ API リファレンス
description: 格納されたオブジェクトのテンプレート引数のポインターモードを追跡し、各代入後にそれらを更新するスマートポインタクラスです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡すべきです。
type: docs
weight: 781
url: /ja/system/dynamicweakptr/
---
## DynamicWeakPtr クラス

格納されたオブジェクトのテンプレート引数のポインターモードを追跡し、各代入後にそれらを更新するスマートポインタクラスです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡すべきです。

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Pointee | 型。 |
| trunkMode | スマートポインタ自体のモードで、shared または weak です。 |
| weakLeafs | 格納型のテンプレート引数のインデックスで、weak ポインタモードに設定すべきものです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| auto [begin](../smartptr/begin/)() | 基底コレクションの [begin()](../smartptr/begin/) メソッドへのアクセサです。SmartPtr_ が [begin()](../smartptr/begin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [begin](../smartptr/begin/)() const | 基底コレクションの [begin()](../smartptr/begin/) メソッドへのアクセサです。SmartPtr_ が [begin()](../smartptr/begin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | ポインタをその自身の型にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | static_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](../smartptr/cbegin/)() const | 基底コレクションの [cbegin()](../smartptr/cbegin/) メソッドへのアクセサです。SmartPtr_ が [cbegin()](../smartptr/cbegin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [cend](../smartptr/cend/)() const | 基底コレクションの [cend()](../smartptr/cend/) メソッドへのアクセサです。SmartPtr_ が [cend()](../smartptr/cend/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 指されているオブジェクトに const_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 指されているオブジェクトに dynamic_cast を使用してポインタを別の型にキャストします。 |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | null スマートポインタを作成します。 |
| [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | 指定されたオブジェクトを指すスマートポインタを作成します。 |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | スマートポインタをコピー構築します。 |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | スマートポインタをコピー構築します。 |
| [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | スマートポインタをコピー構築します。 |
| [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | スマートポインタをムーブ構築します。 |
| auto [end](../smartptr/end/)() | 基底コレクションの [end()](../smartptr/end/) メソッドへのアクセサです。SmartPtr_ が [end()](../smartptr/end/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [end](../smartptr/end/)() const | 基底コレクションの [end()](../smartptr/end/) メソッドへのアクセサです。SmartPtr_ が [end()](../smartptr/end/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 指されているオブジェクトを取得します。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 指されているオブジェクトを取得しますが、ポインタが shared モードであることをアサートします。 |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 参照されているオブジェクトに存在する shared ポインタの数（現在のポインタを含む）を取得します。現在のポインタが shared モードであることをアサートします。 |
| int [GetHashCode](../smartptr/gethashcode/)() const | 指されているオブジェクトで [GetHashCode()](../smartptr/gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 現在参照されているオブジェクト（存在する場合）を取得し、存在しない場合は例外をスローします。 |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 指されているオブジェクト（存在する場合）を取得し、存在しない場合は nullptr を返します。[get()](../smartptr/get/) と同等です。 |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 参照されているオブジェクトを取得します。 |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 指されているオブジェクト（存在する場合）を取得し、存在しない場合は nullptr を返します。[get()](../smartptr/get/) と同等です。 |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 指されているオブジェクトが特定の型またはその子型かどうかを確認します。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | ポインタが所有しているオブジェクト以外（エイリアシングコンストラクタで作成された）を指しているかどうかを確認します。 |
| **bool** [IsShared](../smartptr/isshared/)() const | ポインタが shared モードであるかどうかを確認します。 |
| **bool** [IsWeak](../smartptr/isweak/)() const | ポインタが weak モードであるかどうかを確認します。 |
| explicit  [operator bool](../smartptr/operator_bool/)() const | ポインタが null でないかどうかを確認します。 |
| **bool** [operator!](../smartptr/operator_not/)() const | ポインタが null かどうかを確認します。 |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 指されているオブジェクトへの参照を取得します。ポインタが null でないことをアサートします。 |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 参照オブジェクトのメンバーにアクセスできます。 |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | スマートポインタにムーブ代入します。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | スマートポインタにコピー代入します。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | スマートポインタにコピー代入します。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | スマートポインタに代入します。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | スマートポインタを null に設定します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | スマートポインタが null かどうかを確認します。 |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成された）をポインタから削除し、指すオブジェクトを（shared の場合は管理し、weak の場合は追跡）同じままにします。 |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 指されているオブジェクトを設定します。 |
| void [reset](../smartptr/reset/)() | ポインタを nullptr を指すようにします。 |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | ポインタモードを設定します。参照対象オブジェクトの参照カウントを変更する可能性があります。 |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 指されているオブジェクト（存在する場合）で SetTemplateWeakPtr() メソッドを呼び出します。 |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 必要なモードの [SmartPtr](../smartptr/) オブジェクトを作成します。 |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 必要なモードの null ポインタ [SmartPtr](../smartptr/) オブジェクトを作成します。 |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](../smartptr/) を作成するか、raw ポインタを [SmartPtr](../smartptr/) に変換します。 |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) オブジェクトをコピー構築します。その後、両方のポインタは同じオブジェクトを指します。 |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) オブジェクトをコピー構築します。その後、両方のポインタは同じオブジェクトを指します。許可されていれば型変換も行います。 |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) オブジェクトをムーブ構築します。実質的に、両方が同じモードであれば二つのポインタを交換します。呼び出し後、x は使用できない可能性があります。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 参照配列の型を別の型の新しい配列を作成して変換します。C# で配列型キャストが可能だが C++ ではサポートされていない場合に有用です。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | 空の配列を初期化します。いくつかの C# コード構文の変換に使用されます。 |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ptr の初期値と所有権情報を共有しながら、無関係で管理されていないポインタ p を保持する [SmartPtr](../smartptr/) を構築します。 |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 指されているオブジェクトに static_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 任意のポインタ型を [Object](../object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pointee_ 型の [System::TypeInfo](../typeinfo/) オブジェクトを取得するショートカットです。 |
| [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) オブジェクトを破棄します。必要に応じて、指されているオブジェクトの参照カウントを減らし、オブジェクトを削除します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) の基底クラスエイリアスです。 |
| [DynamicWeakPtr_](./dynamicweakptr_/) | 自身の型エイリアスです。 |
| [Pointee_](./pointee_/) | 指されている型です。 |

## 参照

* クラス [SmartPtr](../smartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)