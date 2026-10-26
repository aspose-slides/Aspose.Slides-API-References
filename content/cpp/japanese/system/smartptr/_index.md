---
title: SmartPtr
second_title: Aspose.Slides for C++ API リファレンス
description: "ヒープ上に割り当てられる型をラップするポインタクラスです。Object を継承するクラスのメモリ管理に使用します。このポインタ型は侵入型ポインタのセマンティクスに従います。参照カウンタは Object 自身または Object インスタンスに tightly 結び付けられたカウンタ構造体に格納されます。いずれの場合も、SmartPtr インスタンスは作成方法に関わらず単一所有グループを形成し、std::shared_ptr クラスの動作とは異なります。生ポインタを SmartPtr に変換することは、同一オブジェクトへの共有参照を保有する他の SmartPtr インスタンスが存在する限り安全です。SmartPtr クラスインスタンスは共有ポインタと弱ポインタの 2 つの状態のいずれかになります。オブジェクトを存続させるには、共有参照のカウントが正である必要があります。弱ポインタも共有ポインタも、指し示すオブジェクトへのメソッド呼び出しやフィールドの読取・書込などに使用できますが、弱ポインタは共有ポインタの参照カウントには参加しません。最後の 'shared' SmartPtr が破棄されると Object は削除されます。したがって、オブジェクトのコンストラクタやデストラクタの間など、他に共有 SmartPtr が存在しない場合にこのことが起きないようにしてください。C++ コードでは System::Object::ThisProtector センティナルオブジェクト、C# では CppCTORSelfReference または CppSelfReference 属性を使用してこの問題を解決します。同様に、C++ では System::WeakPtr ポインタクラスや System::SmartPtrMode::Weak ポインタモード、C# では CppWeakPtr 属性を使用してループ参照を解消してください。複数のオブジェクトが 'shared' ポインタで相互参照すると、決して削除されません。実行時にポインタタイプ（弱または共有）を切り替える必要がある場合は、System::SmartPtr<T>::set_Mode() メソッドまたは System::DynamicWeakPtr クラスを使用してください。SmartPtr クラスは仮想メソッドを持ちません。独自のメモリ管理戦略を作成する場合にのみ継承すべきです。この型は他オブジェクトの削除を管理するためのポインタで、スタック上に割り当て、値渡しまたは const 参照で関数に渡すべきです。"
type: docs
weight: 1236
url: /ja/system/smartptr/
---
## SmartPtr クラス

Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```

### テンプレートパラメータ

| Parameter | Description |
| --- | --- |
| T | Type of the pointed object. Must be either [System::Object](../object/) or subclass of it. |

## メソッド

| Method | Description |
| --- | --- |
| auto [begin](./begin/)() | 基底コレクションの [begin()](./begin/) メソッドへのアクセサです。SmartPtr_ が [begin()](./begin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [begin](./begin/)() const | 基底コレクションの [begin()](./begin/) メソッドへのアクセサです。SmartPtr_ が [begin()](./begin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | ポインタをその型自身にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | static_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](./cbegin/)() const | 基底コレクションの [cbegin()](./cbegin/) メソッドへのアクセサです。SmartPtr_ が [cbegin()](./cbegin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [cend](./cend/)() const | 基底コレクションの [cend()](./cend/) メソッドへのアクセサです。SmartPtr_ が [cend()](./cend/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | 指すオブジェクトに対して const_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | 指すオブジェクトに対して dynamic_cast を使用してポインタを別の型にキャストします。 |
| auto [end](./end/)() | 基底コレクションの [end()](./end/) メソッドへのアクセサです。SmartPtr_ が [end()](./end/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [end](./end/)() const | 基底コレクションの [end()](./end/) メソッドへのアクセサです。SmartPtr_ が [end()](./end/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| [Pointee_](./pointee_/) * [get](./get/)() const | 指し示すオブジェクトを取得します。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | ポインタが共有モードであることをアサートしつつ、指し示すオブジェクトを取得します。 |
| int [get_shared_count](./get_shared_count/)() const | 参照オブジェクトに存在する共有ポインタの数（現在のポインタを含む）を取得します。現在のポインタが共有モードであることをアサートします。 |
| int [GetHashCode](./gethashcode/)() const | 指し示すオブジェクトの [GetHashCode()](./gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | 現在参照しているオブジェクト（存在する場合）を取得し、存在しない場合は例外をスローします。 |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | 指し示すオブジェクト（存在する場合）を取得し、存在しない場合は nullptr を返します。[get()](./get/) と同等です。 |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | 参照されているオブジェクトを取得します。 |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | 指し示すオブジェクト（存在する場合）を取得し、存在しない場合は nullptr を返します。[get()](./get/) と同等です。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | 指し示すオブジェクトが特定の型またはその子型であるかをチェックします。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | ポインタが所有しているオブジェクトとは異なるオブジェクトを指しているか（エイリアシングコンストラクタで作成された場合）をチェックします。 |
| **bool** [IsShared](./isshared/)() const | ポインタが共有モードであるかをチェックします。 |
| **bool** [IsWeak](./isweak/)() const | ポインタが弱モードであるかをチェックします。 |
| explicit  [operator bool](./operator_bool/)() const | ポインタが null でないかをチェックします。 |
| **bool** [operator!](./operator_not/)() const | ポインタが null であるかをチェックします。 |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | 指し示すオブジェクトへの参照を取得します。ポインタが null でないことをアサートします。 |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | 参照オブジェクトのメンバーにアクセスできます。 |
| **bool** [operator<](./operator_less/)(Y *) const | [SmartPtr](./) クラスに対して less 比較セマンティクスを提供します。 |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | [SmartPtr](./) クラスに対して less 比較セマンティクスを提供します。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | [SmartPtr](./) オブジェクトをムーブ代入します。x は使用不能になります。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | [SmartPtr](./) オブジェクトをコピー代入します。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | [SmartPtr](./) オブジェクトをコピー代入します。必要な型変換を行います。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | 生ポインタを [SmartPtr](./) オブジェクトに割り当てます。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | ポインタの値を nullptr に設定します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ポインタが nullptr を指しているかをチェックします。 |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成された）をポインタから除去し、指すオブジェクトが（共有の場合は管理、弱の場合は追跡）同一であることを保証します。 |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | 指し示すオブジェクトを設定します。 |
| void [reset](./reset/)() | ポインタを nullptr を指すようにします。 |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | ポインタモードを設定します。参照オブジェクトの参照カウントが変更される可能性があります。 |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | 指し示すオブジェクト（存在する場合）で SetTemplateWeakPtr() メソッドを呼び出します。 |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | 必要なモードの [SmartPtr](./) オブジェクトを作成します。 |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 必要なモードの null-pointer [SmartPtr](./) オブジェクトを作成します。 |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](./) を作成するか、生ポインタを [SmartPtr](./) に変換します。 |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) オブジェクトをコピー構築します。両ポインタはその後同じオブジェクトを指します。 |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) オブジェクトをコピー構築します。両ポインタはその後同じオブジェクトを指します。許可されていれば型変換を行います。 |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) オブジェクトをムーブ構築します。実質的に、両方が同じモードであれば二つのポインタを交換します。呼び出し後、x は使用不能になる可能性があります。 |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 参照配列の型を異なる型の新しい配列を作成して変換します。C# に配列型キャストがあり C++ でサポートされていない場合に有用です。 |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | 空の配列を初期化します。いくつかの C# コード構造の翻訳に使用されます。 |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ptr の初期値と所有情報を共有しながら、無関係で管理されていないポインタ p を保持する [SmartPtr](./) を構築します。 |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | 指し示すオブジェクトに対して static_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | 任意のポインタ型を [Object](../object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | [System::TypeInfo](../typeinfo/) 型のオブジェクトを取得するショートカットです。 |
|  [~SmartPtr](./~smartptr/)() | [SmartPtr](./) オブジェクトを破棄します。必要に応じて、指し示すオブジェクトの参照カウンタを減らし、オブジェクトを削除します。 |

## 型エイリアス

| Typedef | Description |
| --- | --- |
| [Pointee_](./pointee_/) | 指し示す型。 |
| [SmartPtr_](./smartptr_/) | 特殊化されたスマートポインタ型。 |
| [ArrayType](./arraytype/) | [System::Array](../array/) の特殊化であれば Pointee_ と同じで、そうでなければ void です。 |
| [ValueType](./valuetype/) | 指し示す配列のストレージ型。T が [System::Array](../array/) の特殊化である場合にのみ意味があります。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)