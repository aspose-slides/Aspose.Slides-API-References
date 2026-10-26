---
title: TypeInfo
second_title: Aspose.Slides for C++ API 參考
description: 表示特定類型並提供關於它的資訊。
type: docs
weight: 1379
url: /zh-hant/system/typeinfo/
---
## TypeInfo 類別

表示特定類型並提供關於它的資訊。

```cpp
class TypeInfo
```
## Methods

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | 將指定的屬性新增至類型屬性的清單中。 |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | 設定類型 T 的預設建構函式。 |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | 使用建立類別實例的函子設定預設建構函式。 |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | 將指定的成員新增至類型成員的清單中。 |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | 提供唯一的 [TypeInfo](./) 結構給 **BoxedValue** 類型，以供多個 Boxed* 類別共享。 |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | 未實作。傳回指向宣告此物件所代表之類型之組件的指標。 |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | 未實作。傳回此物件所代表之類型的完整限定名稱（包括組件名稱）。 |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | 傳回基底類型描述子。 |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | 取得指示目前 Type 物件是否具有尚未被具體類型取代之類型參數的值。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | 取得具有指定名稱的成員清單。 |
| [String](../string/) [get_FullName](./get_fullname/)() const | 傳回此物件所代表之類型的完整限定名稱（但不含組件名稱）。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | 取得此類型的泛型型別參數陣列。 |
| **bool** [get_IsAbstract](./get_isabstract/)() const | 取得指示 Type 是否為抽象且必須被覆寫的值。 |
| **bool** [get_IsArray](./get_isarray/)() const | 取得指示類型是否為陣列的值。 |
| **bool** [get_IsClass](./get_isclass/)() const | 取得指示 Type 為類別或委派的值；亦即非值型別或介面。 |
| **bool** [get_IsEnum](./get_isenum/)() const | 取得指示目前 Type 是否為列舉的值。 |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | 取得指示目前 Type 是否為可用於建構其他泛型類型之泛型類型定義的值。 |
| **bool** [get_IsInterface](./get_isinterface/)() const | 取得指示 Type 為介面的值；亦即非類別或值型別。 |
| **bool** [get_IsSealed](./get_issealed/)() const | 取得指示 Type 已宣告為 sealed 的值。 |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | 取得指示 Type 為值型別的值。 |
| **bool** [get_IsVisible](./get_isvisible/)() const | 取得指示 Type 是否可被組件外的程式碼存取的值。 |
| [String](../string/) [get_Name](./get_name/)() const | 傳回此物件所代表之類型的名稱。 |
| [String](../string/) [get_Namespace](./get_namespace/)() const | 取得 Type 的命名空間。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | 搜尋其參數與指定陣列中的型別相符的公共實例建構函式。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的 BindingFlags 搜尋目前 Type 定義的建構函式。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | 傳回目前 Type 定義的所有公共建構函式。 |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | 搜尋具有指定類型且套用於此物件所代表之類型的自訂屬性。 |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | 傳回包含代表套用於該類型之所有自訂屬性的物件陣列。 |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | 傳回包含代表套用於該類型之特定屬性的物件陣列。 |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | 未實作。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的繫結限制搜尋指定欄位。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的繫結限制搜尋目前 Type 定義的欄位。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | 取得此類型的泛型型別參數陣列。 |
| int [GetHashCode](./gethashcode/)() const | 傳回與此實例關聯的雜湊碼。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | 取得目前 Type 所實作或繼承的所有介面。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | 取得具有指定名稱的成員清單。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | 取得具有指定名稱的方法。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | 傳回目前 Type 的所有公共屬性。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的繫結限制搜尋目前 Type 的屬性。 |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | 取得模板參數類型描述子。 |
| **uint32_t** [Hash](./hash/)() const | 傳回與此物件所代表之類型關聯的雜湊值。 |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | 判斷指定類型的實例是否可指派給目前類型的變數。 |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | 未實作。指示是否已將指定類型或其衍生類型的其中一個或多個屬性套用於此成員。 |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 判斷指定物件是否為目前類型的實例。 |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | 判斷此物件所代表之類型是否為指定類別的子類別。 |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | 判斷目前及指定的 [TypeInfo](./) 物件是否不相等。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 判斷目前的 [TypeInfo](./) 物件是否非 null 物件，即它代表某個類型。 |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | 判斷目前及指定的 [TypeInfo](./) 物件是否相等。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 判斷目前的 [TypeInfo](./) 物件是否為 null 物件，即不代表任何類型。 |
| void [reset](./reset/)() | 將 [TypeInfo](./) 設為 null。 |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | 設定指示 Type 為值型別的值。 |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | 設定基底類型描述子。 |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | 設定模板參數類型描述子。 |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | 計算指定字串的雜湊。 |
| [String](../string/) [ToString](./tostring/)() const | 傳回包含此物件所代表之類型名稱的字串。 |
| static const [TypeInfo](./)\& [Type](./type/)() | 傳回一個代表 [TypeInfo](./) 類別的 [TypeInfo](./) 物件。 |
|  [TypeInfo](./typeinfo/)() | 預設建構函式（未設定類型）。 |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | null 物件建構函式（未設定類型）。 |
|  [TypeInfo](./typeinfo/)(const char_t *) | 建構函式。 |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | 建構函式。 |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | 建構函式。 |
## 欄位

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | 代表空的 [TypeInfo](./) 列表之常數。 |
| static [EmptyTypes](./emptytypes/) | 代表空的 [TypeInfo](./) 列表之常數。 |
## 型別別名

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | 用於建構類型的函式指標。 |
## 相關參考

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)