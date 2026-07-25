---
title: WeakPtr
second_title: Aspose.Slides for C++ API リファレンス
description: "コンストラクタで自身を弱モードに設定する System::SmartPtr のサブクラスです。set_Mode() が依然としてアクセス可能であるため、このクラスのインスタンスが常に弱モードのままであることは保証されません。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡すべきです。"
type: docs
weight: 1496
url: /ja/system/weakptr/
---
## WeakPtr クラス

[System::SmartPtr](../smartptr/) のサブクラスで、構築時に自身を弱モードに設定します。[set_Mode()](../smartptr/set_mode/) が依然としてアクセス可能であるため、このクラスのインスタンスが常に弱モードのままであることは保証されません。この型は他オブジェクトの削除を管理するポインタです。スタック上に割り当て、関数に値渡しまたは const 参照で渡すべきです。

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | Pointee type. |

## メソッド

| メソッド | 説明 |
| --- | --- |
| auto [begin](../smartptr/begin/)() | [begin()](../smartptr/begin/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [begin()](../smartptr/begin/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| auto [begin](../smartptr/begin/)() const | [begin()](../smartptr/begin/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [begin()](../smartptr/begin/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | ポインタをその型にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | static\_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic\_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic\_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](../smartptr/cbegin/)() const | [cbegin()](../smartptr/cbegin/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [cbegin()](../smartptr/cbegin/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| auto [cend](../smartptr/cend/)() const | [cend()](../smartptr/cend/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [cend()](../smartptr/cend/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 指すオブジェクトに const\_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 指すオブジェクトに dynamic\_cast を使用してポインタを別の型にキャストします。 |
| auto [end](../smartptr/end/)() | [end()](../smartptr/end/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [end()](../smartptr/end/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| auto [end](../smartptr/end/)() const | [end()](../smartptr/end/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [end()](../smartptr/end/) メソッドを持つ特殊化型の場合のみコンパイルされます。 |
| **bool** [expired](./expired/)() const | 参照されたオブジェクトがすでに削除されているか確認します。 |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 指しているオブジェクトを取得します。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 指しているオブジェクトを取得しますが、ポインタが共有モードであることをアサートします。 |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 参照されたオブジェクトに存在する共有ポインタの数（現在のものを含む）を取得します。現在のポインタが共有モードであることをアサートします。 |
| [Object](../object/) * [get_weak](./get_weak/)() const | 参照されたオブジェクトを取得します。ポインタが弱モードであることをアサートします。 |
| int [GetHashCode](../smartptr/gethashcode/)() const | 指すオブジェクトで [GetHashCode()](../smartptr/gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 現在参照されているオブジェクト（存在する場合）を取得するか、例外を投げます。 |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 指すオブジェクト（存在する場合）または nullptr を取得します。[get()](../smartptr/get/) と同等です。 |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 参照されたオブジェクトを取得します。 |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 指すオブジェクト（存在する場合）または nullptr を取得します。[get()](../smartptr/get/) と同等です。 |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 指すオブジェクトが特定の型またはその子型かどうかを確認します。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | ポインタが所有しているオブジェクトとは別のオブジェクトを指しているか（エイリアシングコンストラクタで作成された場合）を確認します。 |
| **bool** [IsShared](../smartptr/isshared/)() const | ポインタが共有モードであるかを確認します。 |
| **bool** [IsWeak](../smartptr/isweak/)() const | ポインタが弱モードであるかを確認します。 |
| explicit  [operator bool](../smartptr/operator_bool/)() const | ポインタが null でないかを確認します。 |
| **bool** [operator!](../smartptr/operator_not/)() const | ポインタが null かどうかを確認します。 |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 指すオブジェクトへの参照を取得します。ポインタが null でないことをアサートします。 |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 参照されたオブジェクトのメンバーにアクセスできます。 |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | 弱ポインタに値を代入します。SmartPtr_ の特定の代入演算子を呼び出します。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | [SmartPtr](../smartptr/) オブジェクトにムーブ代入します。x は使用不能になります。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | [SmartPtr](../smartptr/) オブジェクトにコピー代入します。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | [SmartPtr](../smartptr/) オブジェクトにコピー代入します。必要な型変換を行います。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | 生ポインタを [SmartPtr](../smartptr/) オブジェクトに代入します。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | ポインタの値を nullptr に設定します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 弱ポインタが null かどうかを確認します。 |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成）をポインタから削除し、指すオブジェクトが (共有の場合は管理し、弱の場合は追跡) 同じであることを保証します。 |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 指すオブジェクトを設定します。 |
| void [reset](../smartptr/reset/)() | ポインタを nullptr に設定します。 |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | ポインタモードを設定します。参照オブジェクトの参照カウントが変わる可能性があります。 |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 指すオブジェクト（存在する場合）で SetTemplateWeakPtr() メソッドを呼び出します。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 必要なモードの [SmartPtr](../smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 必要なモードの null ポインタ [SmartPtr](../smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](../smartptr/) を作成するか、生ポインタを [SmartPtr](../smartptr/) に変換します。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) オブジェクトをコピー構築します。両ポインタはその後同じオブジェクトを指します。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) オブジェクトをコピー構築します。両ポインタはその後同じオブジェクトを指します。許可されていれば型変換を行います。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) オブジェクトをムーブ構築します。実質的に、同じモードの2つのポインタを交換します。呼び出し後、x は使用不能になることがあります。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 参照配列の型を異なる型の新しい配列を作成して変換します。C# で配列型キャストが可能だが C++ ではサポートされていない場合に有用です。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | 空の配列を初期化します。いくつかの C# コード構成を変換するために使用されます。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) を構築します。これは ptr の初期値と所有情報を共有しますが、無関係で管理されていないポインタ p を保持します。 |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 指すオブジェクトに static\_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 任意のポインタ型を [Object](../object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pointee_ 型の [System::TypeInfo](../typeinfo/) オブジェクトを取得するショートカットです。 |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | null ポインタを作成します。 |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | 指定されたオブジェクトへの弱ポインタを作成します。 |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | ptr が指す同じポインタを参照する弱ポインタを作成します。 |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | x が指す同じポインタを参照する弱ポインタを作成します。 |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | 弱ポインタをコピー構築します。 |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | 弱ポインタをコピー構築します。 |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | 弱ポインタをムーブ構築します。 |
|  [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) オブジェクトを破棄します。必要に応じて、指すオブジェクトの参照カウンタを減らし、オブジェクトを削除します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [SmartPtr_](./smartptr_/) | 対応する [SmartPtr](../smartptr/) クラスのエイリアスです。 |
| [WeakPtr_](./weakptr_/) | 自身の型のエイリアスです。 |
| [Pointee_](./pointee_/) | 指す型です。 |

## 参照

* クラス [SmartPtr](../smartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)