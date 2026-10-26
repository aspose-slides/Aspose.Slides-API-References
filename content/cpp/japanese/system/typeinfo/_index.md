---
title: TypeInfo
second_title: Aspose.Slides for C++ APIリファレンス
description: 特定の型を表し、その情報を提供します。
type: docs
weight: 1379
url: /ja/system/typeinfo/
---
## TypeInfo クラス


特定の型を表し、その情報を提供します。

```cpp
class TypeInfo
```

## メソッド

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | 指定された属性を型の属性リストに追加します。 |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | 型 T のデフォルトコンストラクタを設定します。 |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | クラス インスタンスを作成するファンクタによってデフォルトコンストラクタを設定します。 |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | 指定されたメンバーを型のメンバーリストに追加します。 |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | 複数の Boxed* クラスで共有できるように、**BoxedValue** 型に対してユニークな [TypeInfo](./) 構造体を提供します。 |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | 未実装です。現在のオブジェクトが表す型が宣言されているアセンブリへのポインタを返します。 |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | 未実装です。現在のオブジェクトが表す型のアセンブリ名を含む完全修飾名を返します。 |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | 基底型ディスクリプタを返します。 |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | 現在の Type オブジェクトが、具体的な型で置き換えられていない型パラメータを持っているかどうかを示す値を取得します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | 指定された名前を持つメンバーのリストを取得します。 |
| [String](../string/) [get_FullName](./get_fullname/)() const | 現在のオブジェクトが表す型の完全修飾名（アセンブリ名は除く）を返します。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | この型のジェネリック型引数の配列を取得します。 |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Type が抽象であり、オーバーライドが必要かどうかを示す値を取得します。 |
| **bool** [get_IsArray](./get_isarray/)() const | 型が配列であるかどうかを示す値を取得します。 |
| **bool** [get_IsClass](./get_isclass/)() const | Type がクラスまたはデリゲートであるかどうか（すなわち、値型またはインターフェイスではないか）を示す値を取得します。 |
| **bool** [get_IsEnum](./get_isenum/)() const | 現在の Type が列挙型を表すかどうかを示す値を取得します。 |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | 現在の Type が、他のジェネリック型を構築できるジェネリック型定義を表すかどうかを示す値を取得します。 |
| **bool** [get_IsInterface](./get_isinterface/)() const | Type がインターフェイスであるかどうか（すなわち、クラスまたは値型ではないか）を示す値を取得します。 |
| **bool** [get_IsSealed](./get_issealed/)() const | Type が sealed として宣言されているかどうかを示す値を取得します。 |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Type が値型であるかどうかを示す値を取得します。 |
| **bool** [get_IsVisible](./get_isvisible/)() const | Type がアセンブリ外のコードからアクセス可能かどうかを示す値を取得します。 |
| [String](../string/) [get_Name](./get_name/)() const | 現在のオブジェクトが表す型の名前を返します。 |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Type の名前空間を取得します。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | 指定された配列の型に一致するパラメータを持つパブリックインスタンスコンストラクタを検索します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 指定された BindingFlags を使用して、現在の Type に定義されたコンストラクタを検索します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | 現在の Type に定義されたすべてのパブリックコンストラクタを返します。 |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | 指定された型を持ち、現在のオブジェクトが表す型に適用されたカスタム属性を検索します。 |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | 型に適用されたすべてのカスタム属性を表すオブジェクトの配列を返します。 |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | 型に適用された特定の属性を表すオブジェクトの配列を返します。 |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | 未実装です。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 指定されたバインディング制約を使用して、指定されたフィールドを検索します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 指定されたバインディング制約を使用して、現在の Type に定義されたフィールドを検索します。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | この型のジェネリック型引数の配列を取得します。 |
| int [GetHashCode](./gethashcode/)() const | このインスタンスに関連付けられたハッシュコードを返します。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | 現在の Type が実装または継承しているすべてのインターフェイスを取得します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | 指定された名前を持つメンバーのリストを取得します。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | 指定された名前のメソッドを取得します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | 現在の Type のすべてのパブリックプロパティを返します。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 指定されたバインディング制約を使用して、現在の Type のプロパティを検索します。 |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | テンプレートパラメータ型ディスクリプタを取得します。 |
| **uint32_t** [Hash](./hash/)() const | 現在のオブジェクトが表す型に関連付けられたハッシュ値を返します。 |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | 指定された型のインスタンスを現在の型の変数に代入できるかどうかを判断します。 |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | 未実装です。指定された型またはその派生型の属性がこのメンバーに適用されているかどうかを示します。 |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 指定されたオブジェクトが現在の型のインスタンスかどうかを判断します。 |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | 現在のオブジェクトが表す型が、指定されたクラスのサブクラスであるかどうかを判断します。 |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | 現在の [TypeInfo](./) オブジェクトと指定されたオブジェクトが等しくないかどうかを判断します。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 現在の [TypeInfo](./) オブジェクトが null オブジェクトではないか（すなわち、何らかの型を表すか）を判断します。 |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | 現在の [TypeInfo](./) オブジェクトと指定されたオブジェクトが等しいかどうかを判断します。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 現在の [TypeInfo](./) オブジェクトが null オブジェクトか（すなわち、型を表さないか）を判断します。 |
| void [reset](./reset/)() | [TypeInfo](./) を null に設定します。 |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Type が値型であるかどうかを示す値を設定します。 |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | 基底型ディスクリプタを設定します。 |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | テンプレートパラメータ型ディスクリプタを設定します。 |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | 指定された文字列のハッシュを計算します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す型の名前を含む文字列を返します。 |
| static const [TypeInfo](./)\& [Type](./type/)() | [TypeInfo](./) クラスを表す [TypeInfo](./) オブジェクトを返します。 |
|  [TypeInfo](./typeinfo/)() | デフォルトコンストラクタ（型が設定されていません）。 |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | ヌルオブジェクトコンストラクタ（型が設定されていません）。 |
|  [TypeInfo](./typeinfo/)(const char_t *) | コンストラクタ。 |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | コンストラクタ。 |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | コンストラクタ。 |
## フィールド

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | [TypeInfo](./) の空リストを表す定数です。 |
| static [EmptyTypes](./emptytypes/) | [TypeInfo](./) の空リストを表す定数です。 |
## 型定義

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | 型を構築する関数ポインタです。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)