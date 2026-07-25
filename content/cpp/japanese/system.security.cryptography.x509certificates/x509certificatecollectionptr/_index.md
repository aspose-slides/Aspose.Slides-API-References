---
title: X509CertificateCollectionPtr
second_title: Aspose.Slides for C++ APIリファレンス
description: X509 証明書のコレクションへのポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡すべきです。
type: docs
weight: 92
url: /ja/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr クラス

X509 証明書のコレクションへのポインタです。この型は他のオブジェクトの削除を管理するポインタです。スタック上に割り当て、関数には値渡しまたは const 参照で渡すべきです。

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## Methods

| メソッド | 説明 |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [begin()](../../system/smartptr/begin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | ポインタをその自身の型にキャストします。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast を使用してポインタを基底型にキャストします。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast を使用してポインタを派生型にキャストします。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [cbegin()](../../system/smartptr/cbegin/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [cend()](../../system/smartptr/cend/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 指すオブジェクトに const_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 指すオブジェクトに dynamic_cast を使用してポインタを別の型にキャストします。 |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) メソッドへのアクセサ（基底コレクション）。SmartPtr_ が [end()](../../system/smartptr/end/) メソッドを持つ特殊化型である場合にのみコンパイルされます。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 指すオブジェクトを取得します。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | ポインタモードを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 指すオブジェクトを取得しますが、ポインタが共有モードであることをアサートします。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 参照先オブジェクトに存在する共有ポインタの数（現在のポインタを含む）を取得します。現在のポインタが共有モードであることをアサートします。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 指すオブジェクトで [GetHashCode()](../../system/smartptr/gethashcode/) を呼び出します。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 現在参照されているオブジェクト（存在する場合）を取得します。存在しなければ例外をスローします。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 指すオブジェクト（存在する場合）または nullptr を取得します。[get()](../../system/smartptr/get/) と同等です。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 参照オブジェクトを取得します。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 指すオブジェクト（存在する場合）または nullptr を取得します。[get()](../../system/smartptr/get/) と同等です。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 指すオブジェクトが特定の型またはその子型であるかをチェックします。C# の 'is' セマンティクスに従います。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ポインタが所有オブジェクト以外（エイリアシングコンストラクタで作成）を指しているかをチェックします。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ポインタが共有モードであるかをチェックします。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ポインタが弱参照モードであるかをチェックします。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ポインタが nullptr でないかをチェックします。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ポインタが nullptr であるかをチェックします。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 指すオブジェクトへの参照を取得します。ポインタが nullptr でないことをアサートします。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 参照オブジェクトのメンバーにアクセスできます。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) クラスに対して less 比較セマンティクスを提供します。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) オブジェクトに対してムーブ代入を行います。x は使用不能になります。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) オブジェクトに対してコピー代入を行います。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) オブジェクトに対してコピー代入を行います。必要な型変換を行います。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 生ポインタを [SmartPtr](../../system/smartptr/) オブジェクトに割り当てます。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ポインタの値を nullptr に設定します。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ポインタが nullptr を指しているかをチェックします。 |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | アクセサ。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | エイリアシング（エイリアシングコンストラクタで作成）をポインタから除去し、指すオブジェクトが同一であることを（共有の場合は管理し、弱参照の場合はトラッキング）保証します。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 指すオブジェクトを設定します。 |
| void [reset](../../system/smartptr/reset/)() | ポインタを nullptr を指すようにします。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ポインタモードを設定します。参照オブジェクトの参照カウントが変わる可能性があります。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 指すオブジェクト（存在する場合）で SetTemplateWeakPtr() メソッドを呼び出します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 必要なモードの nullptr ポインタ [SmartPtr](../../system/smartptr/) オブジェクトを作成します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 指定されたオブジェクトを指す [SmartPtr](../../system/smartptr/) を作成するか、生ポインタを [SmartPtr](../../system/smartptr/) に変換します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。その後、両方のポインタは同一オブジェクトを指します。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをコピー構築します。その後、両方のポインタは同一オブジェクトを指します。許可されていれば型変換を行います。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) オブジェクトをムーブ構築します。実質的に、両ポインタが同じモードであれば交換します。呼び出し後、x は使用不能になる可能性があります。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 参照配列の型を異なる型の新しい配列を作成して変換します。C# の配列型キャストで C++ でサポートされていない場合に有用です。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 空の配列を初期化します。C# のコード構文の変換に使用されます。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ptr の初期値と所有情報を共有しつつ、無関係で非管理のポインタ p を保持する [SmartPtr](../../system/smartptr/) を構築します。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 指すオブジェクトに static_cast を使用してポインタを別の型にキャストします。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 任意のポインタ型を [Object](../../system/object/) へのポインタに変換します。Pointee_ 型が完全である必要はありません。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ 型に対する [System::TypeInfo](../../system/typeinfo/) オブジェクトへのショートカットを取得します。 |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | nullptr コンストラクタ。 |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | コンストラクタ。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) オブジェクトを破棄します。必要に応じて、指すオブジェクトの参照カウントを減らし、オブジェクトを削除します。 |

## 参照

* クラス [SmartPtr](../../system/smartptr/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../)
* ライブラリ [Aspose.Slides](../../)